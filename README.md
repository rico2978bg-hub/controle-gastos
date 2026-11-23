# Controle de gastos

Controle de gastos do mês, feito em um único arquivo HTML: HTML, CSS e JavaScript puros, sem servidor e sem nenhuma API paga.

- Orçamento mensal salvo no navegador.
- Registro de gastos com descrição, valor e categoria (Alimentação, Transporte, Lazer, Contas, Outros).
- Cards com o total gasto e quanto sobra. O valor da sobra fica vermelho quando passa do orçamento.
- Lista dos gastos do mês, com × para remover.
- Dica automática: mostra a categoria que mais pesa, com a porcentagem, ou avisa quando o orçamento estoura.
- Resumo do mês em português: quanto ainda dá para gastar por dia, para onde foi o dinheiro e sugestões concretas de economia, com o valor estimado.

Só os gastos do mês atual entram no total. Os valores são guardados em centavos, para a soma não ter erro de arredondamento.

## Como usar

Abra o `index.html` no navegador, ou use o link do GitHub Pages do repositório.

Os dados ficam no `localStorage` do navegador, nas chaves `gastos_orcamento` e `gastos_lista`.
