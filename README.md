## 🏠 Previsão de Preços de Imóveis em NYC

Neste projeto, utilizamos um conjunto de dados do Kaggle sobre anúncios do Airbnb na cidade de Nova York. Melhoramos a análise incorporando dados externos que não estão incluídos no conjunto de dados, como:

+ Taxas de criminalidade por bairro
+ Proximidade de atrações turísticas, estações de metrô e pontos de ônibus
+ Extração do número de quartos a partir dos nomes das propriedades

## 📈 Objetivo do Projeto

- Realizar uma análise exploratória de dados (EDA), demonstrando as principais características entre as variáveis e apresentando algumas hipóteses de negócios relacionadas.

- Responder às seguintes perguntas:
  
a) Supondo que uma pessoa esteja pensando em investir em um apartamento para alugar na plataforma, qual seria o melhor lugar para comprar?

b) O número mínimo de noites e a disponibilidade ao longo do ano afetam o preço?

c) Existe um padrão no texto do nome do lugar para locais de maior valor?


- Explicar como a previsão de preços pode ser feita a partir dos dados. Quais variáveis e/ou suas transformações foram utilizadas e por quê? Que tipo de problema estamos resolvendo (regressão, classificação)? Qual modelo melhor se ajusta aos dados e quais são seus prós e contras? Qual métrica de desempenho do modelo foi escolhida e por quê?

A resposta para essas perguntas está disponível no arquivo: ```estudo_airbnb_ny.ipynb```

## 🚀 Como Executar o Projeto

1. Clone o repositório utilizando o comando:
   
```git clone https://github.com/luizcaixeta/airbnb-pricing-new-york.git```

2. Instale as dependências:

Certifique-se de que o Python está instalado na sua máquina. Execute o seguinte comando para instalar as bibliotecas necessárias:

```pip install -r requirements.txt``` 

3. Arquivos necessários:

Verifique se os seguintes arquivos estão no diretório do projeto (já incluídos no repositório):

+ teste_indicium_precificacao
+ MTA_Subway_Entrances_and_Exits__2024_20250129
+ Bus_Stop_Shelter_20250201
+ crimes_por_PTC
+ PTC_por_bairros

Fontes de dados:

. 🚇 [NYC Subway Entrances and Exits (2024)](https://data.ny.gov/Transportation/MTA-Subway-Entrances-and-Exits-2024/i9wp-a4ja/about_data)

. 🚌 [Bus Stop Shelters](https://data.cityofnewyork.us/Transportation/Bus-Stop-Shelters/qafz-7myz)

. 📊 [Crime Statistics](https://www.nyc.gov/site/nypd/stats/crime-statistics/historical.page)

. 🗺️ [Neighborhood Division by PTC](https://www.nyc.gov/site/nypd/bureaus/patrol/precincts-landing.page)

4. Execute a análise e a previsão:

   ```python main.py```

## 🛠️  Tecnologias Usadas

+ Python
+ Pandas, NumPy (Manipulação de dados)
+ Scikit-learn (Modelagem preditiva)
+ Matplotlib, Seaborn (Visualização de dados)

