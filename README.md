# E-Commerce Sales and Profit Analysis Dashboard

## 📊 Project Overview

This project creates an interactive business sales dashboard using Power BI to analyze e-commerce sales data and identify key business insights. The dashboard provides comprehensive analysis of sales trends, product performance, and customer behavior patterns.

## 🎯 Objectives

- Identify best-selling products and revenue drivers
- Track sales trends and seasonal patterns
- Analyze category-wise revenue distribution
- Create interactive visualizations for business decision-making
- Present findings through an intuitive Power BI dashboard

## 📈 Dataset Information

**Dataset:** `cleaned_ecommerce_sales_data.csv`

**Key Statistics:**
- **Total Records:** 1,042,728 transactions
- **Total Revenue:** $20,814,292
- **Unique Products:** 5,469
- **Average Order Value:** $516.38
- **Date Range:** 2010-2011
- **Countries:** Multiple (UK primary market)

**Data Structure:**
```
Columns: Invoice, StockCode, Description, Quantity, InvoiceDate, Price, Customer ID, Country, Sales, InvoiceMonth, Hour, Date
Data Types: Mixed (object, int64, datetime)
Missing Values: 237,108 missing Customer IDs (23% of data)
```

## 🔍 Key Findings

### Top-Selling Products by Revenue
1. **REGENCY CAKESTAND 3 TIER** - $344,563.25
2. **Manual** - $341,104.90
3. **DOTCOM POSTAGE** - $322,657.48
4. **WHITE HANGING HEART T-LIGHT HOLDER** - $266,923.55
5. **PAPER CRAFT, LITTLE BIRDIE** - $168,469.60

### Revenue by Category
| Category | Revenue | Percentage |
|----------|---------|------------|
| Other | $14,647,790.03 | 70.4% |
| Bags & Accessories | $1,951,435.54 | 9.4% |
| Lighting & Candles | $1,730,737.94 | 8.3% |
| Kitchen & Dining | $1,086,431.83 | 5.2% |
| Christmas Items | $836,912.44 | 4.0% |
| Home Decoration | $417,019.51 | 2.0% |
| Gifts | $143,964.71 | 0.7% |

### Peak Sales Months
1. **November 2011** - $1,509,496.33
2. **November 2010** - $1,470,272.48
3. **December 2010** - $1,262,598.79
4. **October 2011** - $1,154,979.30
5. **October 2010** - $1,126,558.04

## 📊 Dashboard Visualizations

### 1. Sales Trend Analysis
- **Chart Type:** Line Chart
- **Purpose:** Track monthly sales performance and identify seasonal patterns
- **Key Insight:** Strong seasonality with November peaks

### 2. Top Products Performance
- **Chart Type:** Horizontal Bar Chart
- **Purpose:** Identify best-selling products by revenue
- **Key Insight:** Top 3 products contribute significantly to overall revenue

### 3. Category Revenue Distribution
- **Chart Type:** Pie Chart/Treemap
- **Purpose:** Analyze revenue distribution across product categories
- **Key Insight:** "Other" category dominates, suggesting need for better categorization

### 4. Interactive Filters
- **Date Range Slicer:** Filter by specific time periods
- **Country Filter:** Analyze performance by geographic region
- **Category Filter:** Focus on specific product categories
- **Product Search:** Quick access to individual product performance

## 🛠️ Technical Implementation

### Tools & Technologies
- **Data Analysis:** Python (Pandas, NumPy)
- **Visualization:** Matplotlib, Seaborn
- **Dashboard:** Microsoft Power BI
- **Data Processing:** Jupyter Notebook

### Data Processing Steps
1. **Data Cleaning:** Handle missing values and data type conversions
2. **Feature Engineering:** Create product categories and time-based features
3. **Aggregation:** Calculate key metrics and KPIs
4. **Visualization:** Generate charts and graphs for dashboard integration

### Key Metrics Calculated
- Total Revenue and Transaction Count
- Average Order Value (AOV)
- Monthly Sales Trends
- Product Performance Rankings
- Category-wise Revenue Analysis
- Customer Geographic Distribution

## 📋 Business Insights & Recommendations

### 🔑 Key Insights
- **Seasonality:** Strong seasonal patterns with Q4 peaks (October-December)
- **Product Concentration:** Top 10 products drive significant revenue
- **Category Opportunity:** "Other" category needs better classification
- **Geographic Focus:** UK market dominance with international presence

### 💡 Strategic Recommendations
1. **Inventory Management:** Increase stock for top-performing products during peak seasons
2. **Product Categorization:** Implement better classification system for "Other" category
3. **Seasonal Marketing:** Develop targeted campaigns for Q4 peak periods
4. **Customer Retention:** Focus on markets with missing customer data
5. **Product Development:** Analyze successful product characteristics for new launches

## 📁 Project Structure
```
├── data/
│   └── cleaned_ecommerce_sales_data.csv
├── notebooks/
│   └── sales_analysis.ipynb
├── dashboard/
│   └── sales_dashboard.pbix
├── visualizations/
│   ├── sales_trend.png
│   ├── top_products.png
│   └── category_distribution.png
└── README.md
```

## 🚀 How to Use

1. **Clone Repository:**
   ```bash
   git clone https://github.com/yourusername/ecommerce-sales-dashboard.git
   ```

2. **Install Dependencies:**
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. **Run Analysis:**
   ```bash
   jupyter notebook notebooks/sales_analysis.ipynb
   ```

4. **Open Dashboard:**
   - Open `dashboard/sales_dashboard.pbix` in Power BI Desktop
   - Refresh data connections if needed
   - Interact with visualizations and filters

## 📊 Dashboard Features

### Interactive Elements
- **Date Range Selector:** Filter data by specific time periods
- **Product Category Filter:** Focus on specific product categories
- **Country/Region Filter:** Analyze geographic performance
- **Search Functionality:** Quick product lookup
- **Drill-down Capabilities:** Detailed analysis at multiple levels

### Key Performance Indicators (KPIs)
- Total Revenue
- Number of Transactions
- Average Order Value
- Top Product Performance
- Monthly Growth Rate
- Category Performance Metrics

## 🔗 Links & Resources

- **LinkedIn Post:** [Project Showcase](https://www.linkedin.com/in/vasu-kilari-162576349/)
- **Dashboard Demo:** [Power BI Online](<img width="1470" height="754" alt="Screenshot 2025-08-05 100150" src="https://github.com/user-attachments/assets/3bf0ae70-0432-48d0-93a5-d18103fc16ae" />


Uploading Recording 2025-08-04 222326.mp4 va.mp4…


- **Data Source:** E-commerce Transaction Data (2010-2011)

## 👨‍💻 Author

**Your Name**
- LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/vasu-kilari-162576349/)
- Email: your.email@example.com

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Data source and business context providers
- Power BI community for dashboard inspiration
- Open source Python libraries for data analysis

---

*This project demonstrates end-to-end data analysis and business intelligence capabilities, from raw data processing to interactive dashboard creation.*
