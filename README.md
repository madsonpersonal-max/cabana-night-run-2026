# Cabana Night Run 2026 — V10.7

Correção da aba **Inscrições**: agora consolida os registros das chaves de homologação utilizadas pelo sistema, em vez de retornar apenas a primeira chave encontrada.

- Consolida `cnr26_inscricoes_v5`, `cnr26_registrations`, `cnr26_inscricoes`, `cnr26_atletas` e `inscricoes_cnr26`.
- Evita duplicar o mesmo registro quando ele estiver replicado em mais de uma chave.
- Mantém registros realmente distintos, inclusive casos de CPF duplicado, para permitir auditoria.
- Mantém V10.6 Bonificações Completas e demais módulos.

**Homologação:** localStorage. Produção deverá usar banco de dados/API compartilhados.
