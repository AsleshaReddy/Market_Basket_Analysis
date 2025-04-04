# 🛒 Market Basket Analysis using Apriori, ECLAT & FP-Growth

This project explores Market Basket Analysis (MBA) using three major algorithms: **Apriori**, **ECLAT**, and **FP-Growth** to identify frequently purchased itemsets and generate association rules for personalized marketing and business insights.

---

## 📂 Files Included

- `MIS637A-final_project.ipynb` – Implementation of Apriori, ECLAT & FP-Growth in Python
- `MIS637A-Database of final project.xlsx` – Dataset used (from OyeHappy e-commerce store)
- `MIS637-A-Final Project Report.docx` – Full academic report
- `MIS637-A-Market Basket Analysis.pptx` – Presentation slides

---

## 🧠 Algorithms Used

- ✅ Apriori (using `mlxtend`)
- ✅ ECLAT (custom implementation)
- ❌ FP-Growth (no frequent items found)

---

## 📊 Tools & Libraries

- Python
- Pandas, NumPy, Matplotlib, Seaborn
- mlxtend.frequent_patterns
- fpgrowth_py (optional)

---

## 🔍 Key Insights

- Association rules help retail stores plan **product placement**
- The **Apriori algorithm** gave the best support-confidence results
- ECLAT showed strong flexibility with varying support values
- FP-Growth did not yield any meaningful frequent itemsets in this case

---

## 🏁 How to Run

1. Open the Jupyter Notebook (`.ipynb`)
2. Make sure all required libraries are installed:
```bash
pip install pandas numpy matplotlib seaborn mlxtend fpgrowth_py

```
```
