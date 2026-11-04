# Social Media Engagement Analytics Using Python

## Google Colab Notebook

**Project Notebook:**  
[https://colab.research.google.com/drive/1aCcPr-SRyJrk0gIDU-V5arRqMPytzb15?usp=sharing]

---

## Project Overview

This project focuses on analyzing social media engagement data using Python. The main objective is to understand user interactions with social media posts and identify patterns in likes, comments, shares, impressions, and engagement rates.

The project involves data cleaning, exploratory data analysis, statistical analysis, and data visualization to extract meaningful insights from the dataset.

## Objectives

- Import and understand the social media dataset.
- Identify and handle missing values and duplicate records.
- Clean and standardize the dataset.
- Perform exploratory data analysis (EDA).
- Apply statistical methods to understand data distributions.
- Analyze engagement patterns across post types, categories, countries, and devices.
- Create visualizations to communicate findings.
- Identify key factors influencing social media engagement.

## Dataset Information

**Dataset Name:** `social_media_engagement_5000.csv`

The dataset contains 5,000 records and 19 columns related to social media users and their post engagement.

Some important columns include:

- `age` – Age of the user.
- `gender` – Gender of the user.
- `country` – User's country.
- `post_type` – Type of social media post.
- `post_category` – Category of the post.
- `likes` – Number of likes received.
- `comments` – Number of comments received.
- `shares` – Number of shares received.
- `watch_time_sec` – Time spent watching the post.
- `impression_count` – Number of post impressions.
- `posted_at` – Date the post was published.
- `follower_count` – Number of followers.
- `is_verified` – Verification status of the account.
- `device_type` – Device used by the user.
- `sentiment` – Sentiment associated with the post.
- `engagement_rate` – Engagement rate of the post.

## Technologies and Libraries Used

- **Python** – Programming language.
- **Pandas** – Data manipulation and analysis.
- **NumPy** – Numerical operations.
- **Matplotlib** – Data visualization.
- **Seaborn** – Statistical data visualization.
- **Plotly** – Interactive visualizations.
- **Google Colab** – Cloud-based development environment.

## Project Workflow

### 1. Data Import and Setup
- Imported the required Python libraries.
- Loaded the dataset using Pandas.
- Checked the dataset structure and data types.
- Converted date columns into datetime format.
- Performed basic NumPy operations.

### 2. Data Cleaning and Preprocessing
- Identified missing values.
- Handled missing numerical and categorical values.
- Checked and removed duplicate records.
- Corrected data types.
- Standardized categorical values.
- Checked unrealistic values.
- Created additional features such as hashtag count.

### 3. Exploratory Data Analysis (EDA)
- Examined dataset structure and summary statistics.
- Analyzed unique values and category distributions.
- Calculated correlations between numerical variables.
- Grouped data to compare engagement across different categories.

### 4. Data Wrangling
- Practiced merging and concatenating DataFrames.
- Created an engagement score.
- Applied data transformations.
- Generated grouped summaries.

### 5. Statistical Analysis
- Calculated mean, median, and mode.
- Analyzed standard deviation and variance.
- Calculated percentiles.
- Examined skewness and kurtosis.

### 6. Data Visualization
Created visualizations using Matplotlib, Seaborn, and Plotly to explore:

- Likes and impressions.
- Daily engagement trends.
- Post category distribution.
- Gender distribution.
- Age distribution.
- Engagement rate.
- Average likes by category.
- Follower count and sentiment.
- Correlation between numerical variables.
- Engagement across different devices.

## Key Analysis Areas

- Engagement performance across different post types.
- Average engagement by post category.
- Engagement patterns across countries.
- Relationship between user age and engagement.
- Engagement differences between verified and non-verified accounts.
- Device-wise watch time analysis.
- Sentiment-wise engagement performance.

## Skills Demonstrated

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Data Manipulation using Pandas
- Numerical Analysis using NumPy
- Statistical Analysis
- Data Visualization
- Feature Engineering
- Data Interpretation

## Project Files

```text
Social-Media-Engagement-Analytics/
│
├── README.md
├── social_media_engagement_5000.csv
└── Social_Media_Engagement_Analytics.ipynb
```

## Conclusion

This project demonstrates how Python can be used to clean, explore, analyze, and visualize social media engagement data. It provides practical experience in data analysis and helps develop the skills required to extract meaningful insights from real-world datasets.
