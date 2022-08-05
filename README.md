# Stocks and Crypto Research
```sh
This research includes the News and Tweet's Sentiment Analysis and trying the predict and forcast the stock and crypto's price.
```

## Part 1: Sentiment Analysis
```sh
News Analysis 
* The news is scraped directly from `Google`, and all the out unwanted URLs are striped out.
* This is scraped out news is then summarized using `Pegasus` Model.
* `Flair` Sentiment Analysis is used to find the sentiment of the summarized News.
```
<https://github.com/kushalBanda/Stocks-and-Crypto-Research/blob/main/Sentiment%20Analysis/News%20Sentiment.ipynb>
```sh
Tweet Analysis 
* The Tweet are scraped directly from Twitter using the `snscrape` module.
* With some preprocessing steps we clean the tweets.
* `Flair` Library is used to find the sentiment of the Tweets.
* `Yahoo Finanace` library is used to get the historical data of the required Stock.
* Comparing our tweet sentiments against real stock data
```
<https://github.com/kushalBanda/Stocks-and-Crypto-Research/blob/main/Sentiment%20Analysis/Tweet%20Sentiment.ipynb>

## Part 2: Time Series Analysis  
```sh
Stock and Crypto Price Prediction
```
```sh
Stock and Crypto Price Forcasting
```

## Part 3: Reinforcemnt Learning 

```sh
 Work in Progress
```




## Contributing

1. Fork it (<https://github.com/yourname/yourproject/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

<!-- Markdown link & img dfn's -->
[npm-image]: https://img.shields.io/npm/v/datadog-metrics.svg?style=flat-square
[npm-url]: https://npmjs.org/package/datadog-metrics
[npm-downloads]: https://img.shields.io/npm/dm/datadog-metrics.svg?style=flat-square
[travis-image]: https://img.shields.io/travis/dbader/node-datadog-metrics/master.svg?style=flat-square
[travis-url]: https://travis-ci.org/dbader/node-datadog-metrics
[wiki]: https://github.com/yourname/yourproject/wiki

