---
# Video Game Sales Analysis
---
## Table of Contents
---

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)

---
### Project Overview
---

This data analysis project dives deep into the sales performance of video games from 1980 to 2016—a pivotal era in gaming history. By dissecting sales data across various dimensions like companies, platforms, genres, and regions, we aim to unearth trends and patterns that defined this period. Our goal is to identify the key players and standout titles, understand what drove their success, and provide data-driven recommendations that shed light on the dynamics of the gaming market. Through this, we'll gain a richer understanding of the industry's evolution and the factors that propelled it forward.

![Annual Global Sales](https://github.com/user-attachments/assets/fe9b8c3e-c830-4494-a522-94b63ddff3a8)

![Global Sales by Region](https://github.com/user-attachments/assets/ccb20275-1fd6-48f2-b6da-528c017b8070)

![Global Sales by Genre](https://github.com/user-attachments/assets/11aca1be-3ef1-40e1-9312-e8429fa24ad3)

![Global Sales by Publisher](https://github.com/user-attachments/assets/e9a0ed02-2641-4991-836e-88d54e29950a)

![Global Sales by Title](https://github.com/user-attachments/assets/d03cdd3d-27a0-4639-883e-f29f169d1621)

---
### Data Sources
---

The foundation of this analysis is the **"vgsales.csv"** dataset, which offers a comprehensive snapshot of video game sales from 1980 to 2016. This dataset encompasses detailed information on over 11,493 game titles, including:
- Game Titles and Genres: Names of the games along with their genres, giving insight into the variety of game types that have been popular over the years.
- Publishing Companies: Information about the publishers responsible for each game, allowing for analysis of the most successful companies in the industry.
- Platforms: Details on the gaming platforms (e.g., PlayStation, Xbox, Nintendo systems) each game was released on, highlighting platform popularity and trends.
- Release Years: The year each game was launched, which is crucial for identifying temporal trends and shifts in the gaming market.
- Regional Sales Figures: Sales data broken down by region—North America, Europe, and Japan—providing a global perspective on the gaming industry's reach and consumer preferences.
The dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/gregorut/videogamesales), ensuring reliable and credible information for our analysis. Before diving into the analysis, the dataset was meticulously cleaned and preprocessed to handle missing values, correct inconsistencies, and standardize data entries across different fields.

---
### Tools
---

- Excel – Data Cleaning 
    - ([Video Game Sales](https://www.kaggle.com/datasets/gregorut/videogamesales))
- Tableau – Creating Reports

---
### Data Cleaning
---

In the initial data preparation phase, I performed the following tasks:
1. Data Loading and Inspection.
2. Handling Missing Values,
3. Data Cleaning and Formatting.

---
### Exploratory Data Analysis
---

EDA involving exploring the sales data to answer key questions, such as:
- What is the overall sales trend?
- Which genres are top Sellers?
- When are the peak sales periods?
- Which platforms are most successful?
- Which regions has the most demand?

---
### Data Analysis
---

- Created Buckets.
- Creates Sales Measures:
   - ```[Global Sales] – [EU Sales]```

---
### Results
---

The analysis results are summarized as follows:
1. Video game sales have been steadily increasing with a noticeable perk during the turn of the millennia.
2. The Action Genera is the best-performing category in terms of sales and revenue.
3. Customer segments with high lifetime value (LIV) should be targeted for marketing efforts.

---
### Recommendations
---

Based on the analysis, we recommend the following actions:
- Invest in marketing and promotions during peak sales seasons in the United States to maximize revenue.
- Focus on expanding and promoting products in the **Action Genera**.
- Implement a customer segmentation strategy to target high LTV customers effectively.

---
### Limitations
---

This analysis faced limitations that could affect result interpretation:

1.	Removal of Zero Sales Values:
   - Data Exclusion: I excluded all entries with zero sales values across all regions to prevent skewing the analysis with non-contributory data.
   - Impact on Conclusions: While this helped in focusing on games with measurable impact, it may have introduced bias by excluding less popular or newly released games that hadn't reported sales yet. This could affect the generalizability of my conclusions, potentially overstating the success within certain genres or platforms.

2.	Presence of Outliers:
   - Influential Data Points: Despite data cleaning, several outliers with exceptionally high sales remained. These can disproportionately affect statistical measures like mean sales and correlation coefficients.
   - Correlation Effects: The positive correlations observed between genres, number of sales, and revenue might be heavily influenced by these blockbuster titles, possibly masking trends among more moderate-performing games.

3.	Limited Time Frame and Data Scope:
   - Historical Data: The dataset spans from 1993 to 2015 and doesn't include data beyond this period. The gaming industry has evolved significantly since then, especially with the rise of digital distribution platforms.
   - Exclusion of Digital Sales: The dataset primarily covers physical sales and may not account for digital downloads, online purchases, or mobile gaming revenues, which became increasingly significant in the latter years and could alter sales dynamics.

4.	Genre Classification:
   - Broad Categories: Genres in the dataset are categorized broadly, potentially oversimplifying the diversity of games within each genre.
   - Nuanced Preferences: This broad classification might overlook niche sub-genres that have dedicated fan bases, affecting the accuracy of genre-based analyses.

5.	Regional Sales Data Limitations:
   - Incomplete Reporting: Sales data may be inconsistently reported across different regions due to varying tracking methods and market transparency.
   - Cultural Influences: Regional preferences and cultural differences can significantly impact game popularity, which might not be fully captured, thereby affecting comparative analyses.


---
### References
---

1. [Youtube](https://www.youtube.com/watch?v=j8FSP8XuFyk)
2. [Kaggle](https://www.kaggle.com/datasets/gregorut/videogamesales)
