# Rossman_Sales_Model
# Projeto de Insights: House Rocket #
   O objetivo desse projeto é 
## 1. Questão de negócio: ##
  

## 2.	Premissas do Negócio: ## 
  
## 3.	Planejamento da Solução: ## 

### 3.1 Coleta de Dados ###
    
Os dados foram extraídos do link abaixo, onde constam todos os imóveis em portfólio e disponíveis para a empresa [Kaggle](https://www.kaggle.com/harlfoxem/housesalesprediction)

•	Os dados são de xxxxx

•	A definição para cada um dos atributos encontra-se abaixo:

Dicionário de Dados

|      Atributo          |      Descrição                                                                                                                            |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
|     id                 |     Numeração única de identificação de cada   imóvel                                                                                     |
|     date               |     Data da venda da casa                                                                                                                 |
|     price              |     Preço que a casa está sendo vendida pelo   proprietário                                                                               |
|     bedrooms           |     Número de quartos                                                                                                                     |
|     bathrooms          |     Número de banheiros (0.5 = banheiro em   um quarto, mas sem chuveiro)                                                                 |
|     sqft_living        |     Medida (em pés quadrado) do espaço   interior dos apartamentos                                                                        |
|     sqft_lot           |     Medida (em pés quadrado)quadrada do   espaço terrestre                                                                                |
|     floors             |     Número de andares do imóvel                                                                                                           |
|     waterfront         |     Variável que indica a presença ou não de   vista para água (0 = não e 1 = sim)                                                        |
|     view               |     Um índice de 0 a 4 que indica a   qualidade da vista da propriedade. Varia de 0 a 4, onde: 0 = baixa 4 = alta                         |
|     condition          |     Um índice de 1 a 5 que indica a condição   da casa. Varia de 1 a 5, onde:1 = baixo 5 = alta                                           |
|     grade              |     Um índice de 1 a 13 que indica a   construção e o design do edifício. Varia de 1 a 13, onde: 13 = baixo, 7 =   médio e 1113 = alta    |
|     sqft_basement      |     A metragem quadrada do espaço   habitacional interior acima do nível do solo                                                          |
|     yr_built           |     Ano de construção de cada imóvel                                                                                                      |
|     yr_renovated       |     Ano de reforma de cada imóvel                                                                                                         |
|     zipcode            |     CEP da casa                                                                                                                           |
|     lat                |     Latitude                                                                                                                              |
|     long               |     Longitude                                                                                                                             |
|     sqft_livining15    |     Medida (em pés quadrado) do espaço   interno de habitação para os 15 vizinhos mais próximo                                            |
|     sqft_lot15         |     Medida (em pés quadrado) dos lotes de   terra dos 15 vizinhos mais próximo                                                            |



### 3.2 Limpeza de Dados ###
### 3.3 Análise Exploratória ###

•	Estatísticas descritivas:


|      attributes      |      maximum      |      minimum     |      mean        |      median      |      std         |
|----------------------|-------------------|------------------|------------------|------------------|------------------|
|     price            |     7700000.00    |     75000.00     |     541645.37    |     450000.00    |     367314.32    |
|     bedrooms         |     11.00         |     0.00         |     3.37         |     3.00         |     0.91         |
|     bathrooms        |     8.00          |     0.00         |     2.12         |     2.25         |     0.77         |
|     sqft_living      |     13540.00      |     290.00       |     2082.73      |     1920.00      |     919.14       |
|     sqft_lot         |     1651359.00    |     520.00       |     15136.06     |     7614.00      |     41538.57     |
|     floors           |     3.50          |     1.00         |     1.50         |     1.50         |     0.54         |
|     view             |     4.00          |     0.00         |     0.24         |     0.00         |     0.77         |
|     condition        |     5.00          |     1.00         |     3.41         |     3.00         |     0.65         |
|     grade            |     13.00         |     1.00         |     7.66         |     7.00         |     1.17         |
|     sqft_above       |     9410.00       |     290.00       |     1791.00      |     1560.00      |     829.01       |
|     sqft_basement    |     4820.00       |     0.00         |     291.73       |     0.00         |     442.78       |
|     yr_built         |     2015.00       |     1900.00      |     1971.10      |     1975.00      |     29.38        |
|     yr_renovated     |     2015.00       |     0.00         |     84.73        |     0.00         |     402.43       |
|     sqft_living15    |     6210.00       |     399.00       |     1988.35      |     1840.00      |     685.68       |
|     sqft_lot15       |     871200.00     |     651.00       |     12786.34     |     7620.00      |     27375.41     |


Novas features:

•	constrution: ano de construção maior ou menor que 1955


### 3.4 Aplicativo em Nuvem ###


## 4.	Principais Insights ##


### H1 -Imóveis com vista para a água são em média mais caros ###

- [x] Resultado: Verdadeiro


### H2 - Imóveis com data de construção menor que 1955 são em média mais baratos ####

- [x]  Resultado: Falso


### H3 - Imóveis sem porão são maiores do que imóveis com porão ###

- [x]  Resultado: Verdadeira


### H4 - Houve crescimento do preço médio dos imóveis YoY ( Year over Year )###

- [x]  Resultado: Falsa 


### H5 - Imóveis com mais quartos são em média mais caros ###

- [x]  Resultado: Verdadeiro


## 5.	Resultados Financeiros: ## 



## 6. Conclusão:

## 7. Referências:

* Blog [Seja um Data Scientist](https://sejaumdatascientist.com/os-5-projetos-de-data-science-que-fara-o-recrutador-olhar-para-voce/)
* Dataset House Sales in King County (USA) from [Kaggle](https://www.kaggle.com/harlfoxem/housesalesprediction)


## 8. Tecnologias:

![jupyter](https://user-images.githubusercontent.com/92406177/142740450-cc471f27-9bd0-4a5d-8cae-83f7521e185d.jpg)
![pycharn](https://user-images.githubusercontent.com/92406177/142740468-2df16be5-4e40-4212-83c0-c8df1f761411.jpg)
![python](https://user-images.githubusercontent.com/92406177/142740482-7d45a576-d134-49df-9d1e-d783a9e2f24a.jpg)
