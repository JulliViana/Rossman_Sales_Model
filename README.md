# Rossman_Sales_Model

   O objetivo desse projeto é 
## 1. Questão de negócio: ##
A Empresa de Vendas Rossmann

Rede privada de drogarias com sede na Alemanha, com operações principais na Europa. Opera mais de 3.000 drogarias em 7 países diferentes.
Oferece produtos de saúde e beleza, incluindo cuidados com o bebê e o corpo, higiene, cosméticos, higiene dental, cuidados com os cabelos e assim por diante.
Modelo de negócios: vendas de produtos.
Problema

O CFO queria reinvestir em todas as lojas, portanto, ele precisa saber quanto de receita cada loja trará para poder investir agora.
Meta

Preveja as vendas diárias de todas as lojas com até seis semanas de antecedência.
  

## 2.	Premissas do Negócio: ## 
Os dias em que as lojas foram fechadas (Abertas) foram retiradas da análise.
Foram consideradas apenas lojas com valores de venda maiores que 0.
Para as lojas que não possuíam informação de “Distância de Competição”, estes dados-se que a distância deveria ser a maior distância observada no conjunto de dados.
  
## 3.	Planejamento da Solução: ## 
O projeto foi desenvolvido através do método CRISP-DM, aplicando os seguintes passos:

Passo 01 - Descrição dos dados: Nessa etapa, o objetivo foi conhecer os dados, seus tipos, usar estatísticas para identificar outliers no escopo do negócio e também analisar estatísticas básicas como: média, mediana, máximo, mínimo, range, skew, curtose e desvio padrão. Nessa etapa também foram feitos alguns ajustes em recursos do conjunto de dados, como preenchimento de NA's por exemplo.

Passo 02 - Feature Engineering: Nessa etapa, foi desenvolvido um mapa mental para analisar as tendências, suas variáveis ​​e os principais aspectos que impactam cada variável. A partir das características das hipóteses e da necessidade de novos atributos, foram elevados novos recursos a partir das variáveis ​​originais, a fim de melhorar as características do ser modelado.

Passo 03 - Filtragem dos dados: O objetivo desta etapa foi filtrar linhas e excluir colunas que não são relevantes para o modelo ou não fazem parte do escopo do negócio, como por exemplo, desconsiderar dias que as lojas não estavam operando e/ou que não houve vendas.

Passo 04 - Análise Exploratória dos dados: O objetivo desta etapa foi explorar os dados para encontrar insights, entender melhor a relevância das variáveis ​​no aprendizado do modelo. Foram feitas análises univariadas, bivariadas e multivariadas, utilizando os dados numéricos e categóricos do conjunto.

Passo 05 - Preparação dos dados: Nessa etapa, os dados foram preparados para o início das aplicações de modelos de machine learning. Foram utilizadas técnicas como Reescalonamento e Transformação, através de codificações e transformação da natureza.

Passo 06 - Seleção de Características: O objetivo desta etapa foi selecionar os melhores atributos para treinar o modelo. Foi utilizado o algoritmo Boruta para fazer a seleção das variáveis, destacando o que tinha mais relevância para as características.

Passo 07 - Modelagem de Machine Learning: Nessa etapa foram feitos os testes e treinamento de alguns modelos de machine learning, onde foi possível comparar seus respectivos desempenhos e feito a escolha do modelo ideal para o projeto. Inclusive foi utilizada a técnica de Validação Cruzada para garantir um desempenho real sobre os dados selecionados.

Passo 08 - Ajuste fino de hiperparâmetros: Tendo a escolha do algoritmo XBoost na etapa anterior, foi feita uma análise através do método Randon Search para escolher os melhores valores para cada um dos parâmetros do modelo. Ao final dessa etapa foi possível obter os valores finais de desempenho do modelo.

Passo 09 - Tradução e interpretação de erros: O objetivo dessa etapa foi de fato demonstrar o resultado do projeto, onde foi possível avaliar o desempenho do modelo com o viés de negócio, demonstrando o resultado financeiro que pode ser esperado se aplicado o modelo desenvolvido.

Passo 10 - Implantar o modelo em produção: Após a execução bem sucedida do modelo, o objetivo foi publicá-lo em um ambiente de nuvem para que outras pessoas ou serviços possam usar os resultados para melhorar a decisão de negócios. A plataforma de aplicativo em nuvem escolhida foi o Heroku.

Passo 11 - Bot do Telegram: A etapa final do projeto foi criar um bot no app de mensagens - Telegram, que possibilita consultar as variações a qualquer momento e lugar, visto que também foi feito o deploy na plataforma em nuvem.

### 3.1 Coleta de Dados ###
    
Os dados foram extraídos do link abaixo, onde constam todos os imóveis em portfólio e disponíveis para a empresa [Kaggle](https://www.kaggle.com/harlfoxem/housesalesprediction)

•	Os dados são de xxxxx

•	A definição para cada um dos atributos encontra-se abaixo:

Dicionário de Dados


## 6. Conclusão:

## 7. Referências:

* Blog [Seja um Data Scientist](https://sejaumdatascientist.com/os-5-projetos-de-data-science-que-fara-o-recrutador-olhar-para-voce/)
* Dataset House Sales in King County (USA) from [Kaggle](https://www.kaggle.com/harlfoxem/housesalesprediction)


## 8. Tecnologias:

![jupyter](https://user-images.githubusercontent.com/92406177/142740450-cc471f27-9bd0-4a5d-8cae-83f7521e185d.jpg)
![pycharn](https://user-images.githubusercontent.com/92406177/142740468-2df16be5-4e40-4212-83c0-c8df1f761411.jpg)
![python](https://user-images.githubusercontent.com/92406177/142740482-7d45a576-d134-49df-9d1e-d783a9e2f24a.jpg)
