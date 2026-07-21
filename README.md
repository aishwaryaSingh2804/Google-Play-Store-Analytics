# Google Play Store Product Analytics: Understanding User Satisfaction, Market Opportunities, and Monetization Strategies

This project is a Product Analytics case study on the Google Play Store. The objective was to understand what drives app performance and use historical Play Store data to generate insights that could help a product team or a new app developer make better business decisions.

I worked with two datasets—one containing app-level information such as category, installs, ratings and pricing, and another containing user reviews with sentiment information. After cleaning and preparing both datasets, I analyzed them to answer three main business questions:

First, if someone wants to launch a new app, which categories offer high demand with relatively lower competition?

Second, what is the trade-off between offering a free app versus a paid app?

Third, are star ratings alone enough to measure user satisfaction, or do user reviews and sentiment provide additional insights?

Based on these analyses, I generated recommendations around market selection, monetization strategy, and user satisfaction by combining quantitative metrics like installs and ratings with qualitative insights from user reviews.
---

## Project Objectives

- Clean and preprocess raw Google Play Store datasets.
- Perform comprehensive exploratory data analysis (EDA).
- Analyze app popularity, ratings, pricing, and category trends.
- Integrate user review sentiment with app metadata.
- Generate actionable business insights from the combined dataset.

---

## Dataset

The project uses two publicly available datasets:

### 1. Google Play Store Apps
Contains information about applications published on the Google Play Store, including:

- App Name
- Category
- Rating
- Reviews
- Size
- Installs
- Price
- Type
- Genres
- Content Rating
- Android Version

### 2. Google Play Store User Reviews
Contains user-generated reviews with sentiment analysis information, including:

- App Name
- Review
- Sentiment
- Sentiment Polarity
- Sentiment Subjectivity

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Workflow

```
Data Loading
        ↓
Data Exploration
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis
        ↓
Merge Apps & Reviews Dataset
        ↓
Sentiment Analysis
        ↓
Business Insights
        ↓
Conclusion
```

---

## Data Cleaning

The following preprocessing steps were performed:

- Removed duplicate records
- Handled missing values
- Converted data types
- Cleaned the `Installs` column by removing commas and '+' symbols
- Converted `Price` to numeric values
- Standardized app sizes into MB
- Parsed date columns
- Removed inconsistent and invalid records
- Prepared datasets for analysis and merging

---

## Exploratory Data Analysis

### Apps Dataset

The following analyses were performed:

- Distribution of app ratings
- Category-wise app distribution
- Rating analysis by category
- Reviews vs Installs
- Rating vs Installs
- Free vs Paid apps
- Market competition vs demand across categories

### Merged Dataset

After merging the Apps and Reviews datasets, the following analyses were performed:

- Rating vs Sentiment Polarity
- Category-wise Average Sentiment
- Free vs Paid Sentiment Comparison
- Sentiment Distribution across Categories
- Most Loved and Most Criticized Apps

---

## Key Business Insights

The analysis showed that market demand and competition vary significantly across categories, so developers should evaluate both before entering a market. I also found that free apps generally achieve much higher adoption, while paid apps tend to receive slightly better ratings, highlighting a trade-off between growth and monetization. Finally, by combining ratings with review sentiment, I showed that star ratings alone don't fully capture user experience, and textual feedback provides valuable context for understanding user satisfaction.

---

## Conclusion

This project demonstrates the complete data analysis workflow—from raw data preprocessing to business insight generation. By integrating user review sentiment with application metadata, the analysis uncovers patterns in user satisfaction, app popularity, pricing strategy, and category performance. The findings highlight how data-driven insights can support developers and businesses in making informed product and market decisions.
