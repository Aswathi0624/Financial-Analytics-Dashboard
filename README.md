# Financial&Budget-Analytics-Dashboard

## Project Overview

This project is a multi-page interactive Power BI dashboard designed to analyze and monitor financial performance, budgeting efficiency, and revenue trends.
The solution integrates multiple analytical views into a single report with seamless navigation, enabling users to explore insights from different financial perspectives.

## Objectives
- Track Total Revenue, Expenses, and Budget
- Evaluate Budget Utilization & Variance
- Identify high-performing categories and segments
- Provide data-driven financial insights
- Improve financial planning and discipline

## Approach

#### Data Processing
- Cleaned and transformed raw dataset using Power BI Power Query
- Handled missing values and ensured data consistency
- Created derived columns (Year, Month, etc.)
#### Data Modeling
- Built relationships between key entities (Customer, Product, Geography)
- Optimized model for performance and scalability

## Multi-Page Dashboard Design

### 1. Budget Analysis Dashboard

#### Purpose: 
Evaluate how effectively the budget is allocated and utilized.

#### Key Features:
- KPI Cards: Total Budget, Expenses, Transaction Count
- Year-wise trend: Budget vs Expenses
- Category-wise budget distribution (IT, Marketing, etc.)
- Budget accuracy analysis

#### Insights Delivered:
- Overspending areas
- Budget allocation efficiency
- Category-level financial control
  
### 2. Financial Analysis Dashboard

#### Purpose: 
Analyze revenue trends and business performance.

#### Key Features:
- KPI Cards: Total Revenue, Total Expenses, Total Amount
- Revenue vs Budget comparison (Year-wise)
- Monthly financial seasonality
- Top customers by revenue
- Industry-level performance

#### Insights Delivered:
- Revenue growth trends
- Seasonal peaks and dips
- High-value customers
- Industry contribution analysis

### 3. Financial Discipline Dashboard

#### Purpose: 
Monitor financial discipline and operational efficiency.

#### Key Features:
- Revenue vs Expenses vs Budget comparison
- Account-level budget vs revenue analysis
- Segment-wise sales (SMB, Strategic, Enterprise)
- Monthly variance tracking table

#### Insights Delivered:
- Cost control effectiveness
- Profit/loss by category
- Segment contribution to revenue
- Budget deviation patterns

## Slicers & Interactivity

### Slicers (Across Pages)

- Year → Enables trend analysis across multiple years
- Month → Supports detailed monthly breakdown
- Category (Revenue / Expense) → Dynamic metric switching
  
### Context-Specific Slicers
- Budget Analysis Page
- Product → Budget allocation per product
- Country → Regional spending insights
- Financial Analysis Page
- Industry → Industry-wise revenue comparison
- Category Toggle → Switch between Expense and Revenue
- Financial Discipline Page
- Account → Account-level financial tracking
- Segment → SMB, Strategic, Enterprise segmentation

### Slicer Capabilities
- Dropdown UI for clean design
- Multi-select enabled
- Fully interactive with all visuals
- Supports cross-filtering and drill-down analysis

### Dataset Overview

The dataset includes multi-dimensional business and financial attributes:

#### Transaction Data
- Row ID
- Order ID
- Order Date
- Date Key
#### Customer Information
- Contact Name
- Customer
- Customer ID
#### Location Data
- Country
- City
- Region
- Subregion
#### Business Attributes
- Industry
- Segment
- Product
- License
#### Financial Metrics
- Sales
- Quantity
- Discount
- Profit
#### Budget Metrics
- Expenses
- Budget
#### Classification
- Account
- Category
  
## Key Performance Indicators (KPIs)

- Total Revenue :	Overall income generated
- Total Expenses : Total operational cost
- Total Budget : Allocated financial resources
- Profit : Net earnings
- Budget Variance	: Difference between budget and expenses
- Budget Utilization % : Efficiency of budget usage
- Profit Margin % : Profitability ratio

## Tools & Technologies

- **Power BI** :	Dashboard Development
- **DAX** : Calculations & Metrics
- **Power Query**	:  Data Cleaning & Transformation
- **Excel/CSV** : Data Source

## Key Insights from Dashboard
- Revenue shows consistent growth trend
- IT category has the highest budget allocation
- Some categories show negative profit, indicating inefficiencies
- Revenue peaks during specific months (seasonality)
- Budget variance highlights overspending areas

## How to Use
1. Download or clone this repository
2. Open the .pbix file in Microsoft Power BI Desktop
3. Load or refresh the dataset
4. Navigate through report pages
5. Interact with visuals and hover for details

## Screenshots

### 1.Budget Analysis
<img width="1028" height="582" alt="Budget analysis" src="https://github.com/user-attachments/assets/23a7bb2d-3ff2-498a-9270-6eeb504a5821" />

###  2.Financial Analysis
<img width="1028" height="598" alt="Financial analysis" src="https://github.com/user-attachments/assets/4f09875d-5c5b-4355-908d-06be15f6c729" />

### 3.Financial Discipline
<img width="1028" height="596" alt="Financial discipline" src="https://github.com/user-attachments/assets/6037844d-ece6-4199-bad5-dc38f06223e6" />



