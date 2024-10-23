# Sales Data Analysis
A comprehensive data analysis project focusing on sales data exploration, cleaning, and statistical analysis. The project includes key insights into sales trends, customer behavior, product categories, delivery times, and seasonality effects. Advanced statistical tests and visualizations are employed to identify significant relationships and make data-driven decisions.
## 📝 Project Overview
In this project, I have analyzed a comprehensive sales dataset to uncover key insights and trends. The analysis is divided into the following steps:
1. **Data Exploration** – Initial examination of the dataset to understand its structure.
2. **Data Cleaning** – Handling missing values, outliers, and correcting data types.
3. **Feature Engineering** – Creating new features like delivery time and customer segments.
4. **Exploratory Data Analysis (EDA)** – Visualizing data to identify trends and patterns.
5. **Time Series Analysis** - Analysing Time Series Components, Trend, Seasonailty, Residue etc
6. **Time Series Forecasting** - Forecasting Sales for next quarter
7. **Hypothesis Testing** – Conducting statistical tests to validate hypothesis.

### Key Insights:
- Products priced between $10 and $1000 are sold more frequently, while higher-priced products have fewer buyers.
- Standard shipping mode (3-7 days) is preferred by most customers, contributing significantly to revenue.
- California and New York lead in sales, with cities like New York, Los Angeles, and San Francisco showing the highest sales.
- There is no significant correlation between delivery time and sales, but clustering around 4-day delivery is observed.
- Technology products, especially phones are most profitable.

## 📊 Data Visualizations
- Sales distribution of sales by product category and sub-category.
- Analysis of delivery times across various regions and customer segments.
- Correlation heatmaps to uncover relationships between key variables.
- Categorical charts for ship modes, regions, states, segment etc
- Time Series analysis plots
- SARIMA Model evaluation graphs

## 🔍 Statistical Tests
- **One-way ANOVA:** Tested sales differences across product categories.
- **Two-sample t-test:** Compared sales between long-term and new customers.

## 🛠 Technologies Used
- **Python**: Core programming language used for the analysis.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical operations.
- **Matplotlib**: Data visualization.
- **Seaborn**: Enhanced data visualizations.
- **Plotly**: Ingeractive data visualizations.
- **Scipy**: Statistical hypothesis testing.
- **Others**: Some other useful utility libraries.

## 📁 Project Structure
```bash
Sales-Data-Analysis/
├── data/
│   └── sales_data.csv, header.png
├── notebooks/
│   └── sales_data_analysis.ipynb  
└── README.md                  
```

## ⚙️ How to Run the Project
1. Clone the repository:
```
git clone https://github.com/ahmadrazacdx/Sales-Data-Analysis.git
```
2. Install the required dependencies:
```
pip install -r requirements.txt
```
3. Open the Jupyter notebook and run the cells:
```
jupyter notebook notebooks/sales_data_analysis.ipynb
```
## 📌 Key Recommendations
- Focus on Technology and Furniture categories to boost sales, as these are highly profitable.
- Optimize delivery times for cities like New York, California, and Washington, which have longer delivery periods.
- Promote Standard Class shipping mode, as it contributes significantly to revenue.
- Target consumers in high-sales cities (New York, Los Angeles, San Francisco) with customized offers and promotions.
- Improve the performance of high-price products by offering discounts or bundles to increase their purchase rate.
## 📧 Contact
If you have any questions or suggestions, feel free to contact me at: [ahmadrazacdx@gmail.com]
