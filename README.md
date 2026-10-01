# 🎧 Music & Mental Health: Statistical Analysis of Listening Behavior

An exploratory statistical analysis investigating relationships between music listening habits, genre preferences, listener characteristics, and self-reported mental health patterns.

The project uses survey data from **610 respondents** and applies statistical hypothesis testing and data visualization to identify patterns in music consumption and reported mental health outcomes.

> **Important:** The analysis identifies associations and patterns in survey responses. It does not establish that music causes changes in mental health.

---

## 📌 Project Overview

Music is consumed in different ways depending on age, occupation, personal preferences, and listening habits. This project explores whether these differences are associated with variations in self-reported mental health indicators and musical behavior.

The analysis focuses on questions such as:

* Which music streaming platforms and genres are most popular?
* How much time do people spend listening to music?
* How do listening preferences vary across age groups?
* Are certain musical characteristics associated with one another?
* Does average BPM differ significantly between music genres?
* What mental health conditions are most commonly reported in the dataset?
* How do respondents perceive the effect of music on their mental health?

---

## 🎯 Objectives

1. Analyze music streaming and genre preferences.
2. Understand listening behavior across demographic groups.
3. Explore patterns in self-reported anxiety, depression, insomnia, and OCD.
4. Investigate relationships between musical characteristics.
5. Test whether average BPM differs across music genres.
6. Examine respondents' self-reported perceptions of music's impact on mental health.

---

## 📊 Dataset

**Source:** Kaggle – MXMH Survey Results

* **Observations:** 610 respondents
* **Features:** 31
* **Data type:** Survey data
* **Information included:**

  * Demographics
  * Music streaming platforms
  * Genre preferences
  * Listening duration
  * Musical characteristics
  * Mental health indicators
  * Self-reported impact of music on mental health

Because the dataset is based on survey responses, the findings should be interpreted as patterns within the sampled respondents rather than estimates of the general population.

---

## 🛠️ Tools & Technologies

### Programming

* Python
* R

### Python Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Statsmodels

### Statistical Methods

* Descriptive statistics
* Chi-square test of independence
* One-way ANOVA
* Tukey's HSD post-hoc test

### Visualization

* Bar charts
* Pie charts
* Histograms
* Boxplots
* Frequency curves

---

## 🔬 Methodology

### 1. Exploratory Data Analysis

The dataset was first explored to understand:

* Variable distributions
* Missing values
* Demographic characteristics
* Streaming platform usage
* Genre preferences
* Listening duration
* Mental health response patterns

Visualizations were then used to identify important trends and differences across groups.

### 2. Categorical Association Analysis

A **Chi-square test of independence** was used to investigate relationships between categorical variables.

For example, the analysis examined the relationship between:

* Being an instrumentalist
* Being a composer

The analysis found a statistically significant association between these variables in the sample.

### 3. Genre Comparison Using ANOVA

A **one-way ANOVA** was used to investigate whether mean BPM differed across music genres.

Where the overall ANOVA indicated differences between groups, **Tukey's HSD post-hoc test** was used to identify specific genre pairs contributing to those differences.

The analysis found statistically significant differences in mean BPM between several genre pairs, including comparisons such as:

* Metal vs Classical
* Rock vs Metal

### 4. Mental Health Analysis

Self-reported indicators of:

* Anxiety
* Depression
* Insomnia
* OCD

were examined to understand their prevalence within the dataset and their relationship with music-listening behavior.

---

## 📈 Key Findings

### Music Consumption

* **Spotify** was the most commonly used streaming platform in the dataset.
* **Rock, Pop, and Metal** were among the most preferred genres.
* Approximately **80% of respondents reported listening to music while working**.
* Most respondents reported listening to music for approximately **1–3 hours per day**.
* The sample contained a large proportion of young adult listeners, particularly those aged **17–30**.

### Age & Genre Preferences

Genre preferences varied across age groups in the sample.

Examples observed in the analysis included:

* Gospel being relatively more common among respondents aged 50+.
* Latin and K-Pop appearing relatively more frequently among respondents under 20.

These findings describe the sample and should not be interpreted as population-wide preferences.

### Musical Characteristics

The analysis found:

* A statistically significant association between being an **instrumentalist** and being a **composer**.
* Respondents who reported enjoying **exploratory music** were more likely to report enjoying **foreign-language music**.
* Mean BPM differed significantly across several genres.

### Mental Health Patterns

Among the mental health variables examined:

* Anxiety and depression were reported more frequently than insomnia and OCD.
* Approximately **76% of respondents reported that music improves their mental health**.
* Approximately **22% reported no change**.
* Approximately **2% reported that music made their mental health worse**.

These are **self-reported survey responses** and should not be interpreted as clinical measurements or evidence that music causes improved mental health.

---

## 📊 Statistical Interpretation

A major focus of this project was distinguishing between **association and causation**.

For example:

> A statistical association between music listening and a mental health measure does not demonstrate that music caused the observed mental health outcome.

Several factors could influence the observed relationships, including:

* Age
* Occupation
* Personal preferences
* Existing mental health conditions
* Listening habits
* Other demographic characteristics

Therefore, the results are interpreted as **observed associations within the survey dataset**.

---

## 🧠 Statistical Concepts Demonstrated

This project provided practical experience with:

* Exploratory Data Analysis
* Descriptive statistics
* Categorical data analysis
* Chi-square hypothesis testing
* One-way ANOVA
* Post-hoc testing
* Statistical significance
* Group comparisons
* Data visualization
* Survey-data interpretation
* Association vs causation

---

## ⚠️ Limitations

Several limitations should be considered when interpreting the results:

1. **Self-reported data**
   Mental health and music preferences were reported by respondents and may contain reporting or recall bias.

2. **Sample size and representativeness**
   The dataset contains 610 respondents and may not represent the broader population.

3. **Observational data**
   The analysis identifies associations rather than causal relationships.

4. **Potential confounding variables**
   Other demographic and behavioral factors may influence the observed relationships.

5. **Mental health measures**
   The dataset contains self-reported indicators rather than clinical diagnoses.

---

## 📁 Repository Contents

```text
music-mental-health-analysis/
│
├── Music_Mental_Health_Analysis.pdf
└── README.md
```

The PDF contains the detailed project analysis, visualizations, statistical tests, and findings.

---

## 🚀 Future Improvements

Possible extensions of this project include:

* Build a reproducible Python analysis notebook.
* Perform deeper subgroup analysis by age and occupation.
* Investigate relationships between listening duration and mental health scores.
* Apply correlation and regression analysis where statistically appropriate.
* Explore multivariate relationships between music preferences and mental health variables.
* Add confidence intervals and effect sizes alongside hypothesis-test results.
* Develop an interactive Power BI dashboard.
* Improve reproducibility by adding a requirements file and structured source code.

---

## 💡 What I Learned

This project strengthened my practical understanding of how statistical methods can be applied to real-world survey data.

In particular, it helped me practice:

* Translating questions into statistical hypotheses
* Selecting appropriate statistical tests
* Interpreting p-values and group differences
* Using post-hoc tests after ANOVA
* Communicating statistical findings through visualization
* Distinguishing statistical association from causation
* Communicating limitations when working with observational data

---

## 👩‍💻 Author

**Navya Kamath**

M.Sc. in Statistics

---

## 📌 Disclaimer

This project is an academic exploratory analysis of publicly available survey data. The findings represent patterns observed in the dataset and should not be interpreted as clinical conclusions or causal evidence regarding music and mental health.
