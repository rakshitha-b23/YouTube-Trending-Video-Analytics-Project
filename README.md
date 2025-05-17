# YouTube Trending Video Analytics 📊

## 🔍 Objective  
To uncover patterns in trending YouTube videos across multiple countries using data analytics techniques and interactive dashboards.

---

## 🛠 Tools Used  
- **Python**: Data cleaning, transformation, sentiment analysis  
- **SQL (SQLite)**: Ranking categories by average views  
- **Power BI**: Dashboard and visual storytelling  
- **Libraries**: pandas, TextBlob, sqlite3

---
## 📂 Project Structure 

```bash
.
├── datasets/                      # Raw YouTube data (country-wise)
├── scripts/
│   ├── data_cleaning.py           # Python script for preprocessing
│   ├── sentiment_analysis.py      # Sentiment labeling using TextBlob
│   └── sql_analysis.py            # SQL query for ranking categories
├── dashboard/                     # Power BI Dashboard file (.pbip)
├── output/
│   └── combined_files.xlsx        # Final cleaned dataset
├── README.md
└── YouTube_Trending_Report.pdf    # Final report
```

## 🔍 Key Steps
1. Merged country-level datasets
2. Cleaned & standardized columns
3. Performed sentiment analysis on video titles & tags
4. Used SQL to rank categories by average views
5. Built a Power BI dashboard for visualization

## 📊 Dashboard Highlights
- Regional comparison of views, likes, comments
- Sentiment analysis breakdown (positive/neutral/negative)
- Monthly and yearly trends in trending videos
- Category-level viewership rankings

## 📌 Key Insights  
- **Great Britain** leads in video views and likes  
- **Neutral sentiment** is most common among trending videos  
- Category IDs between **10–15** had the highest views  
- **May 2018** marked the highest trending activity

---
## 📄 Report
See `YouTube Trending Video Analytics Report.pdf` for a summary of the analysis and conclusions.


---






