# Controle de gastos

Controle de gastos do mês, feito em um único arquivo HTML: HTML, CSS e JavaScript puros, sem servidor e sem nenhuma API paga.

- Orçamento mensal salvo no navegador.
- Registro de gastos com descrição, valor e categoria (Alimentação, Transporte, Lazer, Contas, Outros).
- Cards com o total gasto e quanto sobra. O valor da sobra fica vermelho quando passa do orçamento.
- Lista dos gastos do mês, com × para remover.
- Dica automática: mostra a categoria que mais pesa, com a porcentagem, ou avisa quando o orçamento estoura.
- Resumo do mês em português: quanto ainda dá para gastar por dia, para onde foi o dinheiro e sugestões concretas de economia, com o valor estimado.

- Gastos com besteira: cada gasto pode ser marcado como besteira (o app sugere sozinho para iFood, lanche, cerveja etc.). Um cartão mostra quanto foi no mês, a porcentagem do total, quanto isso vira em 1 ano e as besteiras que mais se repetem.
- Visual de aplicativo de celular: rosca do orçamento, gráfico dos últimos 6 meses com comparação com o mês anterior, botão + que abre uma gaveta para registrar o gasto, e menu embaixo (Início, Gastos e Resumo).

Ícones: [Fluent Emoji 3D](https://github.com/microsoft/fluentui-emoji), da Microsoft (licença MIT). Sem internet, o app usa os emojis comuns do sistema.

Só os gastos do mês atual entram no total. Os valores são guardados em centavos, para a soma não ter erro de arredondamento.

## Como usar

Abra o `index.html` no navegador, ou use o link do GitHub Pages do repositório.

Os dados ficam no `localStorage` do navegador, nas chaves `gastos_orcamento` e `gastos_lista`.
