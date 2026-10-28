# Netflix Customer Analysis 📺

## Project Overview

This project analyzes Netflix customer data to uncover insights into customer demographics, subscription preferences, viewing behavior, and content interests.

Using Python and data analysis libraries, the dataset was explored to identify patterns across age groups, genders, subscription plans, and geographic regions. The findings can help streaming platforms better understand user engagement and content consumption trends.

---

## Business Objectives

- Understand customer viewing behavior.
- Analyze subscription plan preferences.
- Identify the most popular genres among customer segments.
- Compare watch time across demographic groups.
- Generate actionable insights for customer engagement.

---

## Dataset Information

| Metric | Value |
|----------|--------|
| Records | 5,000 |
| Customers | 5,000 |
| Features | 14 |
| Missing Values | 0 |

### Dataset Features

- Customer ID
- Gender
- Age
- Region
- Subscription Type
- Watch Hours
- Favorite Genre
- Device Type
- Account Details

> **Note:** The dataset does not contain a churn indicator column. Therefore, churn prediction or churn rate analysis was not performed.

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Exploratory Data Analysis

### Average Watch Hours by Gender

| Gender | Average Watch Hours |
|----------|-------------------|
| Other | 11.77 |
| Male | 11.62 |
| Female | 11.56 |

**Insight:** Customers categorized as "Other" spend slightly more time watching Netflix content.

---

### Average Watch Hours by Age Group

| Age Group | Average Watch Hours |
|------------|-------------------|
| 18–25 | 10.97 |
| 26–39 | 11.84 |
| 40+ | 11.75 |

**Insight:** Customers aged 26–39 years are the most engaged viewers.

---

### Subscription Distribution by Gender

| Gender | Basic | Standard | Premium |
|----------|----------|----------|----------|
| Female | 606 | 554 | 551 |
| Male | 505 | 581 | 568 |
| Other | 550 | 511 | 574 |

**Insight:** Premium subscriptions show strong adoption across all gender categories.

---

## Genre Preference Analysis

### By Age Group

| Age Group | Most Preferred Genre |
|------------|---------------------|
| 18–25 | Sci-Fi |
| 26–39 | Drama |
| 40+ | Documentary |

### By Gender

| Gender | Favorite Genre |
|----------|---------------|
| Female | Sci-Fi |
| Male | Drama |
| Other | Romance |

### By Subscription Type

| Subscription Type | Favorite Genre |
|------------------|----------------|
| Basic | Romance |
| Premium | Drama |
| Standard | Sci-Fi |

### By Region

| Region | Most Popular Genre |
|---------|-------------------|
| Africa | Documentary |
| Asia | Horror |
| Europe | Sci-Fi |
| North America | Action |
| Oceania | Drama |
| South America | Drama |

---

## Key Insights

- Customers aged 26–39 have the highest average watch time.
- Premium subscriptions are popular across all gender categories.
- Drama and Sci-Fi are among the most preferred genres.
- Viewing preferences vary significantly across demographic and regional segments.
- Content recommendation strategies can be improved using demographic insights.

---

## Future Improvements

- Build an interactive Power BI dashboard.
- Perform customer segmentation using clustering techniques.
- Develop a recommendation system.
- Incorporate churn-related data for predictive analytics.
- Deploy an interactive dashboard using Streamlit.

---

## Project Structure

```text
Netflix-Customer-Analysis/
│
├── data/
│   └── netflix_customer_data.csv
│
├── notebooks/
│   └── netflix_analysis.ipynb
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

## Author

**Ashif**

- Python Developer
- Data Analysis Enthusiast
- Aspiring Data Scientist

---

⭐ If you found this project useful, consider giving it a star on GitHub.
