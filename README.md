# 🛳️ Titanic Data Exploration and Visualization

This project explores the **Titanic dataset** — a classic dataset that contains demographic and travel information of passengers aboard the RMS Titanic.  
Using **Python, pandas, seaborn, and matplotlib**, the notebook performs **data cleaning, visualization, and pattern discovery** to understand the factors influencing passenger survival.

---

## 🚀 Features

### 🧩 Data Loading  
- Imported the Titanic dataset directly from **Seaborn’s built-in collection**.

### 🧼 Data Cleaning  
- Filled missing numerical values (like `age`) with the **median**.  
- Filled categorical values (like `embarked`) with the **mode**.  
- Dropped highly incomplete columns (`deck`).

### 📊 Data Visualization  
- **Histograms** for numerical features such as `age`, `fare`, `sibsp`, and `parch`.  
- **Bar plots** for categorical variables like `sex`, `pclass`, `embarked`, and `survived`.  
- **Boxplot** comparing `fare` distributions between survivors and non-survivors.  
- **Grouped bar chart** showing survival rates across passenger classes.

---

## 💡 Insights

- Most passengers were **young adults (20–40 years old)**.  
- **Higher fares** corresponded to **higher survival chances**.  
- **First-class** passengers had the **highest** survival rate, while **third-class** had the **lowest**.  
- Although there were **more male passengers**, **females had a better chance of survival**.

---

## 🧰 Tech Stack

- **Python 3.11+**  
- **pandas** — data manipulation  
- **matplotlib** — plotting and visualization  
- **seaborn** — dataset loading and styling  

---

## ⚙️ How to Run

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/<your-username>/<repo-name>.git](https://github.com/MaafiaTroodon/titanic-survival-analysis.git)
   cd titanic-survival-analysis
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python -m venv .venv
   .venv\Scripts\activate   # On Windows
   source .venv/bin/activate  # On macOS/Linux
   ```

3. **Install dependencies:**
   ```bash
   pip install pandas seaborn matplotlib
   ```

4. **Open the notebook:**
   ```bash
   jupyter notebook Malhar_Mahajan_B00934337_A1.ipynb
   ```

5. **Run all cells** to reproduce the analysis and visualizations.

---

## 📈 Example Outputs

- 📉 Histograms for numeric features  
- 📊 Bar charts for categorical variables  
- 📦 Boxplot comparing fare by survival  
- 🧮 Grouped bar chart showing survival by passenger class  

---

## 🧠 Key Takeaway

This project demonstrates core **data science skills** — from cleaning and preprocessing data to creating meaningful visualizations that reveal insights about real-world datasets.

---

## 🧑‍💻 Author

**Malhar Mahajan**  
📍 Data Exploration & Visualization Project  
🔗 Built using Python, pandas, matplotlib, and seaborn
