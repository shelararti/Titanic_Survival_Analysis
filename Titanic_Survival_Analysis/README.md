# 🚢 Titanic Survival Analysis

This project explores the famous Titanic dataset to uncover patterns in passenger survival using data analysis and hypothesis testing techniques.

## 📌 Objective

To investigate whether factors such as passenger class, gender, age, and family presence onboard influenced survival odds during the Titanic disaster.

---

## 🔍 Key Questions Explored

1. Does a passenger’s class (`Pclass`) affect their chance of survival?
2. Did gender or age play a role in survival rates?
3. Did having family onboard (`SibSp`, `Parch`) help increase survival odds?

---

## 🧪 Hypotheses Tested

### 1. Effect of Passenger Class
- **H₀:** Passenger class has no effect on survival.
- **H₁:** Passenger class affects survival.

✅ **Test used:** Chi-Square Test of Independence

---

### 2. Gender and Age Influence
- **H₀ (Gender):** Gender does not affect survival.
- **H₁ (Gender):** Gender affects survival.

✅ **Test used:** Chi-Square Test

- **H₀ (Age):** Age does not affect survival.
- **H₁ (Age):** Age affects survival.

✅ **Test used:** Independent t-test (or Mann-Whitney U if non-normal)

---

### 3. Family Onboard
- **H₀ (SibSp):** Number of siblings/spouses does not affect survival.
- **H₁ (SibSp):** Number of siblings/spouses affects survival.

- **H₀ (Parch):** Number of parents/children does not affect survival.
- **H₁ (Parch):** Number of parents/children affects survival.

✅ **Test used:** Mann-Whitney U test and visual analysis

---

## 📊 Tools and Libraries

- **Python**
- **Pandas** – Data manipulation
- **Matplotlib & Seaborn** – Visualization
- **SciPy** – Statistical testing
- **Jupyter Notebook**

---

## 📈 Key Insights

- 1st class passengers had significantly higher survival rates.
- Female passengers were much more likely to survive.
- Younger passengers had slightly better odds, though age wasn’t the strongest predictor.
- Moderate family presence improved survival; too many family members reduced chances.

---

## 📁 Files

- `Main.ipynb`: Full analysis notebook
- `README.md`: Project overview and documentation

---

## 🚀 How to Run

1. Clone this repository or download the files.
2. Open `Main.ipynb` in Jupyter Notebook.
3. Make sure `train.csv` (Titanic dataset) is present in the same directory.
4. Run the cells step-by-step to see the analysis.

---

## ✅ Dataset Source

- [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)

---

## 📬 Contact

Feel free to reach out if you have ideas or feedback!

---

