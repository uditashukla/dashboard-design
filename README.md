# dashboard-design


## 🚀 Overview
This interactive Power BI dashboard provides insights into **sales performance**, **forecast accuracy**, and the **impact of economic indicators** such as GDP growth, inflation, and unemployment rate. It is designed to help business stakeholders track KPIs, analyze trends over time, and make data-driven decisions.

---

## 📁 Dataset
- **Source**: Simulated Financial Forecasting Data  
- **Fields Used**:
  - `sales`, `target_sales`, `Absolute Error`, `Forecast Accuracy`
  - `gdp_growth`, `inflation_rate`, `unemployment_rate`
  - `market_indicator_1`, `market_indicator_2`
  - `Time_index` (used as a proxy for time series)

---

## 🧩 Pages in the Dashboard

### 1. 📊 Performance Trends
- **Key KPIs**: Total Sales, Forecast Accuracy, Average GDP Growth
- **Visuals**:
  - Sales over time
  - GDP growth vs Sales
  - Actual vs Target Sales
  - Market Indicator Bubble Chart
- **Features**:
  - Slicers for economic indicators
  - Cards for totals
  - Clean, dark theme with consistent layout

### 2. 📈 Forecast Accuracy
- **Visuals**:
  - Line chart: Sales vs Target Sales over time
  - Absolute Error trend
  - Forecast Accuracy % card
- **Filters**:
  - Slicers for GDP, Market Indicators, and Unemployment

---

## 🎯 Key Features
- **Interactive Filters**: Dropdown slicers allow dynamic exploration
- **Time-Series Analysis**: Trends shown using `Time_index`
- **Forecasting Accuracy**: Absolute error and accuracy metrics visualized
- **Clean UI**: Cards, slicers, consistent theme and layout

---

## 🛠 Tools Used
- **Power BI Desktop**
- Custom measures and fields added in Power BI
- Visual types: Line, Column, Scatter, Cards, Slicers

---

## 📤 Deliverables
- Power BI (.pbix) dashboard file
- PowerPoint summary (.pptx)
- README file (this document)

---

## 📌 How to Use
1. Open the `.pbix` file in Power BI Desktop.
2. Navigate through the report tabs:
   - **Performance Trends**
   - **Forecast Accuracy**
3. Use slicers to explore the data based on economic variables.

---

