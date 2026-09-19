# Cabana Night Run 2026 — V11.2 Importação de Atletas por Empresa

Homologação administrativa. Adiciona a função exclusiva de importação/atualização incremental de atletas em lotes empresariais.

- Baixar modelo XLSX padrão.
- Importar XLSX/CSV para lote empresarial ativo.
- Pré-validação antes de gravar.
- CPF é a chave para evitar duplicidade.
- Novos atletas são adicionados; CPFs já vinculados ao lote têm somente dados cadastrais atualizados.
- A atualização nunca exclui atletas automaticamente.
- Não altera pagamento, comprovante ou status de inscrição já existentes.
- Exige vagas disponíveis no lote para novos atletas.
- Corridinha valida idade de 4 a 12 anos em 31/12/2026 e dados do responsável.
- Registro de auditoria do Administrador.

Uso: publicar o `admin.html` no repositório `cabana-night-run-2026`.
