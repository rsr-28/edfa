# Predicting Exchange Rate Movements: An Analysis of Monetary Policy Sentiments and Media Uncertainty Indices

## Project Overview

This project investigates the impact of sentiments extracted from the Reserve Bank of India’s (RBI) semi-annual monetary policy reports on economic variables, with a specific focus on exchange rates. Utilizing advanced Natural Language Processing (NLP) techniques, including pre-trained Large Language Models (LLMs) and FinBERT, we extract sentiment features such as Sentiment Subjectivity, Sentiment Polarity, and Sentiment Uncertainty from these reports.

The study incorporates lagged effects of monetary policy sentiments and evaluates their relationship with exchange rate movements through robust regression analysis. The findings contribute to the understanding of how monetary policy communications affect financial markets and suggest pathways for improving sentiment analysis models for more accurate economic forecasting.

## Abstract

This project explores the relationship between sentiments conveyed in RBI’s monetary policy reports and exchange rate movements. By leveraging LLMs and FinBERT, we extract sentiment indicators like Sentiment Subjectivity, Sentiment Polarity, and Sentiment Uncertainty. The analysis reveals significant lagged effects of monetary policy sentiments on the exchange rate, aligning with the theory that information transmission through media impacts economic variables over time.

## Objectives

- Extract and analyze sentiment features from RBI’s monetary policy reports using NLP techniques.
- Investigate the temporal effects of different sentiment indicators on exchange rates, accounting for potential lagged effects and autocorrelation.
- Assess the robustness of the sentiment analysis model and explore potential refinements for better accuracy.

## Methodology

### 1. Data Preprocessing
- Removal of stopwords and punctuation marks from RBI monetary policy reports.
- Pre-processing steps carried out using the Software Repository for Accounting and Finance.

### 2. Sentiment Extraction
- **LLMs**: Utilized pre-trained OpenAI models to extract Sentiment Subjectivity, Sentiment Polarity, and Sentiment Uncertainty from the reports.
- **FinBERT**: Used FinBERT, a transformer model specialized in analyzing financial texts, to extract sentiment polarity.

### 3. Media Uncertainty Index
- Obtained from the Economic Policy Uncertainty website. Measures policy-related economic uncertainty based on newspaper articles.

### 4. Regression Analysis
- Basic OLS linear regression revealed high multicollinearity and autocorrelation.
- Expanded analysis to include monthly data for a more granular view.

## Results

- **High Explanatory Power**: The model exhibits a high R-squared value (0.959), indicating strong explanatory power.
- **Lagged Effects**: Significant lagged effects of monetary policy sentiments on exchange rate were observed, especially with Sentiment Subjectivity and Polarity indicators.
- **Model Robustness**: Multicollinearity issues were addressed, and no significant multicollinearity was detected (checked via Variance Inflation Factors).

## Future Work

- Fine-tuning LLMs for more precise sentiment extraction.
- Exploring real-time applications for economic forecasting.

## Conclusion

This project demonstrates that monetary policy sentiments have a significant impact on exchange rate movements. The findings underscore the importance of central bank communication in financial markets and highlight the potential of sentiment analysis in economic forecasting.

## Keywords

- Sentiment Analysis
- Monetary Policy
- Large Language Models (LLMs)
- FinBERT
- Reserve Bank of India (RBI)
- Exchange Rate
- Natural Language Processing (NLP)
- Economic Forecasting
- Regression Analysis
- Lagged Effects
- Financial Texts
