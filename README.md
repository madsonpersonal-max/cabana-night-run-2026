# Cabana Night Run 2026 — V9.0

Versão de homologação focada em Empresas/Lotes, reserva de estoque e separação financeira.

## Regras V9.0
- Criar lote reserva imediatamente as vagas restantes do estoque da modalidade.
- Disponíveis = total - utilizadas - reservadas por empresas.
- Atleta de empresa não gera cobrança individual nem comprovante.
- Pagamento fica associado ao lote empresarial.
- Atleta vinculado consome saldo do lote, sem reduzir novamente o estoque público.
- Lote não pode exceder o saldo público disponível para reserva.
- Liberação de saldo restante devolve as vagas ao estoque público.
- Limite central não pode ser reduzido abaixo de vagas utilizadas + reservadas.

Homologação local com localStorage; produção deve usar backend/banco transacional.
