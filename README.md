# 🍽️ Zomato Restaurant Data Analysis - EDA

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?logo=pandas)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow?logo=powerbi)

## 📌 Project Overview

Exploratory Data Analysis (EDA) on Zomato restaurant dataset to uncover key business insights about restaurant ratings, online ordering trends, pricing, and restaurant types.

---

## 📂 Project Structure

```
Zomato-EDA/
│
├── Zomato_EDA.ipynb        # Main Jupyter Notebook (EDA)
├── Zomato-data-.csv        # Dataset
├── Zomato_Dashboard.pbix   # Power BI Dashboard
├── images/                 # Dashboard screenshots
│   └── dashboard.png
└── README.md
```

---

## 📊 Dataset Info

| Feature | Description |
|---|---|
| `name` | Restaurant name |
| `online_order` | Online ordering available (Yes/No) |
| `book_table` | Table booking available (Yes/No) |
| `rate` | Restaurant rating (out of 5) |
| `votes` | Number of votes |
| `cost_for_two` | Approximate cost for two people (₹) |
| `listed_in(type)` | Restaurant type (Dining/Buffet/Cafes/other) |

- **Total Records:** 148 restaurants
- **Source:** Kaggle - Zomato Restaurants Dataset

---

## 🔍 Key Insights

1. **Online Ordering** – Majority of restaurants offer online ordering
2. **Table Booking** – Very few restaurants support table booking
3. **Average Rating** – Most restaurants are rated between **3.5 – 4.2 / 5**
4. **Cost** – Average cost for two is around **₹300–500**
5. **Restaurant Types** – Dining is most common, followed by Cafes
6. **Online Order vs Rating** – Restaurants with online ordering tend to be rated slightly higher
7. **Correlation** – More votes = higher ratings (popular restaurants perform better)

---

## 📈 Visualizations

- Rating Distribution (Histogram + Boxplot)
- Online Order & Table Booking breakdown
- Cost for Two Distribution
- Restaurant Type Analysis
- Rating by Restaurant Type
- Correlation Heatmap

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|---|---|
| Python 3 | Core language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib & Seaborn | Data visualization |
| Jupyter Notebook | EDA environment |
| Power BI | Interactive dashboard |

---

## 🚀 How to Run

1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/Zomato-EDA.git
cd Zomato-EDA
```

2. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Launch Jupyter Notebook
```bash
jupyter notebook Zomato_EDA.ipynb
```

## 📊 Power BI Dashboard Preview
![Dashboard](dashboard.png)


## 👤 Author

**Nakul**  
Data Analyst Intern | Python • SQL • Power BI • Tableau  
[LinkedIn](https://linkedin.com/in/YOUR_PROFILE) | [GitHub](https://github.com/YOUR_USERNAME)
