# Cabana Night Run ADM V1.3 — Correções para teste

## Ajustes desta versão
- Anexo de lista de atletas limitado a 2 MB para reduzir falhas de quota do localStorage.
- Botão para baixar novamente a lista anexada ao cadastro empresarial.
- Rótulos mais claros para vagas contratadas, utilizadas e não utilizadas.
- Recibo empresarial discrimina vagas utilizadas e não utilizadas.
- Um BM só pode ser marcado como PAGO quando houver data de recebimento.
- Tratamento de erro quando o armazenamento local está cheio.
- Dashboard diferencia BMs recebidos e BMs pendentes cadastrados; se nenhum BM foi lançado, indica isso explicitamente.

## Regras mantidas
- Corrida 7 km: 1.000 vagas totais, incluindo até 10 PCD.
- Corridinha infantil: 100 vagas totais, 50 liberadas inicialmente.
- Lista de atletas é anexo documental, não cria inscrições individuais automaticamente.
- Recibos são administrativos, não fiscais e não comprovam entrada bancária.

## Limitações
Dados e anexos ficam no navegador atual. Não há base compartilhada, autenticação de servidor ou integração com o sistema de inscrições. Testar em homologação; não usar em produção.
