
# Consumer Sentiment Analysis

## Overview
- **Total Reviews:** 5,000
- **Categories:** 8
- **Brands:** 38
- **Date Range:** 2024-01-01 to 2024-12-31
- **Model:** DistilBERT (distilbert-base-uncased-finetuned-sst-2-english)
- **Model Accuracy:** 76.36%
- **Avg Confidence Score:** 98.88%

## Dashboard Sections
1. KPI Cards - Positive, Negative, Neutral Sentiment, Avg Rating
2. Sentiment Distribution by Category
3. Monthly Sentiment Trend 2024
4. Average Rating by Brand (Top 15)
5. Model Confidence Score Distribution
6. Overall Sentiment Donut Chart
7. Reviews by Category
8. Rating Distribution
9. Negative Sentiment Rate by Category

## Key Insights
- 67.4% positive sentiment across all categories
- Electronics and Automotive have highest negative rates
- Model confidence averages 98.88% across all predictions
- Average customer rating of 3.70/5.0

## Technologies
- Python, Pandas, NumPy
- HuggingFace Transformers (DistilBERT)
- PyTorch (GPU accelerated)
- Matplotlib, Seaborn
- Google Colab (T4 GPU)
