# Drug, Side Effects & Medical Conditions Analysis

This project analyzes relationships between drugs, their associated side effects, medical conditions, and user ratings using Python and Tableau.

---

## Objective

To perform data analytics on a drug dataset and extract insights for:
- Most common drug classes and medical conditions
- Frequent and severe side effects
- User review ratings and correlations
- Alcohol & pregnancy safety classifications

---

## Tools & Technologies
- Python (Pandas, NumPy, Seaborn, Matplotlib)
- VS Code Notebook
- Tableau Public (Interactive Dashboard)
- GitHub

---

## Dataset Details

| Feature                | Description                                         |
|------------------------|-----------------------------------------------------|
| drug_name              | Name of the drug                                    |
| medical_condition      | Condition treated by the drug                       |
| side_effects           | Reported side effects                               |
| rating                 | Average user rating (1–10)                          |
| no_of_reviews          | Number of user reviews                              |
| pregnancy_category     | Risk category for pregnant users (A, B, C, D, X, N) |
| csa                    | Controlled Substance Act schedule                   |
| rx_otc                 | Prescription or over-the-counter                    |
| alcohol                | Interaction with alcohol                            |

---

## Exploratory Data Analysis

- Distribution of drug ratings
- Top conditions treated by drugs
- Most reported(common) side effects
- Ratings grouped by drug classes
- Heatmap for Correlation

---

## Tableau Dashboard

An interactive dashboard visualizing:
- Drug frequency by condition
- Side Effects Frequency
- Drug Class vs Ratings
- Pie chart of pregnancy category

🔗 [https://public.tableau.com/app/profile/harshita.lalawat/viz/Drugs_Side_Effects/Dashboard1?publish=yes]

---

## Key Insights

- Most treated: Pain, Cold & Flu, Acne
- Common side effects: Hives, Itching, Breathing difficulty
- Top-rated drugs: Found in topical classes

---

## Future Enhancements

- ML model to predict drug rating
- Side effect severity classification
- Deployment via Flask/Django
- Real-time API for new drug entries

---

## Developed By
**Harshita Lalawat**
