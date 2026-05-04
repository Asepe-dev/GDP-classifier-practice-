# GDP Classifier Practice

## 📌 Overview
This project demonstrates a complete data analysis workflow using real-world economic data from the World Bank. It focuses on Gross Domestic Product (GDP) trends across selected African countries and prepares the foundation for future classification or machine learning tasks.

The notebook is implemented in Google Colab using Python and standard data science libraries.

---

## 🎯 Objectives
- Acquire a real dataset from a trusted global source  
- Perform exploratory data analysis (EDA)  
- Clean and preprocess raw data  
- Visualize economic patterns and trends  
- Build intuition for future GDP classification tasks  

---

## 🌍 Dataset Source
- Provider: World Bank  
- Dataset: Global GDP dataset (filtered for African countries)  
- Format: CSV  

Link:  
https://raw.githubusercontent.com/datasets/gdp/master/data/gdp.csv  

---

## 🛠️ Tech Stack
- Python  
- Google Colab  
- Pandas  
- Matplotlib  
- Seaborn  

---

## 🔍 Exploratory Data Analysis
Initial inspection of the dataset includes:

- `df.shape` → dataset dimensions  
- `df.info()` → data types and missing values  
- `df.describe()` → statistical summary  

---

## 🧹 Data Preprocessing
Key cleaning steps:

- Handle missing values:
  - Drop null rows using `dropna()`  
  - Fill missing GDP values using mean  

- Fix data types:
  - Convert GDP (`Value`) column to numeric  

- Remove duplicates:
  - Use `drop_duplicates()`  

- Filter dataset:
  - Focus on selected African countries  

---

## 📊 Visualizations
The following plots were created:

1. **Histogram** – Distribution of GDP values  
2. **Scatter Plot** – GDP trends over time  
3. **Bar Chart** – GDP comparison (latest year)  
4. **Box Plot** – Outliers and spread  
5. **Correlation Heatmap** – Relationships between countries  

---

## 📈 Insights
- GDP distribution is uneven across countries  
- A few countries dominate economically  
- Growth trends vary significantly  
- Some countries show strong correlations in GDP movement  

---

## 🚀 How to Run

1. Open Google Colab  
2. Create a new notebook  
3. Paste the project code  
4. Run all cells step-by-step  

Make sure you have an active internet connection to load the dataset.

---

## 🔮 Next Steps
- Convert GDP into categories (Low, Medium, High)  
- Train a classification model  
- Add more features (population, inflation, etc.)  
- Build an interactive dashboard  

---

## 👤 Author
** Abolade Asepeniseoluwa **  

---

## 📄 License
This project is for educational purposes only.
