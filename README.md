# 📊 YouTube Sentimental Analysis Using NLP

This project provides an in-depth analysis of a YouTube dataset, focusing on key metrics such as video performance, audience engagement, country-based distribution, and trends in tag usage. Additionally, sentiment analysis has been incorporated to classify video titles as Positive, Neutral, or Negative, enhancing insights into content reception.

---

## 📋 Project Overview

### Key Features:
1. **Data Cleaning**:
   - Removed irrelevant columns and duplicate records.
   - Corrected data types for date columns.
   
2. **Exploratory Data Analysis (EDA)**:
   - Visualized correlations between views, likes, dislikes, and comments.
   - Analyzed trends by country, day of the week, and month.
   - Generated word clouds to showcase popular tags.

3. **Top/Bottom Analysis**:
   - Identified top and bottom videos and channels based on views, likes, dislikes, and comments.

4. **Sentiment Analysis**:
   - Classified video titles as Positive, Neutral, or Negative using TextBlob.
   - Visualized sentiment distribution.

5. **Power BI Dashboard**:
   - Created an interactive dashboard for visualizing insights.

---

## 📂 Project Structure

- **`youtube.zip` and `youtube2.zip`**: Original split datasets containing YouTube video details.
- **`youtube_final.ipynb`**: Jupyter Notebook with all analysis steps and visualizations.
- **`youtube2.csv`**: Cleaned dataset exported after preprocessing.
- **Power BI Dashboard Files**:
  - `Youtube Dashboard.pbit`: Power BI template file.
  - `Youtube Dashboard.pbix`: Power BI report file.
  - `Youtube Dashboard.pdf`: PDF version of the dashboard.

---

## 📝 Steps in Analysis

### 1. Data Loading and Cleaning:
- Merged datasets from `youtube.zip` and `youtube2.zip`.
- Removed columns such as `comments_disabled`, `ratings_disabled`, and `video_error_or_removed`.
- Checked for duplicate records and corrected date formats.

### 2. Exploratory Data Analysis (EDA):
- Visualized distributions and correlations using:
  - Heatmaps
  - Count plots
  - Pair plots
- Generated a Word Cloud for popular tags.

### 3. Top/Bottom Analysis:
- Identified top and bottom 5 videos/channels based on:
  - Views
  - Likes
  - Dislikes
  - Comments

### 4. Sentiment Analysis:
- Classified video titles into Positive, Neutral, or Negative using TextBlob.
- Visualized the sentiment distribution using a count plot.

### 5. Power BI Dashboard:
- Interactive dashboard highlights:
  - Total number of categories.
  - Videos published by weekdays and months.
  - Total likes, dislikes, comments, and views.
  - Country-wise distribution of engagement metrics.

---

## 🛠️ How to Run

### Clone the Repository:
```bash
git clone https://github.com/sahilmaurya881/youtube-data-analysis.git
