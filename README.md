# House Rocket Company


![readme_2seattle](https://user-images.githubusercontent.com/99512194/179364327-41addcc4-a259-4753-989a-e2b0a7bd7421.jpg)

## Descrição:

A House Rocket é uma empresa do ramo imobiliário em que seu core business é comprar imóveis no melhor preço possível, reformar e revender para gerar lucro. Entretando, as casas possuem muitos atributos que as tornam mais ou menos atrativaas aos compradores e a localização e o período do ano também afetar os preços.
Além disso, o porfólio de imóveis da empresa é muito extenso, sendo impossível realizar o trabalho manualmente, com isso a necessidade de elaborar um projeto para solução do problema de negócio utilizando ferramentas de data science.

A partir do desafio em responder esses questionamentos o principal objetivo em explorar esse dataset foi criar um **Projeto de Insights** que responderá a questão de negócio a partir da coleta, limpeza e exploração dos dados e, como produto final, entregar um aplicativo interativo utilizando  o streamlit.

Para acessar o aplicativo Streamlit, basta clicar no link a seguir publicado utilizando a plataforma cloud Heroku:

https://peaceful-mountain-62003.herokuapp.com/ 

## Questão de negócio:
1) Quais casas a empresa House Rocket deveria comprar levando em conta seus atributos e qual melhor preço de compra?
2) Qual melhor momento para vender as casas e qual o preço de venda ideal?


### Dados:
O projeto de insights foi criado a partir do dataset 'House Sales in King County, Settle'. O dataset apresenta casas que foram vendidas entre maio de 2014 e maio de 2015, seus atributos e preço de venda. 
O dataset poderá ser encontrado em: https://www.kaggle.com/datasets/harlfoxem/housesalesprediction

Os atributos dos imóveis são os seguintes:
| Atributo |  Descrição  |
| ------------------- | ------------------- |
|  id |  ID único e identificação do imóvel |
|  date |  Data da venda do imóvel |
|  price |  Preço de venda |
|  bedrooms |  nº de quartos |
|  bathrooms |  nº de banheiros |
|  sqft_living |  medida em pés quadrados da área habitável do imóvel |
|  sqft_lot|  medida em pés quadrados da área do terreno |
|  floors |  nº de andares do imóvel |
|  waterfront |  variavel categorica: presença de vista para água = 1 e sem vista = 0|
|  view |  índice ordenado de 0 a 4 em que indica a qualidade da vista do imóvel |
|  condition |  índice ordenado de 0 a 5 em que indica a condição física/estrutural do imóvel |
|  date |  índice ordenado de 0 a 13 em que indica design e condição de construção do imóvel |
|  sqft_basement |  área do subsolo / porão |
|  yr_built |  ano de construção do imóvel |
|  yr_renovated|  ano da última reforma do imóvel |
|  lat |  latitude|
|  long |  longitude |
|  sqft_livining15 |  área em pés quadrados da área habitável do imóvel para os 15 vizinhos mais próximos |
|  sqft_lot15 |  área em pés quadrados da área dos terrenos para os 15 vizinhos mais próximos |

### Autor
Robson de Castro Serafim

https://www.linkedin.com/in/robson-castro-serafim/

https://medium.com/@robson.serafim
