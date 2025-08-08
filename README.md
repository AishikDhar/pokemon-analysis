# Pokémon Data Analysis 🧬

This project explores and analyzes the Pokémon dataset using **Python** and **Pandas**, focusing on data cleaning, exploratory data analysis (EDA), and visualization.

---

## 📁 Dataset

The dataset used is [`Pokemon.csv`](Pokemon.csv), which contains stats for various Pokémon including:
- Name, Type 1, Type 2
- HP, Attack, Defense, Speed
- Generation and Legendary status

---

## ✅ Tasks Completed

### 🧹 1. Data Cleaning
- Checked for missing values in all columns
- Replaced missing `Type 2` with `"None"` to represent single-type Pokémon clearly
- Removed duplicate Pokémon based on their names or total stats
- Identified outliers in numeric columns like HP and Speed using the IQR method

### 📊 2. Exploratory Data Analysis (EDA)
- Found the **top 5 most common Type 1 Pokémon**
- Calculated the **average Attack, Defense, and Speed per generation**
- Identified Pokémon with the **highest Total stats**
- Compared **Legendary vs Non-Legendary** stat averages
- Plotted a **correlation heatmap** for all numerical features

---

## 📈 Tools & Libraries
- Python 3
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook / VS Code

---

## 📌 How to Run

```bash
pip install pandas matplotlib seaborn
