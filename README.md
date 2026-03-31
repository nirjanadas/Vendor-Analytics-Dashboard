# 🛒 Retail Vendor Performance Analysis

## 📌 Project Summary
This project delivers an end-to-end data analysis pipeline to evaluate vendor performance in a retail environment. It focuses on identifying profitability drivers, optimizing procurement decisions, and improving inventory efficiency using data-driven insights.

---

## 🎯 Business Problem
Retail companies often struggle with:
- Lack of visibility into vendor-wise profitability
- Inefficient procurement strategies leading to increased costs
- Overstocking or understocking due to poor inventory planning
- Over-reliance on a small subset of vendors

This project addresses these issues by analyzing vendor transactions, inventory flow, and pricing data.

---

## 🚀 Key Objectives
- Analyze vendor-wise sales, purchases, and profit contribution  
- Identify top-performing and underperforming vendors  
- Evaluate inventory turnover and stock efficiency  
- Detect pricing inefficiencies and cost leakages  
- Provide actionable recommendations for business optimization  

---

## 🧠 Approach & Methodology

### 1. Data Ingestion & Cleaning
- Imported multiple datasets (sales, purchases, inventory)
- Handled missing values and removed duplicates
- Standardized column formats for consistency

### 2. Data Transformation
- Aggregated vendor-level sales and purchase data
- Merged datasets to create a unified analytical view
- Engineered new features such as:
  - Profit = Sales − Purchase Cost  
  - Profit Margin (%)  
  - Inventory Turnover Ratio  

### 3. Analysis
- Vendor-wise performance evaluation
- Profitability and margin analysis
- Inventory efficiency assessment
- Identification of high-risk and high-opportunity vendors  

### 4. Visualization
- Bar charts for top vendors by profit  
- Distribution plots for profit margins  
- Interactive dashboard using Power BI  

---

## 🛠️ Tech Stack
- **Python (Pandas, NumPy)** → Data processing & analysis  
- **Matplotlib** → Visualization  
- **SQL (optional)** → Querying structured data  
- **Power BI** → Interactive dashboard  
- **Jupyter Notebook** → Exploratory Data Analysis  
- **Git & GitHub** → Version control  

---

## 📂 Project Structure
```
Retail-Vendor-Performance-Analysis/
│
├── data/ # Raw datasets
├── notebooks/ # EDA notebooks
├── scripts/ # Modular Python scripts
│ ├── data_processing.py
│ ├── analysis.py
│ └── visualization.py
├── outputs/ # Processed outputs
├── main.py # Pipeline entry point
├── requirements.txt
└── README.md
```
---

## 📊 Key Metrics Computed
- **Total Sales per Vendor**
- **Total Purchase Cost**
- **Profit (Revenue − Cost)**
- **Profit Margin (%)**
- **Inventory Turnover Ratio**

---

## 📈 Key Insights
- A small group of vendors contributes disproportionately to total revenue → **vendor dependency risk**
- Several vendors show high margins but low sales → **growth opportunity**
- Bulk purchasing significantly reduces per-unit cost → **procurement optimization**
- Low inventory turnover indicates **capital inefficiency and overstocking**

---

## 💡 Business Impact
- Enables data-driven vendor selection  
- Reduces procurement costs through optimized purchasing  
- Improves inventory planning and reduces wastage  
- Supports strategic decision-making with measurable insights  

---

## ⚙️ How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/nirjanadas/Retail-Vendor-Performance-Analysis.git
cd Retail-Vendor-Performance-Analysis
```
### 2. Install Dependencies
```bash
pip install -r requirements.txt
```
### 3. Execute the Pipeline
```bash
python main.py
```
### 4. View Outputs
-**Processed results stored in /outputs**
-**Visualizations displayed during execution**
-**Open Power BI dashboard (.pbix) for interactive insights**


```bash
git clone https://github.com/nirjanadas/Retail-Vendor-Performance-Analysis.git
cd Retail-Vendor-Performance-Analysis
