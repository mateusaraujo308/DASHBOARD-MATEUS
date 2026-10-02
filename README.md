# Meu dia — dashboard pessoal

Exemplo editável em português, sem instalação de dependências. Abra `index.html` no navegador para usar.

- Contas: adicionar, editar, excluir e marcar como pagas pelo formulário de edição; resumo e listagem do mês atual.
- Agenda: adicionar, editar e excluir compromissos; listagem de hoje em diante.
- Atividades: registrar por dia e marcar como concluídas; seletor de data para consultar o histórico.
- Backup: exportação e importação de JSON.

Os dados iniciais são fictícios. Os registros são guardados no armazenamento local do navegador. Não há login, integração bancária, integração com Google Agenda ou sincronização entre dispositivos. Use Exportar backup para guardar uma cópia. Limpar dados do navegador remove os registros locais. Abrir o arquivo e usar a versão hospedada são espaços de armazenamento diferentes; exporte e importe para transferir os dados.

## Colocar no GitHub

1. Crie um repositório e envie `index.html` e este `README.md` para a raiz da branch `main`.
2. No repositório, abra Settings → Pages.
3. Selecione Deploy from a branch e `main`, pasta `/ (root)`, e salve.
4. Abra o endereço exibido pelo GitHub quando a publicação terminar.

O código pode ser público; seus lançamentos não são enviados ao GitHub pelo aplicativo. Não envie backups pessoais ao repositório. Para usar os mesmos dados em vários dispositivos, será necessário acrescentar autenticação e um banco de dados.

## Personalizar

Todo o código está em `index.html`: cores no bloco CSS, interface no HTML e comportamentos no bloco JavaScript. Não exige servidor de aplicação ou processo de build.
