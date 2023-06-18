## Sentiment-Analysis-of-Stock-Market-Trading

## Introduction :

Sentiment analysis is a powerful technique used to determine the overall sentiment or opinion expressed in a piece of text. When applied to stock trading news, sentiment analysis can help investors and traders understand the market sentiment surrounding specific stocks or companies.

This project aims to perform sentiment analysis on stock trading news articles to gauge the sentiment associated with different private sector banks. By analyzing the sentiment, investors can gain insights into market perceptions and potentially make more informed trading decisions.

## Scrapping Headlines

There are Various ways to obtain news

* Finviz is the most powerful financial news website. By srapping this website, we can gather a large number of articles for sentiment anaysis.

  <img src="https://github.com/manasa0551/Sentiment-Analysis-of-Stock-Trading-News/assets/83413401/dd831e96-e5c9-48a4-a049-1d1888d48e7a" width="500" height="300">


   <img src="https://github.com/manasa0551/Sentiment-Analysis-of-Stock-Trading-News/assets/83413401/e27d6fa6-633b-4c7f-b197-7cad3a20f9e5" width="500" height="300">

## Steps :

1. Extract The Stock Tickers from URL
2. Extract the stock news headlines
3. Applying Sentiment Analyzer to calcuate polarity Scores
4. postive news
5. negitive news

## Flow chart :
```mermaid
  graph TD;
A[Finviz stock news] -->B[Preprocessing steps];
B[Preprocessing steps]-->c[Sentiment Intensity Analyzer];
c[Sentiment Analyzer]-->D{Decision};
D{Polarity scores}-->E[Positive news];
E[Positive news]-->F[Stock Price Increase];
D{Polarity Scores}-->G[Negative News];
G[Negative News]-->H[Stock Price Decreases];

```

## Bank Nifty Weightage 
<img src="https://github.com/manasa0551/Sentiment-Analysis-of-Stock-Trading-News/assets/83413401/60b49d19-5135-4d65-9a6c-13859d7b07cb" width="500" height="300">
