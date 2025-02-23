
# A/B Testing with Python – Analyzing Website Conversions

## Overview

This project applies A/B testing techniques using Python to analyze the performance of two versions of a website (Group A - Control, Group B - Treatment). The goal is to determine whether the new version improves conversion rates.

For a deeper understanding of A/B testing, check out my blog:

---

## Dataset  
The dataset used for this analysis is available on **Kaggle**:  [A/B Testing Dataset on Kaggle](https://www.kaggle.com/datasets/adarsh0806/ab-testing-practice)

This dataset includes:

User ID – Unique identifier for each user
Group – Control (A) or Treatment (B)
Page Views – Number of pages viewed per session
Time Spent – Time spent on the website (in seconds)
Conversion – Whether the user converted (Yes/No)
Device – Desktop or Mobile
Location – The user’s country

---

## What’s Inside?  
1. Data Preprocessing – Cleaning and encoding categorical variables.
2. Exploratory Data Analysis (EDA) – Visualizing conversion rates, time spent, and page views.
3. Hypothesis Testing – Running Chi-Square, Mann-Whitney U Test to determine statistical significance.
4. Business Insights & Recommendations – Interpreting findings to guide decision-making.

---
## Key Findings from A/B Testing

Group B (Treatment) had a significantly lower conversion rate than Group A.
Time Spent and Page Views showed no significant difference between the two groups.
Business Decision: The new version (Group B) underperformed, suggesting that changes to messaging, CTA, or design might have negatively impacted conversions.

<img width="1047" alt="Screenshot 2025-02-23 at 1 32 06 PM" src="https://github.com/user-attachments/assets/b47d0945-f0f2-429c-9d0c-2b672cd8ebff" />
<img width="701" alt="Screenshot 2025-02-23 at 1 33 10 PM" src="https://github.com/user-attachments/assets/98933fbf-40b0-492e-9533-9401a63eb35f" />

---
## Technologies Used

Python (Pandas, NumPy, Seaborn, SciPy, Matplotlib)
Jupyter Notebook
Statistical Analysis (Chi-Square Test, Mann-Whitney U Test)
A/B Testing Best Practices

---



## 🛠 How to Run the Code  
1. **Clone the Repository**  
   ```bash
   git clone https://github.com/Sri-Amirdha-Sudha/AB-Testing-Python.git
   cd AB_Testing_Python
   ```
2.  **Set Up a Virtual Environment (Optional but Recommended)**
   ```bash
   python -m venv env
   source env/bin/activate  # For Mac/Linux
   env\Scripts\activate     # For Windows
 ```
3.  **Set Up a Virtual Environment (Optional but Recommended)**
   ```bash
    jupyter notebook AB_Testing.ipynb
   ```

---

### Contact & Contributions

If you have any feedback or would like to contribute, feel free to:
- Open an issue on GitHub
- Suggest improvements via GitHub Discussions

