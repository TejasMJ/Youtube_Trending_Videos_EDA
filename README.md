# YouTube Trending Videos EDA 📊

A comprehensive **Exploratory Data Analysis (EDA)** on YouTube trending videos across multiple countries using Python, Pandas, Plotly, Seaborn, and Matplotlib to uncover insights about content popularity and engagement metrics.

---

## 🌟 Features

### Core Features
- **Data Cleaning & Preprocessing:** Handling missing values, duplicates, and type conversions.
- **Trending Insights:** Identify patterns in trending videos by country, day of the week, and time frames.
- **Engagement Analysis:** Insights on views, likes, dislikes, and comments.
- **Sentiment & Interaction Analysis:** Explore public sentiment based on like/dislike ratios and comment counts.
- **Visualization:** Interactive and static plots using Plotly, Seaborn, and Matplotlib.

---

## 🗂 Project Structure

The project folder is organized as follows:

```text
YouTube_Trending_Videos_EDA/
├── youtube.csv                         # Dataset of trending YouTube videos
├── YouTube_Trending_Videos_EDA.ipynb   # Jupyter Notebook with full EDA
├── requirements.txt                    # Python dependencies
└── venv/                               # Virtual environment

```

---

## 🏗️ EDA Architecture

```text
+----------------------+  
|      DATA LAYER      |  
|  Raw app dataset     |  
|  (CSV / Excel)       |  
+----------+-----------+  
           ↓  
+-------------------------+  
|  ANALYSIS LAYER         |  
|  - Data Cleaning        |  
|  - Statistical Insights |  
|  - Category & Rating    |  
|    Analysis             |  
|  - User Engagement      |  
|  - Pricing & Revenue    |  
+----------+--------------+  
           ↓  
+---------------------------------------+  
| VISUALIZATION LAYER                   |  
|  - Interactive Dashboards (Plotly)    |  
|  - Static Plots (Seaborn & Matplotlib)|  
|  - Scatter, Bar, Boxplots             |  
+---------------------------------------+  

```

---

## 🛠 Tech Stack

- **Language:** Python 3.8+
- **Libraries:**
  - **Data Manipulation:** Pandas, NumPy
  - **Visualization:** Matplotlib, Seaborn, Plotly
- **Environment:** Jupyter Notebook
- **Data Source:** [Kaggle – YouTube Trending Videos](https://www.kaggle.com/datasets/thedevastator/youtube-trending-videos-dataset?resource=download)

---

## 📊 Dataset Overview

- **Rows:** 40,000+ trending videos
- **Columns include:** title, channel_title, publish_date, trending_date, time_frame, published_day_of_week, publish_country, tags, views, likes, dislikes, comment_count, comments_disabled, ratings_disabled
  
**Context:**  
This dataset provides structured insights into YouTube trending videos across multiple countries. It enables analysis of viewer engagement, content popularity, and patterns in trending content.

**Acknowledgements:**  
- Data sourced from YouTube via Kaggle.
- Thanks to Kaggle contributors for making this dataset accessible.

**Inspiration:**  
Analyzing trends in YouTube videos can help marketers, content creators, and researchers make data-driven decisions about content creation, marketing strategies, and audience engagement.

---

## 🚀 Quick Start

### 1. Clone Repository
```bash
git clone https://github.com/TejasMJ/Youtube_Trending_Videos_EDA.git
cd Youtube_Trending_Videos_EDA
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```
### 3. Activate Virtual Environment
#### Windows:
```bash
.\venv\Scripts\activate
```
#### Mac/Linux:
```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```
### 5. Run Notebook

```bash
jupyter notebook
```

# 📊 App Analysis Project

## Detailed Analysis Scope

### Data Cleaning & Preprocessing
- Remove duplicates
- Handle missing values
- Convert column types (e.g., views, likes, dislikes to numeric, publish_date to datetime)

### Trending Insights
- Identify trends in trending videos by country and day of the week
- Determine optimal publishing days for maximum engagement
- Analyze time frames for video trends

### Engagement Analysis
- Explore views, likes, dislikes, and comment counts
- Identify highly engaging and viral content
- Compare like/dislike ratios to assess public sentiment

### Sentiment & Interaction Analysis
- Analyze comment counts and determine impact of disabled comments
- Explore correlation between likes, dislikes, and engagement
- Identify controversial vs positively received videos

### Visualization
- Interactive dashboards using **Plotly**
- Static plots using **Seaborn** & **Matplotlib**

## 👨‍💻 Author
**Tejas Jadhav**  

- GitHub: [@tejas-jadhav](https://github.com/TejasMJ)  
- LinkedIn: [Tejas Jadhav](https://www.linkedin.com/in/tejas-m-jadhav/)
