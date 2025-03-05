# Brainwave\_Matrix\_Intern

Data Science Projects on Sales Data Analysis and Social Media Sentiment Analysis

---

## 1. Retail Sales Data Analysis

### Project Overview

This project analyzes retail sales data to gain insights into sales performance, customer purchasing behavior, and product trends. The goal is to use data-driven approaches to improve business decision-making.

### Objectives

- Clean and preprocess sales data.
- Analyze sales trends and key performance metrics.
- Identify top-selling products and customer purchasing patterns.
- Visualize insights using Matplotlib and Seaborn.

### Dataset

- **File Name:** `cleaned_retail_sales.csv`
- **Columns:**
  - `transaction_id`: Unique identifier for each transaction.
  - `date`: Transaction date.
  - `customer_id`: Unique ID for each customer.
  - `gender`: Customer gender.
  - `age`: Customer age.
  - `product_category`: Category of the purchased product.
  - `quantity`: Number of units purchased.
  - `price_per_unit`: Price of a single unit.
  - `total_amount`: Total revenue from the transaction.
  - `calculated_total`: Validated total amount for accuracy.
  - `month_year`: Extracted month and year for trend analysis.

### Analysis & Key Metrics

1. **Data Cleaning & Preprocessing**
   - Converted date column to datetime format.
   - Checked and handled missing values.
   - Verified calculated totals for consistency.
2. **Sales Performance Metrics**
   - **Total Revenue:** Sum of all transaction values.
   - **Average Transaction Value:** Mean transaction revenue.
   - **Monthly Sales Trends:** Analyzed sales fluctuations over time.
3. **Customer Insights**
   - **Sales by Gender:** Revenue distribution among male and female customers.
   - **Sales by Age Group:** Identified high-spending age groups.
4. **Product Analysis**
   - **Top-Selling Categories:** Ranked categories by total revenue.
   - **Outlier Detection:** Used boxplots to visualize potential anomalies.

### Visualizations

- **Boxplots:** Outlier detection for `quantity`, `price_per_unit`, and `total_amount`.
- **Bar Charts:** Sales trends by gender, age group, and product category.
- **Line Charts:** Monthly revenue trends.

### Tools & Technologies

- **Python (Pandas, Matplotlib, Seaborn)** for data processing and visualization.
- **Jupyter Notebook** for analysis workflow.
- **GitHub** for project version control.

---

## 2. Twitter Sentiment Analysis

### Project Overview

This project focuses on analyzing public sentiment on Twitter using Natural Language Processing (NLP). The objective is to classify tweets as positive, negative, or neutral, providing insights into public opinion trends.

### Objectives

- Collect and preprocess Twitter data.
- Perform sentiment classification using NLP techniques.
- Analyze trends and sentiment distributions.
- Visualize insights using Seaborn and Matplotlib.

### Dataset

- **File Name:** `twitter_sentiment.csv`
- **Columns:**
  - `tweet_id`: Unique identifier for each tweet.
  - `date`: Date of the tweet.
  - `user_id`: Unique identifier for the user.
  - `tweet_text`: Content of the tweet.
  - `sentiment`: Labeled sentiment (positive, negative, neutral).
  - `cleaned_text`: Processed text after removing stopwords, punctuation, etc.

### Analysis & Key Metrics

1. **Data Cleaning & Preprocessing**

   - Removed special characters, stopwords, and URLs.
   - Tokenized and lemmatized text data.
   - Applied sentiment labeling using NLP models.

2. **Sentiment Analysis**

   - **Sentiment Distribution:** Percentage of positive, negative, and neutral tweets.
   - **Time-Based Trends:** Sentiment variation over time.

3. **NLP Techniques Used**

   - **VADER (Valence Aware Dictionary and sEntiment Reasoner):** Used for sentiment classification.

### Visualizations

- **Line Chart:** Sentiment trends over time.
- **Bar Chart:** Most frequently used hashtags in different sentiment categories.

### Tools & Technologies

- **Python (Pandas, NLTK, VADER, Matplotlib, Seaborn)** for data processing and visualization.
- **Jupyter Notebook** for analysis workflow.
- **GitHub** for project version control.

---

## Author

**Alphine Dora** - [GitHub](https://github.com/AlphineDora29)

