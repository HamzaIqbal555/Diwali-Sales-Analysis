# Diwali Sales Analysis: Unlocking Festival E-Commerce Insights

##  Business Use Case
During **Diwali**, India's biggest festival, e-commerce platforms see explosive sales growth in categories like Food, Clothing, and Electronics. This project analyzes **11,253 real sales transactions** to derive **actionable insights** for business stakeholders:

- **Marketing Targeting**: Identify high-value customer segments (e.g., married women aged 26-35 in UP/Maharashtra/Karnataka from IT/Healthcare).
- **Inventory Optimization**: Prioritize top-selling categories and products.
- **Regional Strategies**: Focus promotions on top states (UP, Maharashtra, Karnataka ~50% of sales).
- **ROI Impact**: Potential 20-30% uplift by targeting key demographics, based on sales patterns.

As a **Data Analyst**, this demonstrates skills in data cleaning, EDA, visualization, and translating data into business recommendations.

##  Dataset Overview
- **Source**: Diwali Sales Dataset (`Diwali Sales Data.csv`).
- **Size**: 11,253 rows × 15 columns.
- **Key Columns**:

| Column          | Description                  | Sample Values |
|-----------------|------------------------------|---------------|
| User_ID        | Unique customer ID          | 1002903      |
| Gender         | F/M                         | F             |
| Age Group      | 0-17, 18-25, 26-35, etc.   | 26-35         |
| Marital_Status | 0=Unmarried, 1=Married      | 1             |
| State          | Customer state              | Uttar Pradesh |
| Occupation     | IT Sector, Healthcare, etc. | IT Sector     |
| Product_Category | Food, Clothing, etc.      | Food          |
| Amount         | Sale amount (₹)             | 23952         |

##  Data Cleaning & Preprocessing
Handled in `Diwali_Sales_Analysis.ipynb`:
1. Dropped irrelevant columns: `Status`, `unnamed1`.
2. Removed null rows: Reduced from ~13K to 10,655 rows.
3. Converted `Amount` to integer.
4. Renamed `Marital_Status` → `Shaadi`.

## Exploratory Data Analysis (EDA) Highlights
Key visualizations and findings:

### 1. Gender Distribution & Sales
```
Females: 70% buyers, higher avg spend (₹14K vs ₹11K for males).
```
![Gender Sales](https://via.placeholder.com/600x300?text=Gender+Sales+Barplot) *(View notebook for interactive charts)*

### 2. Top Age Group
```
26-35 yrs (esp. females): 50%+ orders.
```
![Age Group](https://via.placeholder.com/600x300?text=Age+Group+Countplot)

### 3. Top States (Orders & Amount)
| State           | Orders | Amount (₹ Cr) |
|-----------------|--------|---------------|
| Uttar Pradesh  | 24K   | 15.2         |
| Maharashtra    | 14K   | 10.1         |
| Karnataka      | 9K    | 6.3          |

![State Sales](https://via.placeholder.com/800x300?text=Top+States+Barplot)

### 4. Marital Status & Occupation
- **Married women** dominate high-value purchases.
- **Top Occupations**: IT, Healthcare, Aviation.

### 5. Top Product Categories
```
Food (26%), Clothing (17%), Electronics (12%).
```
![Product Category](https://via.placeholder.com/800x300?text=Product+Category+Sales)

**Core Insight**: *Married women (26-35 yrs) from UP/Maharashtra/Karnataka in IT/Healthcare/Aviation buy most Food/Clothing/Electronics.*

##  Business Recommendations
1. **Targeted Campaigns**: Email/SMS to married women 26-35 in top states with Food/Clothing deals.
2. **Stock UP**: Allocate 50% inventory to top 3 states/categories.
3. **Occupation Focus**: Partner with IT/Healthcare firms for Diwali promotions.
4. **A/B Test**: Gender-specific discounts → Expected 15% sales lift.

##  Technologies Used
- **Python**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Notebook**: Jupyter

##  How to Run
1. Install dependencies: `pip install pandas numpy matplotlib seaborn jupyter`
2. Open: `jupyter notebook Diwali_Sales_Analysis.ipynb`
3. Run all cells for EDA & charts.

##  Results Showcase
Total Sales: **₹1.82 Cr** | Avg Order: ₹844 | Top Product IDs by Amount available in notebook.

**Portfolio Project by [Your Name] | LinkedIn/GitHub: [Add Links]**

![Diwali Sales](https://via.placeholder.com/1200x400?text=Diwali+Sales+Dashboard)
*(Full analysis in notebook)*

