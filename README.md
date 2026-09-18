# Cabana Night Run 2026 — V10.2
## Pagamentos e controle financeiro

Incluído no ADM > Pagamentos:
- Indicadores de pagamentos em validação, confirmados e correções.
- Valor individual confirmado.
- Quantidade de isentos.
- Resumo financeiro por origem.
- Regra explícita de que atleta de empresa/lote não gera cobrança individual.
- Conferência filtrável por origem, status, CPF/nome.
- Lista com forma de pagamento, valor e tratamento da cobrança.
- Quadro separado de empresas/lotes com vagas e valor informado no lote.
- Evita dupla contagem: valor do lote fica separado dos valores individuais dos atletas.

A homologação continua usando localStorage. Em produção, pagamentos e valores devem ser validados no backend/banco, com trilha de auditoria e reconciliação com o PSP/banco quando a integração for implantada.
