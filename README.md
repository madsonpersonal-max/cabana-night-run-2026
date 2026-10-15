# Cabana Night Run ADM V1.4 — BM pago e PCD

## Correções
- Cada BM não pago agora possui botão **Marcar pago** no histórico.
- Ao marcar pago, solicita data de recebimento; altera status para PAGO e registra ação na auditoria.
- Dashboard passa a refletir o BM como recebido após salvar.
- Vagas PCD utilizadas são descontadas do saldo da corrida, pois o usuário confirmou que estão fora do contador de inscrições online, mas continuam dentro do limite total de 1.000 vagas.
- Mantém lista de atletas anexada e botão de download da versão anterior.

## Como testar
1. No GitHub, substitua `index.html` pelo arquivo deste pacote e aguarde GitHub Pages.
2. Entre em Empresas > BMs no lote de teste.
3. Localize o BM-001 em status ENVIADO e clique **Marcar pago**.
4. Informe a data do recebimento. O status deve mudar para PAGO.
5. Confira o Dashboard: valor deve sair de BM pendente e entrar em BM recebido; confira também Auditoria.
6. Na Central de Vagas, se online=30 e PCD=5, o saldo da corrida deve descontar as 35 vagas (além de outras ocupações/reservas).

## Limitações
Protótipo de homologação em GitHub Pages/localStorage. Os dados não são compartilhados entre computadores e não há confirmação bancária automática. Recibo é administrativo, não fiscal.
