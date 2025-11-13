# Mental Health & Lifestyle Analysis

**Author:** Daya  
**Project Type:** Exploratory Data Analysis (EDA)  
**Dataset:** [Mental Health and Lifestyle Habits 2019-2024](https://www.kaggle.com/datasets/atharvasoundankar/mental-health-and-lifestyle-habits-2019-2024)

---

## Project Overview
This project explores the relationship between lifestyle factors — including **exercise levels, diet types, sleep, screen time, and social interaction** — and **mental health outcomes** such as happiness and stress.  

The goal is to uncover **subtle but meaningful patterns** that highlight how lifestyle choices may impact mental well-being.

---

## Key Libraries
- `pandas` for data manipulation  
- `matplotlib` and `seaborn` for data visualization  

---

## Data Cleaning & Validation
Before analysis, the dataset was carefully validated to ensure reliability:  
- **Missing values:** None  
- **Duplicates:** Removed  
- **Data types:** Correct for all columns (categorical vs numerical)  
- **Outliers checks:** Verified ranges and distributions of key columns  

This ensures the insights generated are trustworthy and accurate.

---

## Exploratory Analysis & Visualizations

### 1) Average Happiness by Exercise Level
- Higher exercise levels are associated with **higher happiness scores**.  
- Even moderate exercise shows a noticeable positive effect compared to low exercise.  
- **Visualization:** Bar chart of average happiness per exercise level.

### 2)  Stress Level Distribution by Diet Type
- Diet type has a **subtle effect on stress**:  
  - Plant-based diets (Vegetarian, Vegan) tend to have more participants reporting **low stress**.  
  - Junk food diet shows slightly higher proportions in **high stress**, though exercise mitigates this.  
- **Visualization:** Stacked bar chart of stress levels by diet type.

### 3)  Combined Exercise & Diet vs Happiness (Highlight Chart)
- High exercise consistently correlates with higher happiness, **regardless of diet**.  
- **Peak Happiness:** Vegetarian diet + High exercise = **5.68** (highest overall).  
- Interesting observations:  
  - Balanced diet shows largest disparity between High and Low exercise groups.  
  - High exercise + Junk Food diet can be happier than Low exercise + Keto diet — highlighting the **dominant effect of exercise**.  
- **Visualization:** Grouped bar chart showing happiness by exercise and diet type.

---

## Summary of Insights
1. **Exercise Dominates:** Exercise level is a stronger predictor of happiness than diet type.  
2. **Diet Matters Subtly:** Vegetarian diets show consistently high happiness scores; balanced diets show largest variance.  
3. **Lifestyle Impact:** Combining exercise and mindful diet choices is associated with higher happiness and potentially lower stress.  
4. **Key Stats:**  

| Rank | Diet Type   | Exercise Level | Avg Happiness Score |
|------|------------|----------------|------------------|
| 1    | Vegetarian | High           | 5.68              |
| 2    | Junk Food  | High           | 5.60              |
| 3    | Keto       | High           | 5.58              |
| 4    | Junk Food  | Moderate       | 5.57              |
| 5    | Balanced   | High           | 5.53              |

---


