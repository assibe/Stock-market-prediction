
# Description of the project

The goal of this project is to predict whether the stockmarket value will fall or not based on the daily news from top 25 news outlets. The data used for this project is obtained from Kaggle datasets which can be found at https://www.kaggle.com/aaron7sun/stocknews

The file ***stockMarketAndNewsData.csv*** contains all the required data. The columns in the data include **Date, Label** (0 if stockmarket value droped, 1 otherwise), and ***Top1 - Top25*** store the text of the daily top 25 news headlines.

The solution is developed on pyspark using Spark 1.6.0.
