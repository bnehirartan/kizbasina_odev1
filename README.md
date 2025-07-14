# 🛳️ Titanic Dataset Analysis – Assignment 1

This project explores the Titanic dataset to extract key insights about passenger survival, demographics, and ticket fares. It was completed as part of the KızBaşına: Data Science Training assignment using Python and Pandas in Google Colab.

---

## 📁 Dataset Source

- Kaggle Titanic Competition: [https://www.kaggle.com/c/titanic/data](https://www.kaggle.com/c/titanic/data)
- File path used in Colab:  
  `'/content/drive/My Drive/Colab Notebooks/KızBasına_Odevler/odev1/Titanic_dataset.csv'`

---


## Dataset Overview

- Rows: `891`
- Columns: `12`
- Key Features:
  - `Survived`: Survival (0 = No, 1 = Yes)
  - `Pclass`: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd)
  - `Sex`, `Age`, `Fare`, `Embarked`, etc.

---

## Questions Answered

1. **What was the average age of passengers who died?**
   - 📌 **Result:** ~30.63 years

2. **What was the average and median fare of passengers who died?**
   - 📌 **Average:** $22.12  
   - 📌 **Median:** $10.50  
   - 🧯 *Most paid lower fares; high-paying passengers were rare outliers.*

3. **What was the average age of deceased males?**
   - 📌 **Result:** ~31.62 years

4. **What was the average age of deceased females?**
   - 📌 **Result:** ~25.05 years  
   - 📊 *Females who died were younger on average than males.*

5. **What was the average age of survivors?**
   - 📌 **Result:** ~28.34 years

6. **What was the average fare of survivors?**
   - 📌 **Result:** $48.40  
   - 💡 *Higher fare → greater likelihood of survival*

7. **How many people survived?**
   - 📌 **Total survivors:** 342

8. **What was the median fare of children under 10?**
   - 📌 **Result:** $27.00

9. **How do fares vary by passenger class (1st, 2nd, 3rd)?**
   - 📈 **Mean & Median Fares:**
     | Class | Mean ($) | Median ($) |
     |-------|----------|-------------|
     | 1st   | 84.15    | 60.29       |
     | 2nd   | 20.66    | 14.25       |
     | 3rd   | 13.68    | 8.05        |
   - ✳️ *Clear correlation between fare and class.*

10. **Compare death rates between men and women.**
    - 🧔 **Men:** 81.1% death rate  
    - 👩 **Women:** 25.8% death rate  
    - 📌 *Women had a significantly higher chance of survival.*

---

## Visualizations Included

- Histogram of fare distribution for deceased passengers
- Bar plot: Average age of deceased males vs females
- Boxplot: Fare comparison between survivors and deceased
- Bar plot: Death ratio by gender
- Bar chart: Mean & median fare by class

---

## Conclusion

This notebook demonstrates how exploratory data analysis (EDA) using Pandas and Seaborn can provide meaningful insights into a tragic historical dataset. The results highlight:

- The strong impact of gender and class on survival
- Younger females in higher classes had better chances
- Most passengers who died paid significantly lower fares

---

## How to Run

1. Open [Google Colab](https://colab.research.google.com/)
2. Mount your Google Drive
3. Load the dataset from your path
4. Run all cells in order

---

## Author

Basak Nehir – [KızBaşına Data Science Participant]  
_This project was completed as part of the assignment for the Titanic dataset analysis module._

