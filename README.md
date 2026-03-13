# 🎬 Netflix Movie Content Analysis (2019–2021)

## 📌 Project Overview
Netflix is one of the largest digital streaming and entertainment platforms in the world. Movies are one of the primary types of content offered on the platform.

This project analyzes Netflix movie content from **2019 to 2021** to understand trends in movie additions, identify dominant genres and countries, and provide **data-driven recommendations** to support future content growth.

The dataset used in this analysis contains **3,276 movie records**.

---

# ❓ Business Problem

During the observed period, the number of movies added to Netflix experienced a decline:

- **2019 → 2020:** -8.81%  
- **2020 → 2021:** -36.67%

This decline raises the following business question:

**How can Netflix increase movie content growth from -36.67% to -27.86% in the following year?**

---

# 🎯 Project Objectives

- Analyze the **trend of movie content growth on Netflix**
- Identify **countries contributing the most movie content**
- Analyze **dominant movie genres**
- Identify **directors contributing the most movies**
- Provide **data-driven recommendations** to increase movie content growth

---

# 📂 Dataset Description

The dataset contains information about movies available on Netflix with the following attributes:

| Column | Description |
|------|------|
| show_id | Unique identifier for each movie |
| type | Content type (Movie or TV Show) |
| title | Movie title |
| director | Name of the movie director |
| cast | List of actors |
| country | Country of production |
| date_added | Date when the movie was added to Netflix |
| years_added | Year when the movie was added |
| release_year | Year when the movie was released |
| rating | Age rating classification |
| duration | Duration of the movie |
| listed_in | Genre categories |
| description | Short description of the movie |

---

# 🧹 Data Cleaning

Before conducting the analysis, several data cleaning steps were performed to prepare the dataset:

- Removing duplicate records based on the **show_id** column
- Handling missing values in the **country** and **director** columns
- Formatting data variables such as converting **date_added** into date format and extracting **years_added**
- Splitting multi-value columns such as **country** and **listed_in** for more detailed analysis

---

# 🔍 Data Analysis Workflow

This project follows a standard data analysis workflow:

1. **Business Understanding**  
Understanding the decline in movie content growth.

2. **Data Understanding**  
Exploring the dataset and identifying key variables.

3. **Data Preparation**  
Cleaning and transforming the dataset.

4. **Exploratory Data Analysis (EDA)**  
Identifying patterns in movie growth, countries, genres, and directors.

5. **Visualization & Insight Extraction**  
Creating visualizations to identify meaningful insights.

---

# 📊 Key Analysis Metrics

### Movie Content Growth per Year
Analyzes how many movies are added to Netflix each year.

### Movie Content Growth by Country
Identifies which countries contribute the most movies to Netflix.

### Genre Distribution
Analyzes the most common movie genres on Netflix.

### Director Contribution
Identifies directors who have contributed the most movies.

---

# 💡 Key Insights

### Country Contribution
The **United States** contributes the highest number of movies with **1,676 movies**, followed by **India**. Other countries contribute significantly fewer movies.

### Genre Distribution
The most dominant genres on Netflix include:

- Dramas
- International Movies
- Comedies

### Dominant Genres in the United States
The most common genres produced in the United States include:

- Dramas
- Comedies
- Action & Adventure
- Children & Family Movies
- Independent Movies

### Director Contribution
The director with the highest number of movies is **Cathy Garcia-Molina** with **13 movies**, while **Robert Rodriguez** ranks fifth with **8 movies**.

---

# 🧾 Conclusion

The analysis shows that the decline in Netflix movie additions is influenced by **content concentration in a limited number of countries and genres**. Most movies originate from the **United States and India**, while other countries contribute relatively little.

This indicates opportunities to expand content production across more countries and diversify genre offerings.

---

# 🚀 Recommendations

### Expand Movie Production Across More Countries
Encourage movie production in countries with lower contributions to increase global content diversity.

### Diversify Genre Offerings
Expanding the variety of movie genres can help attract broader audiences.

### Collaborate with Experienced Directors
Working with experienced directors may help produce high-quality movies and strengthen Netflix's competitiveness.

---

# 🛠 Tools & Technologies

The analysis was conducted using:

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

# 🔮 Future Improvements

Possible improvements for this project include:

- Movie rating analysis
- Movie duration analysis
- Release year trend analysis
- Predictive modeling for movie popularity