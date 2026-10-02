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

## Atualização financeira
Selecione mês e ano no campo Mês financeiro. Cadastre entradas ou saídas únicas ou recorrentes mensais (de 2 a 120 meses, incluindo o inicial). Cada ocorrência é editada e excluída individualmente. Para continuar uma série encerrada, crie outra a partir do mês seguinte. Dias 29, 30 e 31 são ajustados para o último dia dos meses menores.

Marque como Pago / recebido e informe a data efetiva: ela determina os totais realizados e o comparativo anual. A data original continua sendo o vencimento ou previsão. Os lançamentos aparecem no mês previsto e também no mês em que foram realizados, quando diferente; os totais realizados contabilizam cada um somente uma vez. O maior gasto compara somente saídas pagas do ano selecionado, indicando empates. Os registros antigos continuam funcionando, tratados como despesas únicas; backups antigos podem ser importados.

Para atualizar seu site, primeiro exporte um backup no painel atual. Substitua apenas index.html no mesmo repositório e branch usados pelo GitHub Pages, mantendo o mesmo endereço. Aguarde a publicação e atualize o navegador. O armazenamento usa a mesma chave da versão anterior.
