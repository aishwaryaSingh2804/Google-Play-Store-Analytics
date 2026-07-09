# Google Play Store App Analysis

An end-to-end data analysis project exploring the Google Play Store ecosystem using Python. This project focuses on data cleaning, exploratory data analysis (EDA), and sentiment analysis by combining app metadata with user reviews to uncover insights into app performance, user satisfaction, and market opportunities.

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

- Free apps dominate the Google Play Store ecosystem.
- The Family category has the largest number of published applications.
- Higher ratings generally correspond to more positive user sentiment.
- App popularity is influenced by factors beyond ratings alone.
- Some categories demonstrate high user demand despite lower competition.
- User reviews provide valuable insights beyond star ratings.
- Combining app metadata with sentiment analysis provides a more complete understanding of user satisfaction.

---

## Conclusion

This project demonstrates the complete data analysis workflow—from raw data preprocessing to business insight generation. By integrating user review sentiment with application metadata, the analysis uncovers patterns in user satisfaction, app popularity, pricing strategy, and category performance. The findings highlight how data-driven insights can support developers and businesses in making informed product and market decisions.
