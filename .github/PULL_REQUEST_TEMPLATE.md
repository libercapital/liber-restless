<!--

Antes de abrir um PR, garanta que seu código cumpre os seguintes checks:

- Revise seu código e faça QA dele como se fosse o usuário final. Garanta que ele faz tudo o que foi descrito no JIRA.
- Dê rebase (ou faça um merge) da branch de destino com a sua e corrija conflitos.
- Verifique se não esqueceu nenhum comentário, typos ou byebugs no código.
- DRY (Don’t repeat yourself).
- KISS (Keep it simple).
- YAGNI (You ain’t gonna need it) - Não faça coisas antecipadamente se você não precisa delas ainda.
- Performance - verifique a quantidade de queries que sua mudança introduz e garanta que não há N+1s.

Caso tenha realizado todos os checks acima, continue e lembre-se de apagar seções que não fazem
sentido para esse PR ou adicionar novas seções conforme necessário.

-->

## Escopo

<!--

Breve descrição DO QUE você fez nesse pull request e POR QUE.

-->

[JIRA-###](https://liber.atlassian.net/browse/JIRA-###)

## Implementação

<!--

Uma descrição de COMO você conseguiu fazer isso.
Sugestão de tópicos para abordar aqui:
- Uma descrição de alto nível do fluxo que seu código altera ou implementa.
- O que você teve que refatorar e por qual motivo?
- Quais tradeoffs você teve que fazer na implementação?
- Existe algo que você quer que outros devs se atentem ao revisar o seu código?

-->

## Screenshots

<!-- Adicione screenshots da funcionalidade implementada caso tenha tido alguma alteração no frontend (pode copiar e colar do JIRA) -->

## Como testar

<!--

A descrição de um cenário de teste (pelo menos o happy flow) pode ajudar outros desenvolvedores que não estão familiarizados
com a parte do código que foi modificada nesse PR mas querem ver tudo funcionando antes de aprovar.
Essa seção pode incluir uma instrução passo a passo de como chegar exatamente no ponto do fluxo que seu código está alterando.
Idealmente isso já estaria no JIRA então pode ser copiado e colado aqui.

Exemplo de descrição:
- Logar com o usuário `foo` da empresa `bar` configurada com a opção `foobar`
- Clicar no botão `X` da interface
- Esperar o sistema devolver `Y`

-->

## Guia de Emojis

Emojis podem ser adicionados a comentários de review para separar comentários bloqueantes de não bloqueantes.

Exemplo: Elogios, pequenas sugestões ou perguntas que não bloqueiam um merge.

> 🟢 Curti o refactor!

> 🟡 Por que esse valor foi removido?

Exemplo: Feedbacks bloqueantes devem ser endereçados antes de um merge.

> 🔴 Essa mudança vai quebrar um fluxo importante do sistema

### Exemplos

| Tipo           | Exemplos       | Descrição                              |
| -------------- | -------------- | -------------------------------------- |
| Bloqueante     | 🔴 ❌ 🚨       | Emojis vermelhos                       |
| Não bloqueante | 🟡 💡 🤔 💭    | Emojis amarelo, pensativos, etc        |
| Elogio         | 🟢 💚 😍 👍 🙌 | Emojis verde, corações, positivos, etc |
