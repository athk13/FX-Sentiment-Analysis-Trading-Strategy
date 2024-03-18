# FX-Sentiment-Analysis-Trading-Strategy
An innovative Forex trading strategy based on sentiment analysis of New York Times articles, applying machine learning and a dynamic Kalman filter to outperform the HFRI Currency Index with a focus on the USD/GBP exchange rate

This repository houses a comprehensive Forex trading strategy centered on sentiment analysis extracted from over 100 queries to the New York Times API, spanning from 2003 to 2024. The strategy focuses on the USD/GBP exchange rate, leveraging machine learning techniques to uncover patterns in headlines, lead paragraphs, and abstracts.

## Project Overview

- **Objective**: Develop a Forex trading strategy based on sentiment analysis of New York Times articles, aiming to outperform the HFRI Currency Index.
- **Data Extraction**: Utilized the New York Times API to analyze news articles related to economic indicators and currency strength, applying regex for pattern detection.
- **Model Development**: Implemented a dynamic Kalman filter adjusted to sentiment changes for precise trading signals.
- **Results**: Achieved an annualized return of 3.2%, surpassing the HFRI Currency Index by 2.01%.

## Repository Structure

- `/notebooks`: Contains Jupyter notebooks detailing the data extraction, preprocessing, and analysis phases.
- `/doc`: Documentation covering the strategy rationale, methodology, and results summary. Additional insights into the project's approach, including challenges and solutions.

## Getting Started

To explore and utilize this trading strategy, ensure your environment supports Python libraries such as `pandas`, `numpy`, `matplotlib`, `requests`, and `textblob`. 

## Key Insights

- The use of sentiment analysis as a predictor for Forex market movements proved effective, with the strategy outperforming a notable benchmark.
- Dynamic adjustment of trading signals via a Kalman filter significantly enhanced the strategy's precision and profitability.
- Extensive data analysis highlighted the impact of economic news on currency strength, guiding the development of a data-driven trading strategy.

## Conclusion

This project underscores the potential of integrating sentiment analysis with quantitative trading strategies. By systematically analyzing news sentiment, we've developed a robust model that not only captures market sentiment shifts but also delivers superior returns, demonstrating the effectiveness of this approach in the dynamic Forex market.

---

The `FX-Sentiment-Analysis-Trading-Strategy` repository utilizes innovative use of data science in financial markets, offering valuable insights and tools for traders and analysts alike.
