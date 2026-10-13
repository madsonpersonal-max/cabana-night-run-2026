# Cabana Night Run 2026 — ADM V1.0

## Objetivo
Primeira base administrativa enxuta, com foco em Dashboard, Patrocínios, Empresas e Central de Vagas. Inclui Auditoria local de apoio.

## Regras preservadas
- Corrida 7 km: 1.000 vagas totais.
- PCD: até 10 vagas gratuitas dentro das 1.000 vagas da corrida; nunca estoque adicional.
- Corridinha infantil: 100 vagas totais, com 50 liberadas inicialmente.
- Compra/reserva de empresa é registrada como lote, não cria inscrições individuais.
- Recibo administrativo informa empresa, CNPJ, modalidade, quantidade, valor por vaga, total e status.
- Bonificações são consideradas na Central de Vagas por contagem de conciliação manual; o módulo individual de bonificações não faz parte deste ADM reduzido.
- Identidade visual escura com acento terra cota.

## Limitações importantes
Esta versão é um protótipo front-end. Dados ficam no `localStorage` do navegador e não são compartilhados entre usuários/dispositivos. Não há login, controle de permissões no servidor, banco de dados, upload real de listas, integração com inscrições, confirmação bancária nem WhatsApp. Não usar como sistema oficial em produção.

## Publicação para homologação
Subir `index.html` para uma pasta ou repositório GitHub Pages de homologação. Evitar substituir o sistema público de inscrições. A publicação no Pages não transforma `localStorage` em base compartilhada.

## Testes mínimos antes de homologar
1. Cadastrar/editar/excluir patrocinador.
2. Cadastrar/editar/excluir empresa e gerar recibo.
3. Validar limite de vagas e bloqueio de quantidade acima da capacidade.
4. Atualizar Central de Vagas e conferir Dashboard.
5. Exportar backup JSON e validar o arquivo.
6. Testar em desktop e celular.
