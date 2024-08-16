## 해외주식 투자자반응 제공 서비스 (Stock Investor Sentiment Service)

### Team infomation

- **Team name:** 자연스럽게만두추가  
- **Team Members:** 신욱현, 이선재, 이지희

---

### Project Overview

This project provides a service that analyzes and summarizes overseas investor sentiments to assist domestic retail investors in making better investment decisions regarding foreign stocks. The service visually presents various indicators based on the reactions of overseas individual investors, offering a valuable tool for those looking to invest in international markets.

<img src="/images/Untitled.png"  width="300">

---

### Problem Awareness

1. **Information Asymmetry for Retail Investors**  
   Retail investors often have limited access to critical information compared to institutional or professional investors, resulting in lower returns. Given their difficulty in accessing and evaluating necessary information, this service aims to bridge that gap by summarizing overseas investor reactions.

2. **Lack of Information on Foreign Stocks**  
   Domestic investors have limited tools and information when investing in foreign stocks. Unlike domestic stocks, where sentiment and data are more readily available, it is challenging to gauge global investor sentiment for foreign stocks. This service addresses that gap by summarizing opinions from international investors.

---

### Service Features

1. **Comparison of Investor Sentiment and Actual Performance**  
   The service scores the sentiment of international investors, allowing users to compare these scores with the actual performance of the stock during the same periods.

   <img src="/images/Sentiment_ex.png">

2. **Summary of Positive and Negative Sentiments**  
   The service provides a graphical representation of the proportion of positive and negative sentiments, along with concise summaries of key reactions.

   | 종목명 | 긍정평가 | 부정평가 |
   | --- | --- | --- |
   | TSLA | Enthusiastic reception for the new Model X and Model Y updates, and strong confidence in Tesla's innovations in FSD and battery technology. | Owners are expressing frustration with the Model S's quality issues, frequent recalls, and declining resale value / Many users find the Model S overpriced for its features and performance compared to other electric vehicles. |
   | AAPL | Exciting advancements: anticipation for foldable iPhone / Insightful and dynamic tech reviews help users understand new innovations | People are disappointed with the lack of meaningful updates in the new iPad Pro, making jokes about basic features finally arriving years late / Users feel frustrated with Apple's focus on making devices thinner instead of improving battery life and functionality. |
   | META | Investors are confident about the company's long-term potential and its investments in AI and VR technology. / People are excited about the advancements and upcoming releases, such as Meta Quest 3. | People are frustrated with Meta's ad algorithms and overall declining advertisement efficiency. / Users voice concerns about Meta's VR products and the company's overall direction, viewing it critically. |
   | MSFT | People are consistently supportive and optimistic about Microsoft's long-term growth and reliability / Investors show appreciation and confidence in Microsoft’s consistent performance and growth trajectory. | Users are concerned that the company’s acquisitions and strategies are not yielding expected returns and feel there will be long term issues despite AI advancements. / Many users have contested that Microsoft's performance and decisions seem overrated, pointing to failed acquisitions and questioning the company's overall direction. 

3. **Mentions in News Articles**  
   The number of times the stock is mentioned in news articles is compared against the S&P 500 average, providing additional context regarding investor interest and information availability.

   | 종목명 | 하루 동안의 뉴스 기사 수 | 1개월 동안의 뉴스 기사 수 |
   | --- | --- | --- |
   | Alphabet | 3359 | 188720 |
   | Amazon | 1069 | 75654 |
   | Apple | 719 | 94916 |
   | Meta | 1902 | 91105 |
   | Microsoft | 2098 | 123963 |
   | Nvidia | 1283 | 63397 |
   | Tesla | 919 | 48268 |

---

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
   <p align="left">
      <img src="/images/Frame%203-2.png" width="300" style="margin-right: 20px;"/>
      <img src="/images/Frame%204-1.png" width="300" />
   </p>

2. **Correlation Analysis Between Sentiment and Stock Price**  
   By analyzing the time-lagged relationship between sentiment and stock price, the service can offer more reliable information for predicting stock movements.    
   <img src="/images/Frame 5.png" width="250" />

### Limitations and Considerations

- Due to limitations in data availability, the current version only covers a limited number of high-market-cap stocks. Expanding data coverage is essential for further improvement.
- Bias in data collection, influenced by specific community user characteristics, requires further adjustment and correction.

---

This project was done for the Big data AI festival hold by 미래에셋 자산증권.  
[Project link](https://miraeassetfesta.com/)  
[Project Report](https://quick-climb-d69.notion.site/2480e8f5cc024cbab6fab8ab2ae0521e)