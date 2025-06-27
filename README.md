# 🎧 Music and Mental Health Analysis

This project explores how music consumption—streaming habits, genres, and listening behaviors—relates to mental health conditions such as anxiety, depression, insomnia, and OCD. Based on a Kaggle dataset of 610 respondents, we performed statistical tests and visual analyses to derive insights on listener behavior and the therapeutic role of music.

## 🧠 Project Title
**An Exploratory Analysis on Music and Mental Health**

## 👩‍💻 Author
Navya Kamath  
M.Sc. in Statistics, SDM College, Ujire  
Supervised by Ms. Shwetha Kumari

## 🎯 Objectives
- Identify the most used music streaming services and preferred genres.
- Understand listening behavior by age, work status, and time spent.
- Analyze mental health patterns (anxiety, depression, etc.) among music listeners.
- Explore relationships between musical traits (e.g., instrumentalist vs composer, exploratory vs foreign language music).
- Compare BPM (Beats Per Minute) across genres using ANOVA.
- Assess the self-reported impact of music on mental health.

## 📊 Dataset
- 📁 Source: [Kaggle - MXMH Survey Results](https://www.kaggle.com/datasets/catherinerasgaitis/mxmh-survey-results)
- 🎧 31 features, 610 respondents
- 🎼 Includes demographic data, streaming platforms, genre preferences, mental health scores, and music behavior.

## 🛠️ Tools & Techniques
- **Languages:** Python, R
- **Libraries:** pandas, seaborn, matplotlib, scipy, statsmodels
- **Methods Used:**
  - Chi-square Test of Independence
  - One-Way ANOVA with Post-hoc Tukey Test
  - Visualizations: Bar Charts, Pie Charts, Histograms, Boxplots, Frequency Curves

## 🔍 Key Insights
1. **Spotify** is the most used streaming service; **Pandora** is the least used.
2. **Rock, Pop, and Metal** are the most preferred genres, while **Gospel and Latin** are least preferred.
3. ~80% of people listen to music **while working**.
4. Most listeners spend **1 to 3 hours per day** on music.
5. The majority of listeners are **young adults (17–30)**.
6. **Gospel** is popular among 50+ age group; **Latin and K-Pop** among <20.
7. There is a **significant association** between being an **instrumentalist and a composer**.
8. Listeners of **exploratory music** are more likely to enjoy **foreign language** music.
9. **Mean BPM significantly differs** by genre (e.g., Metal vs Classical, Rock vs Metal).
10. **Insomnia and OCD** are less commonly reported, while **anxiety and depression** are more prevalent.
11. ~76% of listeners say music **improves their mental health**, while 22% feel no change and 2% feel worse.
