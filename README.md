
<!-- Badges -->
<!-- 
![](https://img.shields.io/github/stars/pandao/editor.md.svg) ![](https://img.shields.io/github/forks/pandao/editor.md.svg) ![](https://img.shields.io/github/tag/pandao/editor.md.svg) ![](https://img.shields.io/github/release/pandao/editor.md.svg) ![](https://img.shields.io/github/issues/pandao/editor.md.svg) ![](https://img.shields.io/bower/v/editor.md.svg)
-->

<!-- #<img src="https://pandao.github.io/editor.md/images/logos/editormd-logo-180x180.png" alt="dogcoin" class="center"/>
![](https://pandao.github.io/editor.md/images/logos/editormd-logo-180x180.png) -->

<p align="center">
<img src="https://i0.wp.com/cdn.quantargo.com/assets/blog/2021-07-15-elon-musk-tweet-effect-dodge-coin/og.png" alt="dogcoin" width="500px" height="300px" class="center"/>
</p>

<!-- https://i0.wp.com/cdn.quantargo.com/assets/blog/2021-07-15-elon-musk-tweet-effect-dodge-coin/og.png -->


# Analise Multivariável  de Características de Tweets sobre  Comportamento das Criptomoedas


# Topics
  - [Description](README.md#Description)
  - [Projeto e Repositório](README.md#Specification)
  - [Configuração](README.md#Tasks)
  - [Execução](README.md#Methodology)
  - [Installation](README.md#Installations)
  - [Usage/Examples](README.md#Usage/Examples)
  - [Deployment](README.md#Deployment)
  - [Lessons Learned](README.md#Lessons-Learned) 
  - [API Reference](README.md#API-Reference)
  - [References](README.mdReferences)
  
## Description


Objetivo

Integração dos dados financeiros com outras bases, para ver a correlação entre o comportamento do mercado e o comportamento dos dados das outras bases

Comparar bolsas tradicionais com bitcoin/dogecoin, influência de tweets de Elon Musk nas criptomoedas/falta de influência na SP500/apple, amazon, googl

[TOCM]

[TOC]

## Specification

- Specification 1
- Specification 2
- Specification 3

## Tasks

- [x]  Reunir, analisar e manipular os conjuntos de dados disponíveis 
- [x]  Pesquisar referências dos métodos de predição do valor de criptomedas e bolsas de valores baseado em redes sociais
- [x]  Realizar experimentações exploratórias iniciais para viabilidade do aprofundamento do problema e início da investigação e pesquisa
- [ ]  Compreender o problema e verificar as soluções utilizadas pelo estado da arte
- [ ]  Levantar e hipóteses e projetar uma análise de correlação entre as variáveis do problema
- [ ]  Identificar, definir e selecionar relevantes características dos dados
- [ ]  Analisar os métodos de análise de sentimento para predizer o comportamento das criptomoedas
- [ ]  Escolher uma metodologia para realizar análise de sentimento baseado em alguma rede social

  
## Methodology

To do.

## Installation

## Usage/Examples

To do.

## Deployment

To deploy this localy project run

`
   http://<local_url>:8080/resource.
`

  
To deploy this cloud project run

`
   http://<remote_url>:8080/resource.
`

## Lessons Learned 

To do.


## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.



## References 🔗

### Dados financeiros

- [stock-exchange-data](https://www.kaggle.com/mattiuzc/stock-exchange-data)

- [price-volume-data-for-all-us-stocks-etfs - @borismarjanovic](https://www.kaggle.com/borismarjanovic/price-volume-data-for-all-us-stocks-etfs)

- [bitcoin-price-prediction](https://www.kaggle.com/team-ai/bitcoin-price-prediction?select=bitcoin_price_Training+-+Training.csv)

- [sandp500 - @camnugent](https://www.kaggle.com/camnugent/sandp500)

- [bitcoin-tweets - @kaushiksuresh147](https://www.kaggle.com/kaushiksuresh147/bitcoin-tweets)

- [ bitcoin-tweets-20160101-to-20190329 - @alaix14](https://www.kaggle.com/alaix14/bitcoin-tweets-20160101-to-20190329)

- [cryptocurrencypricehistory](https://www.kaggle.com/sudalairajkumar/cryptocurrencypricehistory?select=coin_Bitcoin.csv)
 
- [mczielinski/bitcoin-historical-data](https://www.kaggle.com/mczielinski/bitcoin-historical-data)
 
- [dogecoin-historical-data](https://www.kaggle.com/dhruvildave/dogecoin-historical-data)



## Notebooks

- [s-p-500-time-series-forecasting-with-prophet](https://www.kaggle.com/janiobachmann/s-p-500-time-series-forecasting-with-prophet)

- [stock-market-analysis-prediction-using-lstm](https://www.kaggle.com/faressayah/stock-market-analysis-prediction-using-lstm)

- [temporal-behaviours](https://www.kaggle.com/tezdhar/temporal-behaviours)

- [bitcoin-price-prediction-by-arima](https://www.kaggle.com/myonin/bitcoin-price-prediction-by-arima)

- [bitcoin-dogecoin-on-rapids-and-elon-musk](https://www.kaggle.com/andradaolteanu/bitcoin-dogecoin-on-rapids-and-elon-musk)

- [Panda Profiling Automatic EDA Ellon Musk](https://colab.research.google.com/drive/1-G_lyyqH4a81B1NF6J500yfrTrM9_4jJ)
  
- [international-football-results-from-1872-to-2017](https://www.kaggle.com/martj42/international-football-results-from-1872-to-2017)  

- [covid19-lockdown-dates-by-country](https://www.kaggle.com/jcyzag/covid19-lockdown-dates-by-country)

- [The Elon Musk Tweet Effect on Dogecoin DOGE](https://www.r-bloggers.com/2021/07/the-elon-musk-tweet-effect-on-dogecoin-doge/)

- [https://www.r-bloggers.com/2021/02/causal-effect-of-elon-musk-tweets-on-dogecoin-price/](https://www.r-bloggers.com/2021/02/causal-effect-of-elon-musk-tweets-on-dogecoin-price/)

- [Bitcoin and Twitter Sentiment](https://rstudio-pubs-static.s3.amazonaws.com/473326_bac13e3e87d141c38ff60cb85e85aa33.html)

  

Base com números do twitter (correlacionar com cripto), número de menções gerais, pessoas relevantes
  

- [elon-musk-tweets-2010-2021](https://www.kaggle.com/ayhmrba/elon-musk-tweets-2010-2021)

- [all-elon-musks-tweets](https://www.kaggle.com/andradaolteanu/all-elon-musks-tweets)

- [tweets-about-the-top-companies-from-2015-to-2020](https://www.kaggle.com/omermetinn/tweets-about-the-top-companies-from-2015-to-2020)

- [stock-markettweets-lexicon-data](https://www.kaggle.com/utkarshxy/stock-markettweets-lexicon-data)


## Sentiment Analysis

- [how-to-build-a-bitcoin-sentiment-analysis-using-python-and-twitter](https://medium.com/analytics-vidhya/how-to-build-a-bitcoin-sentiment-analysis-using-python-and-twitter-beb89e6ce0c8)

- [Bitcoin-Price-Twitter-Sentiment-Analysis](https://github.com/Aaron-Paul/Bitcoin-Price-Twitter-Sentiment-Analysis)

- [pytorch-sentiment-analysis](https://github.com/bentrevett/pytorch-sentiment-analysis)


## Artigos

- [The predictive power of public Twitter sentiment for forecasting cryptocurrency prices](https://www.sciencedirect.com/science/article/abs/pii/S104244312030072X)

- [Cryptocurrency Price Prediction Using Tweet Volumes and Sentiment Analysis](https://scholar.smu.edu/datasciencereview/vol1/iss3/1/)

- [Advanced social media sentiment analysis for short-term cryptocurrency price prediction](https://onlinelibrary.wiley.com/doi/abs/10.1111/exsy.12493)

- [Bitcoin Spread Prediction Using Social And Web Search Media](https://www.researchgate.net/publication/279917417_Bitcoin_Spread_Prediction_Using_Social_And_Web_Search_Media)  

- [Cryptocurrency Price Prediction Using Tweet Volumes and Sentiment Analysis](https://scholar.smu.edu/cgi/viewcontent.cgi?article=1039&context=datasciencereview)

- [Sentiment analysis algorithms and applications: A survey](https://www.sciencedirect.com/science/article/pii/S2090447914000550)

- [Sentiment Analysis of Twitter Data](https://aclanthology.org/W11-0705.pdf)

- [Twitter Sentiment Analysis: The Good the Bad and the OMG!](https://ojs.aaai.org/index.php/ICWSM/article/view/14185)


## Dissertação

- [Cryptocurrency analysis based on user-generated social media content](https://repositorio.iscte-iul.pt/handle/10071/22088)

- [Predicting Bitcoin price fluctuation with Twitter sentiment analysis](https://www.diva-portal.org/smash/get/diva2:1110776/FULLTEXT01.pdf)

- [O Impacto nos Mercados Financeiros dos Tweets do Presidente Norte Americano Donald Trump](https://iconline.ipleiria.pt/bitstream/10400.8/5544/1/Tese%20Mestrado%20-%20Paulo%20Malaquias.pdf)

- [The Interplay between Social Media Sentiment and the Cryptocurrency Market](https://ethz.ch/content/dam/ethz/special-interest/mtec/chair-of-entrepreneurial-risks-dam/documents/dissertation/master%20thesis/Master%20Thesis%20Eisner_final.pdf)

## API

- [Twitter API](https://developer.twitter.com/en/docs/twitter-api)
- [Twitter API v2: Early Access](https://developer.twitter.com/en/docs/twitter-api/early-access)


## Acknowledgements

- [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
- [Awesome README](https://github.com/matiassingers/awesome-readme)
- [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)
  

## Authors

- [Bruno dos Anjos - @Sivirino1](https://www.github.com/Sivirino01)
- [Ravi Barreto - @ravibdf](https://www.github.com/ravibdf)
- [Rafael Campello - @rafaelmcam](https://www.github.com/rafaelmcam)
- [Richardson Bruno - @jcrbsa](https://www.github.com/jcrbsa)


## Feedback

If you have any feedback, please reach out to us at fake@fake.com


## License

[MIT](https://choosealicense.com/licenses/mit/)

