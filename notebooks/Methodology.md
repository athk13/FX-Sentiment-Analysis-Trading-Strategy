# Methodology

## Objective
The primary aim of this trading strategy is to systematically leverage sentiment analysis derived from news articles to generate predictive signals for the USD/GBP exchange rate and to compare the performance against the HFRI Currency Index.

## Data Extraction and Preprocessing
- Utilized the New York Times API to collect articles from 2003 to 2024 related to economic indicators influencing the Forex market.
- Implemented regex-based data cleaning techniques to extract and structure relevant information from headlines, lead paragraphs, and abstracts.

## Sentiment Analysis
- Conducted sentiment analysis on structured text data to quantify the impact of economic news on market sentiment.
- Utilized `TextBlob` for assessing the sentiment polarity of each article, contributing to the overall sentiment score for the USD/GBP exchange rate.

## Trading Signal Generation
- Developed a dynamic Kalman filter, calibrated to the sentiment scores, to identify optimal trade entry and exit points with high precision.

## Hyperparameter Optimization
- Executed a hyperparameter optimization process to find the best settings for the Kalman filter, including the smoothing factor, standard deviation bounds, and holding periods.

## Backtesting
- Backtested the trading strategy using historical USD/GBP exchange rate data to validate the effectiveness of sentiment-based signals.

## Performance Evaluation
- Evaluated the strategy's performance using various metrics, including annualized return, Sharpe ratio, maximum drawdown, and the percentage of winning months.

## Comparison with Benchmark
- Compared the developed strategy's performance metrics with those of the HFRI Currency Index to determine its competitiveness in the real market.
