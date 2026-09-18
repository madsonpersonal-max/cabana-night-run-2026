# Cabana Night Run 2026 — V9.9
## Relatórios corrigidos

Correções:
- Modalidade inicia em “Todas”.
- PCD é reconhecido pela modalidade/campo PCD, mesmo quando a origem técnica é PRESENCIAL.
- Atleta vinculado a empresa/lote é classificado como EMPRESA mesmo quando o cadastro operacional gravou origem PRESENCIAL.
- Bonificação é identificada pela origem e pelos campos de bonificação.
- CPF duplicado não é escondido: continua visível e passa a ser destacado como inconsistência.
- Resumo de empresas/lotes mostra contratadas, utilizadas e restantes.
- Dashboard/relatório devem ser conferidos com a mesma base lógica.
- Exportação CSV inclui empresa e lote.
- Valor confirmado considera apenas registros confirmados.

Homologação local: a regra definitiva de unicidade de CPF deve ser aplicada também no backend/BD de produção.
