## **Table of Contents**
- [Extra - Estruturas de repetição](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/1a_ee_02_estruturas_de_repeticao.html&ref=master#mcetoc_1esj4slvm0) 
  - [Objetivo](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/1a_ee_02_estruturas_de_repeticao.html&ref=master#mcetoc_1f4saelkq2)
  - [Preparativos](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/1a_ee_02_estruturas_de_repeticao.html&ref=master#mcetoc_1f33pqfa48)
- [Você deverá criar um arquivo chamado kain.py.](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/1a_ee_02_estruturas_de_repeticao.html&ref=master#mcetoc_1f4saavro1)
- [Exercícios](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/1a_ee_02_estruturas_de_repeticao.html&ref=master#mcetoc_1esq74qsl4) 
- [Entregáveis](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/1a_ee_02_estruturas_de_repeticao.html&ref=master#mcetoc_1egvoav555j) 
  - [Repositório](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/1a_ee_02_estruturas_de_repeticao.html&ref=master#mcetoc_1egvrpv6k1l4)
- [Critérios de aceitação](https://npepa32v9l.execute-api.us-east-1.amazonaws.com/v2/?project_id=19989138&filename=python/outubro-20/1a_ee_02_estruturas_de_repeticao.html&ref=master#mcetoc_1eh146n6m3) 
# **Extra - Estruturas de repetição**
Nessa entrega você exercitará seus conhecimentos sobre **estruturas de repetição** e lógica elementar.
## **Objetivo**
O objetivo dessa atividade é trabalhar lógica elementar aplicada a estruturas de repetição.
## **Preparativos**
Você deverá criar um arquivo chamado kain.py.
# -----
# **Exercícios**
Defina as seguintes funções, observando os exemplos de chamada de cada uma: 

- **corresponding\_parenthesis(text)** 
  - **Parâmetros:** Um texto contendo uma certa quantidade de parêntesis, podendo ter abertura ou fechamento de parêntesis
  - **Procedimento:** A função deve verificar os parêntesis que tem correspondente, dessa forma, um parêntese aberto deve ter um parêntese fechado correspondente e vice-versa
  - **Retorno:** Uma string contendo todos os parênteses sem correspondência

\# EXEMPLO 1:

result = corresponding\_parenthesis("()()")

print(result)

\> ""

\# EXEMPLO 2:

result = corresponding\_parenthesis("()))")

print(result)

\> ))

\# EXEMPLO 3:

result = corresponding\_parenthesis(")))(((((")

print(result)

\> ((

\# EXEMPLO 4:

result = corresponding\_parenthesis(")(")

print(result)

\> ""



- **remove\_more\_than\_two\_repetitions(text)** 
  - **Parâmetros:** Um texto com algumas letras repetidas
  - **Procedimento:** A função deve remover repetições consecutiva de letras, caso se repita mais que 2 vezes, ou seja, uma letra pode se repetir no máximo duas vezes de forma consecutiva
  - **Retorno:** O texto sem letras repetidas mais que duas vezes consecutivamente

\# Exemplo 1:

text = "Ollloco meuuuu, taaa peegaando fogoo biiiiichooo"

text = remove\_more\_than\_two\_repetitions(text)

print(text)

\> Olloco meuu, taa peegaando fogoo biichoo



-----
# **Entregáveis**
## **Repositório**
- Link do **repositório** do **GitLab**
- **Código fonte:** 
  - arquivo **kain.py**.
- **Privacidade** 
  - Incluir **ka-br-out-2020-correcoes** como reporter.
-----
# **Critérios de aceitação**

|**pts**|**Dado**|**Quando**|**É esperado**|
| :-: | :-: | :-: | :-: |
|1.5|Função corresponding\_parenthesis|Executada a bateria de testes semelhante ao que foi especificado nas Entradas e Saídas|A função retorne como esperado|
|1.5|Função remove\_more\_than\_two\_repetitions|Executada a bateria de testes semelhante ao que foi especificado nas Entradas e Saídas|A função retorne como esperado|


**Boa diversão dev! 🤠**




