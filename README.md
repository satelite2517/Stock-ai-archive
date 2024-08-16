## 해외주식 투자자반응 제공 서비스 (Stock Investor Sentiment Service)

### Team infomation

- **Team name:** 자연스럽게만두추가  
- **Team Members:** 신욱현, 이선재, 이지희

### Project Overview

This project provides a service that analyzes and summarizes overseas investor sentiments to assist domestic retail investors in making better investment decisions regarding foreign stocks. The service visually presents various indicators based on the reactions of overseas individual investors, offering a valuable tool for those looking to invest in international markets.

### Problem Awareness

1. **Information Asymmetry for Retail Investors**  
   Retail investors often have limited access to critical information compared to institutional or professional investors, resulting in lower returns. Given their difficulty in accessing and evaluating necessary information, this service aims to bridge that gap by summarizing overseas investor reactions.

2. **Lack of Information on Foreign Stocks**  
   Domestic investors have limited tools and information when investing in foreign stocks. Unlike domestic stocks, where sentiment and data are more readily available, it is challenging to gauge global investor sentiment for foreign stocks. This service addresses that gap by summarizing opinions from international investors.

### Service Features

1. **Comparison of Investor Sentiment and Actual Performance**  
   The service scores the sentiment of international investors on a scale from -100 to 100 for both the past month and the past three months, allowing users to compare these scores with the actual performance of the stock during the same periods.

2. **Summary of Positive and Negative Sentiments**  
   The service provides a graphical representation of the proportion of positive and negative sentiments, along with concise summaries of key reactions.

3. **Mentions in News Articles**  
   The number of times the stock is mentioned in news articles is compared against the S&P 500 average, providing additional context regarding investor interest and information availability.

### Data Collection and Analysis

- **Data Sources:**  
  Youtube video titles and comments, Reddit posts and comments, and international news articles.

- **Keyword Extraction and Data Gathering:**  
  Using HyperCLOVA X, relevant keywords for each stock were identified, and data was then collected based on these keywords.

- **Sentiment Analysis:**  
  Transformer models were used to conduct sentiment analysis, categorizing opinions as positive or negative and extracting key insights from these comments.

### Future Improvements

1. **Time Series Analysis of Investor Sentiment and Volatility**  
   Future iterations will aim to provide sentiment scores on a daily or hourly basis, offering better insight into volatility and sentiment changes over time.

2. **Correlation Analysis Between Sentiment and Stock Price**  
   By analyzing the time-lagged relationship between sentiment and stock price, the service can offer more reliable information for predicting stock movements.

### Limitations and Considerations

- Due to limitations in data availability, the current version only covers a limited number of high-market-cap stocks. Expanding data coverage is essential for further improvement.
- Bias in data collection, influenced by specific community user characteristics, requires further adjustment and correction.

### Team Introduction

- **Team Name:** 자연스럽게만두추가 (Naturally Dumpling Extra)  
- **Team Members:** Shin Uk-hyun, Lee Seon-jae, Lee Ji-hee

---

This service provides M-Stock users with valuable and easy-to-understand insights based on overseas individual investor sentiment, ultimately enhancing the investment decisions of domestic retail investors in the international stock market.


---

This project was done for the Big data AI festival hold by 미래에셋 자산증권.  
[Project link](https://miraeassetfesta.com/)  
[Project Report](https://quick-climb-d69.notion.site/2480e8f5cc024cbab6fab8ab2ae0521e)