# Meu dia — versão 3

Abra index.html no navegador. Para atualizar o GitHub Pages, exporte um backup no painel atual e substitua index.html na mesma branch e no mesmo repositório. Mantenha o endereço anterior para usar os mesmos dados locais.

## Financeiro

- Selecione o mês ou use as setas para navegar.
- Cadastre entradas e saídas, com categoria e vencimento.
- Escolha **Todo mês — recorrente**. Deixe o mês final vazio para repetição sem prazo final.
- A recorrência aparece automaticamente nos meses futuros e começa em aberto em cada mês.
- Para confirmar pagamento ou recebimento, clique em Editar na ocorrência, escolha Pago / recebido e informe a data efetiva.
- Editar ou excluir uma ocorrência afeta apenas aquele mês.
- Em Contas recorrentes, use Editar recorrência para mudar descrição, categoria, valor padrão e último mês. Ocorrências já salvas/editadas/pagas são preservadas.
- Dias 29, 30 e 31 são ajustados ao último dia dos meses menores, mantendo o dia original nos demais meses.

## Gráficos

O gráfico de barras compara entradas e saídas nos 12 meses do ano selecionado. A rosca mostra despesas por categoria no mês selecionado. A tabela expansível traz os valores exatos. O destaque identifica o maior gasto e eventuais empates.

**Previsto por vencimento** inclui recorrências, valores em aberto e pagos no mês de vencimento. **Pago / recebido** considera somente valores realizados, pela data efetiva. O resumo superior usa valores realizados, com pendências mostradas separadamente. O saldo é do mês; não inclui saldo bancário anterior.

Uma conta paga em outro mês pode aparecer nas listas dos dois meses para conferência, mas entra somente uma vez em cada base de cálculo.

## Dados e compatibilidade

O painel mantém agenda, atividades diárias, exportação e importação de backups. Usa a mesma chave de armazenamento da versão anterior e aceita seus backups. Contas antigas sem classificação são despesas em Outros; edite para classificar. Recorrências antigas são migradas para regras mensais sem prazo final; ajuste o último mês em Editar recorrência se a conta tiver fim definido.

Os dados ficam somente no navegador e dispositivo utilizados. Não há integração bancária, login ou sincronização em nuvem. Não envie backups pessoais ao repositório público.

Na primeira atualização, uma cópia do armazenamento anterior é preservada localmente. Se os dados não puderem ser lidos, o painel mantém o armazenamento original e permite exportar ou importar um backup, sem substituí-lo automaticamente.
