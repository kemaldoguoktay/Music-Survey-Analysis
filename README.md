# Music Preferences and Social Interaction Analysis

This repository contains the complete implementation and analysis of a term project conducted for the course **STAT365 - Sampling and Survey Techniques** at Middle East Technical University (METU). The project explores the intricate relationship between music preferences, listening habits, and social interactions among METU students.

---

## Table of Contents

1. [Introduction](#introduction)
2. [Survey Design and Objectives](#survey-design-and-objectives)
3. [Data Collection and Sampling Strategy](#data-collection-and-sampling-strategy)
4. [Analysis and Findings](#analysis-and-findings)
5. [Methodology](#methodology)
6. [Results](#results)
7. [How to Use This Repository](#how-to-use-this-repository)
8. [Dependencies](#dependencies)
9. [Acknowledgments](#acknowledgments)
10. [License](#license)

---

## Introduction

Music is a universal language that plays a pivotal role in emotional regulation, social bonding, and cultural identity. This project investigates how music preferences influence social interactions among METU students, focusing on patterns in listening habits and their correlations with interpersonal connections.

The primary goal is to offer actionable insights into the role of music in shaping social behaviors and personal expression.

---

## Survey Design and Objectives

The survey used in this project was designed using Google Forms and aimed to collect detailed data about students’ music preferences and related social behaviors. Key objectives of the survey include:

1. Understanding the listening habits of METU students.
2. Analyzing the connection between music preferences and socialization.
3. Exploring the role of significant life events in shaping music preferences.
4. Assessing how discussions about music impact social engagement.
5. Evaluating the importance of lyrics in music enjoyment.

---

## Data Collection and Sampling Strategy

The data collection process followed a **stratified sampling approach** to ensure diverse representation across gender, academic years, and departments. Surveys were conducted in high-traffic locations such as:

- **Çatı Café**
- **Library**
- **Physics Department Cafeteria**

### Observations During Data Collection

1. **High Engagement**: Locations with social settings (cafeterias, libraries) resulted in higher participation rates.
2. **Balanced Representation**: Efforts were made to achieve gender diversity and include students from various academic years.
3. **Language Barriers**: English-only surveys posed challenges for some participants.

---

## Analysis and Findings

Statistical and visual analysis tools were used to uncover meaningful patterns. Specifically, Python libraries such as Pandas, Matplotlib, Seaborn, and Scikit-learn were utilized for data preprocessing, visualization, and statistical analysis. Key methodologies include:

### Hypotheses Tested

1. **Proportional Z-Test**: Examined if 50% of students exhibit the highest music listening frequency.
2. **ANOVA**: Analyzed the relationship between leisure time preferences and music listening frequency.
3. **Regression Analysis**: Investigated correlations between socialization scores and music discussion frequency.

### Key Findings

- **Music as a Social Catalyst**: Frequent discussions about music are strongly correlated with higher socialization scores.
- **Lyrics Matter**: A majority of students rate lyrics as moderately to very important in music.
- **Life Events Influence Preferences**: Academic transitions, personal relationships, and global events significantly impact listening habits.

---

## Methodology

### Sampling Strategy

- **Stratified Sampling**: Ensured gender and academic year diversity.
- **Cluster Sampling**: Diversified data collection locations for better representation.

### Statistical Tools

- **Proportional Z-Tests**
- **ANOVA**
- **Regression Analysis**

### Visualization Techniques

- Heatmaps
- Boxplots
- Word Clouds
- Line Graphs

---

## Results

### Quantitative Insights

1. **Music Listening Habits**:

   - Z-Test revealed significant deviations from the assumption that 50% of students listen to music at the highest frequency.

2. **Socialization and Music**:

   - Regression analysis confirmed a positive relationship between discussing music and socialization. The strength of this relationship was quantified using a linear regression model, which produced a statistically significant coefficient for music discussion frequency. For instance, an increase in the frequency of discussing music by one unit corresponded to an average increase in socialization scores by 0.8 units, as visualized in the regression plot with a narrow confidence interval.

3. **Life Events**:

   - Word cloud analysis highlighted key life events (e.g., university, relationships) shaping music preferences.

---

## How to Use This Repository

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Install the required dependencies (listed below).
3. Open the Jupyter Notebook `music_survey_analysis.ipynb` for detailed analysis.

---

## Dependencies

- Python 3.8+
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

Install dependencies using:

```bash
pip install -r requirements.txt
```

---

## Acknowledgments

This project was conducted as part of the STAT365 course. Special thanks to all participants who contributed their valuable time and insights.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

### Additional Information

- Survey form: [Google Form Link](https://forms.gle/Aw2sv9iZyE6XXw3j8)
- Full project report available in `365 last.pdf`.



