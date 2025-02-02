# Projeto de Análise de Dados: Avaliação de Vinhos

## projeto
- Verifique o projeto aqui [Clique Aqui](https://github.com/silascosta/Analise-de-dados-de-vinhos/blob/master/An%C3%A1lise%20Exploratoria%20Dataset%20de%20Vinhos.ipynb) 



## Sumário
Este projeto tem como objetivo analisar dados de vinhos, incluindo suas características, avaliação de qualidade, e preços. O dataset contém diversas informações sobre os vinhos, como o país de origem, a descrição, o tipo de uva, a pontuação, o preço, entre outras variáveis. A análise busca identificar padrões e insights sobre o mercado de vinhos, como correlação entre preço e qualidade, os melhores vinhos por faixa de preço, e as regiões ou variedades de uvas que se destacam nas avaliações.

## Descrição dos Dados

O conjunto de dados possui as seguintes colunas:

- **unnamed**: Coluna de índice.
- **country**: País onde o vinho foi produzido.
- **description**: Descrição do vinho.
- **designation**: Um termo que identifica a origem, tipo ou características específicas do vinho.
- **points**: Pontuação que o vinho obteve em sua avaliação (de 80 a 100 pontos).
- **price**: Preço da garrafa do vinho.
- **province**: Província onde o vinho foi produzido.
- **region_1**: Região onde o vinho foi produzido.
- **region_2**: Região mais específica dentro da região 1.
- **taster_name**: Nome do avaliador.
- **taster_twitter_handle**: Perfil do Twitter do avaliador.
- **title**: Nome do vinho.
- **variety**: Tipo de uva utilizada no vinho.
- **winery**: Adega responsável pela produção do vinho.

## Classificação dos Vinhos por Pontuação

A classificação dos vinhos de acordo com a pontuação obtida é a seguinte:

- **80 - 82**: Aceitável
- **83 - 86**: Bom
- **87 - 89**: Muito Bom
- **90 - 93**: Excelente
- **94 - 97**: Soberbo
- **98 - 100**: Clássico


## Análises Realizadas
### 1. Quais países possuem os vinhos com maior pontuação?
A análise busca identificar quais países têm os vinhos com as melhores avaliações.

### 2. Há alguma correlação entre o preço do vinho e sua pontuação?
Foi realizada uma análise estatística para verificar se existe uma relação entre o preço da garrafa e a pontuação do vinho, o que pode indicar se vinhos mais caros tendem a ter avaliações mais altas.

### 3. Quais são as uvas mais utilizadas nos vinhos com maior avaliação?
Com base nas pontuações mais altas, é possível identificar quais tipos de uvas são mais comuns entre os vinhos mais bem avaliados.

### 4. Qual o melhor vinho em cada faixa de preço?
A análise foi conduzida para determinar qual vinho recebe a maior pontuação dentro de cada faixa de preço. Isso ajuda a identificar quais vinhos oferecem o melhor custo-benefício em suas respectivas faixas.

## Faixas de preço definidas

- Até **10** Dolares
- Entre **10 e 25** Dolares
- Entre **25 e 40** Dolares
- Entre **40 e 55** Dolares
- Acima de **55** Dolares


## Como Rodar o Projeto: 
- Ter anaconda instalado