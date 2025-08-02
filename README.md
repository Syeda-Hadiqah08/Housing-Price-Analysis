# **🏠 Housing Prices Analysis Project**

This repository contains an Exploratory Data Analysis (EDA) project on a housing prices dataset from Kaggle. The aim is to uncover meaningful insights about property pricing patterns, area distributions, and furnishing effects using Python libraries like Pandas, Seaborn, and Matplotlib.

---

## **📁 Dataset Source**

- **Kaggle Dataset**: [Housing Prices Dataset](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset)
- Contains columns like: `price`, `area`, `bedrooms`, `furnishingstatus`, and proximity to roads.

---

## **🔧 Technologies Used**

- 🐍 Python 3
- 📊 Pandas
- 📈 Seaborn
- 🎨 Matplotlib

---

## **📝 Project Tasks**

**✅ Part 1: Load the Data**
- Imported the dataset from a `.csv` file using `pandas.read_csv()`.

**✅ Part 2: Data Exploration & Cleaning**
- Used `.head()`, `.describe()`, `.isnull().sum()`, and `.duplicated()` to explore the structure and clean the data.
- Removed null values and checked for duplicates.

**✅ Part 3: Descriptive Statistics*
- Computed statistical measures like:
  - Mean, Median, Mode
  - Variance, Standard Deviation
  - Skewness & Kurtosis
  - Minimum & Maximum

**✅ Part 4: Data Visualization**
- Created:
  - 📊 Histograms for Area and Price (with KDE curves)
  - 📦 Boxplots to detect outliers and spread
  - 🔍 Scatter plot for `Price VS Area`, colored by `Furnishing Status`

**✅ Part 5: Storytelling**
- A concise, data-driven narrative was written summarizing key insights:
  - Outliers and spread in housing prices
  - Effect of furnishing on pricing
  - Market inconsistency due to varied housing sizes and features

---

## **📌 Key Insights**

- Prices and areas are **right-skewed** with notable outliers.
- **Furnishing status** plays a visible role in house pricing.
- There's a positive correlation between **area and price**, but it's not strictly linear.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/HousingPrices-EDA.git
   cd HousingPrices-EDA

2. Launch Jupyter Notebook:
   ```bash
    jupyter notebook

3. Open **SyedaHadiqahFatima_HousingAnalysis.ipynb** and run the cells.

---

## **🙋‍♀️ Author**

**Syeda Hadiqah Fatima**  
*Data Analyst*  
**Email:** hadiqah.fatima02@gmail.com  
**LinkedIn:** https://www.linkedin.com/in/s-hadiqah-f/

---

## **📜 License**  
This project is licensed under the MIT License.

---

## **🌟 Acknowledgment**  
Thanks to Kaggle for providing the dataset that made this project possible!
