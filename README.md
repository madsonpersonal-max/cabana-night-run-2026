# Cabana Night Run 2026 — ADM Enxuto V1.0

Inclui quatro módulos: Dashboard, Central de Vagas, Patrocínios e Empresas.

## Regras do protótipo
- Corrida 7 km: 1.000 vagas.
- Corridinha Infantil: 100 vagas.
- Até 10 vagas PCD estão incluídas nas 1.000 vagas da corrida.
- Na Central de Vagas, preencher quantidade realizada de Site, Recepção e Bonificadas. O saldo é calculado automaticamente.
- PCD é indicador auxiliar: deve estar incluído no total de Recepção, para não ser contado duas vezes.
- Empresas são controladas por lote: quantidade comprada, usada e restante.
- Patrocínios são controlados separadamente das compras de vagas empresariais.

## Como testar
Abra index.html em navegador moderno.

## Limitação
É protótipo local: dados salvos no LocalStorage deste navegador, sem banco central ou autenticação. Não usar em produção antes da integração do TI com API, banco central, autenticação e auditoria no servidor.
