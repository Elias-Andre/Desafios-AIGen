# Desafios AI Generativa

🚀 Desafios de código do curso de AI Generativa da Nexa em parceria com a DIO. 🚀


## 💻 Stack utilizada

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

## 🤔 Apêndice

        1. Geração de conteúdo;
        2. O melhor modelo de IA;
        3. Selecionando um Modelo;





## 🖋️ Descrição

### 1. Geração de Conteúdo
#### Descrição
Você está desenvolvendo um sistema de geração de sugestões de tópicos para um blog de tecnologia. O objetivo é associar características específicas dos modelos Claude 3 da Anthropic às palavras-chave fornecidas e fornecer o nome do modelo correspondente como saída.

#### Entrada
Uma descrição correspondente a um dos modelos Claude 3 da Anthropic, como "automatizar tarefas" ou "equilíbrio ideal entre inteligência e velocidade".

#### Saída
O nome do modelo Claude 3 que melhor corresponde à característica fornecida na entrada, como "Claude 3 Opus", "Claude 3 Sonnet" e "Claude 3 Haiku". Caso a entrada não possua características dos modelos citados acima, o programa deve retornar uma mensagem: Modelo não encontrado.

### 2.  O Melhor Modelo de IA
#### Descrição
Neste desafio, o objetivo ajudar na escolha do modelo de inteligência artificial mais adequado com base em critérios específicos definidos pelo cliente, utilizando as inovações recentemente anunciadas pela Amazon Web Services (AWS). Os modelos de IA disponíveis são da família Claude 3, desenvolvidos pela Anthropic, que foram anunciados como disponíveis na plataforma Amazon Bedrock. Esses modelos de última geração foram projetados para oferecer um equilíbrio entre precisão, desempenho, velocidade e custo, atendendo às demandas de clientes de todos os tamanhos.

Atenção:
Alguns dados que utilizados são simulados e podem não representar situações reais.

#### Entrada
A entrada consiste em quatro linhas, cada uma representando uma característica do modelo de inteligência artificial:

  1. Desempenho: um número inteiro indicando a capacidade de desempenho do modelo.
  2. Velocidade: um número inteiro representando a velocidade de processamento do modelo.
  3. Custo: um número inteiro que reflete o custo associado ao modelo.
  4. Capacidades: uma lista de capacidades específicas separadas por vírgulas.

#### Saída
O programa fornecerá a recomendação do modelo mais adequado com base nas características fornecidas. A saída incluirá uma explicação detalhada sobre por que esse modelo específico foi escolhido com base nos critérios estabelecidos pelo cliente, utilizando informações sobre os modelos Claude 3 disponíveis na plataforma Amazon Bedrock. Se nenhum modelo atender aos critérios, o programa informará que nenhum modelo foi encontrado.
### 3 - Selecionando um Modelo Amazon Bedrock Ideal
### Descrição
Você foi contratado para desenvolver uma lista de dicionários chamado modelos_disponiveis contendo os modelos de inteligência artificial (IA) da Amazon Bedrock, dentro da lista crie três dicionários, sendo, nome, pontuacao_desempenho e preco_mensal, cada um deles representa um modelo disponível para recomendação e suas características.

Em seguida crie uma função chamada recomendar_modelo e receba dois parâmetros que será modelos e orçamento, que representa uma lista de modelos e o orçamento do usuário em unidades monetárias. Dentro da função recomendar_modelo verifique se o orçamento fornecido é suficiente para recomendar algum modelo. Se o orçamento for inferior a 250 unidades monetárias, a função retorna uma tupla com dois elementos:

1. "None": indicando que nenhum modelo pode ser recomendado.
2. Uma mensagem de aviso informando que o orçamento é muito baixo para recomendar um modelo adequado..

O objetivo geral do desafio é selecionar o melhor modelo que é escolhido com base no orçamento, priorizando modelos com preço mais próximo ao orçamento fornecido pelo usuário.

Detalhes dos Modelos:
  - Modelo: Claude 3 Opus. Desempenho: 9. Preço mensal: $ 600;
  - Modelo: Claude 3 Sonnet. Desempenho: 8. Preço mensal: $ 450;
  - Modelo: Claude 3 Haiku. Desempenho: 7. Preço mensal: $ 350;

Atenção:
Alguns dados que utilizados são simulados e podem não representar situações reais.

#### Entrada
O usuário deve fornecer os detalhes seu orçamento para que seja avaliado o melhor modelo com base no seu orçamento pelo preço mensal e desempenho.

#### Saída
Com base nos modelos fornecidos e no orçamento especificado, a função deve recomendar o modelo adequado conforme o seu orçamento. O melhor modelo sugerido deve ser escolhido com base no orçamento, priorizando modelos com preço mais próximo ao orçamento fornecido pelo usuário. Caso o orçamento seja menor do que 250, retorne uma mensagem informando: "Se orçamento é muito baixo para recomendar um modelo adequado."
