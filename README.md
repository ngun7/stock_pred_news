# RMDS 2021 Data Science Competition

# Impact of News Sentiment on the Stock Market

**Problem Statement**:

This data science competition seeks to create an innovative solution to analyze the effects of news sentiment and biases on daily stock performance for top companies in the oil and gas industry. News Sentiments and biases have a significant impact on stock prices and consumer behavior. Contestants will be provided with the necessary news data, stock market data, macro data and company financial data.

**Datasets**

Datasets are downloaded from this [Link](https://worlddata.ai/bucket/WorldDataTeam/Competition_RMDS_WorldData). Merged various datasets on common column "Date" and filtered columns based on domain knowledge. Added extra technical indicators to predict.

Among all 10 companies, "Phillips 66" stock is filtered and analyzed the impact of the news sentiment score to predict its closing price.

1) To replicate this work, please install necessary packages from requirements.txt file
2) For data preparation and merging, follow the steps from Data_Preparation.ipynb
3) For modeling and forecasting, follow the code from Stock_Pred_LSTM.ipynb
