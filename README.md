# 📊 YouTube Data Analysis Project

This project performs an in-depth data analysis on a YouTube dataset, focusing on trends such as top-performing videos, correlations between metrics, distribution by country, and tag usage. The cleaned dataset, exported as `youtube2.csv`, was further used to create a dynamic dashboard in Power BI to visualize key insights.

## 📋 Project Overview

The analysis includes:
- **Data Cleaning**: Removing irrelevant columns, handling duplicates, and ensuring correct data types.
- **Exploratory Data Analysis (EDA)**: Visualizing key statistics, checking distributions, and analyzing relationships.
- **Top/Bottom Analysis**: Identifying top and bottom videos, channels, and countries based on views, likes, dislikes, and other metrics.
- **Visualization**: Correlation heatmaps, distribution plots, count plots by country and day of the week, and a word cloud for frequently used tags.
- **Dashboard Creation**: A Power BI dashboard was created to provide an interactive view of the insights.

## 📂 Key Files

- **`youtube.zip` and `youtube 2.zip`**: The original split datasets containing YouTube video details. These were merged for analysis.
- **`youtube_analysis.ipynb`**: Jupyter notebook with all data cleaning, EDA, and visualizations.
- **`youtube2.csv`**: The cleaned and merged dataset exported after analysis.
- **Power BI Dashboard Files**:
  - **`Youtube Dashboard.pbit`**: Power BI template file.
  - **`Youtube Dashboard.pbix`**: Power BI report file.
  - **`Youtube Dashboard.pdf`**: PDF version of the Power BI dashboard for quick reference.

## 📚 Libraries Used

- **Pandas** and **NumPy**: For data manipulation and cleaning.
- **Seaborn** and **Matplotlib**: For data visualization.
- **WordCloud**: For generating a word cloud of popular tags.
- **Warnings**: To ignore unnecessary warnings during analysis.

## 📝 Steps in Analysis

1. **Data Loading and Merging**:
   - Loaded the split datasets from `youtube.zip` and `youtube 2.zip`.
   - Merged the datasets to create a single comprehensive dataset for analysis.
   
2. **Data Cleaning**:
   - Removed unnecessary columns such as `comments_disabled`, `ratings_disabled`, and `video_error_or_removed`.
   - Checked for duplicate records and corrected data types for date fields.

3. **Exploratory Data Analysis**:
   - Used descriptive statistics and visualizations to understand distributions and correlations.

4. **Custom Functions for Top/Bottom Analysis**:
   - Defined functions to identify the top 5 and bottom 5 videos/channels based on views, likes, dislikes, and comments.

5. **Correlation Matrix**:
   - Generated a heatmap to identify relationships between key variables (views, likes, dislikes, and comment count).

6. **Country-wise and Day-wise Analysis**:
   - Analyzed counts of videos based on country and day of publishing.

7. **Word Cloud for Tags**:
   - Generated a word cloud to identify frequently used tags in video descriptions.

## 📊 Power BI Dashboard

The Power BI dashboard provides an interactive way to explore insights from the YouTube dataset. Key visuals include:
- **Total Number of Categories**: Displayed as a bar chart.
- **Number of Videos Per Channel**: Shows the distribution of videos across different channels.
- **Videos Published by Weekdays**: A pie chart illustrating the distribution of videos published on different days of the week.
- **Total Likes, Dislikes, Comments, and Views**: A summary of engagement metrics in billion and million scales.
- **Total Number of Likes by Country**: Bar chart comparing likes across countries (e.g., GB, US, Canada, France).
- **Total Number of Dislikes and Comments**: Bar chart showing dislikes and comments by country.
- **Videos Published by Month**: A time-series chart showing the number of videos published across months.

## 🎯 Project Outcomes

This project highlights trends in YouTube video performance that could inform data-driven content creation and marketing strategies. Key insights include:
- Top and bottom videos by views, likes, and dislikes.
- Trends based on country and day of the week.
- Frequently used tags associated with trending content.

## 🛠️ How to Run

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/youtube-data-analysis.git
2. **Install dependencies**:
   - Ensure all required libraries (**Pandas**, **NumPy**, **Seaborn**, **Matplotlib**, **WordCloud**) are installed.

3. **Run the Jupyter Notebook**:
   - Open `youtube_analysis.ipynb` and run the cells to view the analysis and visualizations.

4. **Power BI Dashboard**:
   - Use `Youtube Dashboard.pbit` or `Youtube Dashboard.pbix` to explore the interactive dashboard in Power BI.
