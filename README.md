# WeRateDogs Data Wrangling & Analysis

> **Project Overview**: This project involves the full data lifecycle—from gathering data using APIs to cleaning messy data and visualizing insights about the famous "WeRateDogs" Twitter account.

## 🛠️ Tech Stack
* **Language**: Python
* **Libraries**: Pandas, NumPy, Requests, Tweepy (Twitter API), Matplotlib, Seaborn

## 🧹 The Wrangling Process
I addressed over 10 quality and tidiness issues to ensure the data was ready for analysis:

### 1. Data Acquisition
* **API Integration**: Extracted retweet and favorite counts using the **Tweepy** library.
* **Web Scraping**: Procured image predictions from a URL using the **Requests** library.

### 2. Data Cleaning
* **Structural Fixes**: Corrected timestamp formats and removed HTML tags from the 'source' column.
* **Feature Engineering**: Concatenated rating columns to form a unified 'rating' metric.

## 📊 Key Insights
* **Engagement Winner**: "Puppers" (younger dogs) consistently achieve higher retweets and favorites than "doggos".
* **Creative Impact**: Humorous and witty captions paired with high ratings generate significantly more interaction.
