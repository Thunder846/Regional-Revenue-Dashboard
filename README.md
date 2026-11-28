<div align="center">

# 📊 Regional Revenue Dashboard

### 🏪 Excel-Based Sales Performance Analytics

[![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/en-us/microsoft-365/excel)
[![Formulas](https://img.shields.io/badge/Advanced_Formulas-FF6B6B?style=for-the-badge)]()
[![SUMIFS](https://img.shields.io/badge/SUMIFS-0176D3?style=for-the-badge)]()
[![VLOOKUP](https://img.shields.io/badge/VLOOKUP-FFA500?style=for-the-badge)]()
[![XLOOKUP](https://img.shields.io/badge/XLOOKUP-28A745?style=for-the-badge)]()

**An interactive Excel dashboard for analyzing regional revenue performance. Built using Excel formulas including SUMIFS, VLOOKUP, and XLOOKUP - no Pivot Tables or DAX required!**

[Features](#-features) • [Installation](#-installation) • [Usage](#-usage) • [Architecture](#-architecture) • [Insights](#-key-insights) • [Author](#-author)

</div>

---

## 📑 Table of Contents

- [Project Overview](#-project-overview)
- [Key Highlights](#-key-highlights)
- [Tech Stack](#-tech-stack)
- [Dataset Information](#-dataset-information)
- [Features](#-features)
- [Business Problem](#-business-problem)
- [Dashboard Goal](#-dashboard-goal)
- [Architecture](#-architecture)
- [Excel Formulas](#-excel-formulas)
- [Dashboard Walkthrough](#-dashboard-walkthrough)
- [Key Insights](#-key-insights)
- [Business Impact](#-business-impact)
- [Installation & Setup](#-installation--setup)
- [How to Use](#-how-to-use)
- [Project Structure](#-project-structure)
- [File Specifications](#-file-specifications)
- [Screenshots](#-screenshots)
- [Troubleshooting](#-troubleshooting)
- [Future Enhancements](#-future-enhancements)
- [Author](#-author)

---

## 📌 Project Overview

The **Regional Revenue Dashboard** is a comprehensive Excel-based analytics solution that helps retail businesses analyze regional revenue performance, store performance, and product-level growth trends.

Built as a **single-file Excel solution**, this project combines raw data, advanced Excel formulas (SUMIFS, VLOOKUP, XLOOKUP), and interactive visualizations into one cohesive `.xlsx` file - **without using Pivot Tables or Power Pivot**.

The dashboard transforms store and product revenue data into actionable business insights through:
- Interactive KPIs
- Store performance analysis
- Product growth tracking
- Monthly comparison metrics
- Top/Bottom product identification
- Dynamic filters

**Designed for:**
- 🏪 Retail Analysts
- 📊 Regional Managers
- 💼 Sales Directors
- 📈 Business Operations Teams
- 💼 Retail Decision Makers
- 📚 Data Analytics Students

---

## 🌟 Key Highlights

| Highlight | Details |
|-----------|---------|
| 📁 **Single File Solution** | Data + Dashboard in one `.xlsx` file |
| 📊 **Multi-Year Data** | Comprehensive revenue dataset |
| 🧠 **Formula-Based** | SUMIFS, VLOOKUP, XLOOKUP only - No Pivot Tables |
| 📈 **10+ Visualizations** | Charts, bar graphs, trend lines |
| 📊 **YoY & MoM Analysis** | Year-over-Year and Month-over-Month tracking |
| 🏪 **Multiple Stores** | Various retail locations |
| 📅 **Monthly Comparison** | August 2023 vs September 2023 analysis |
| 📊 **Product Performance** | Growth drivers and loss leaders |
| 🏷️ **Product Categories** | Category-level analysis |

---

## 🛠 Tech Stack

This project was built using the following Microsoft Excel technologies:

| Technology | Purpose |
|------------|---------|
| 📊 **Microsoft Excel** | Main platform for dashboard |
| 📝 **SUMIFS Formula** | Conditional summing for KPIs |
| 🔍 **VLOOKUP Formula** | Data lookup and matching |
| 🎯 **XLOOKUP Formula** | Advanced data lookup |
| 📈 **Conditional Formatting** | Dynamic visual indicators |
| 📊 **Charts & Graphs** | Data visualization |
| 📁 **File Format** | `.xlsx` (Excel 2016+) |

> ✅ **No Power Pivot or DAX Required!** This dashboard uses only Excel formulas and works on standard Excel versions.

---

## 📂 Dataset Information

The dashboard uses a retail revenue dataset containing store-level and product-level revenue data across multiple US locations with 10 columns.

### Dataset Schema (10 Columns)

| # | Column Name | Data Type | Description | Example |
|---|-------------|-----------|-------------|---------|
| 1 | `Year` | Integer | Year of transaction | 2023 |
| 2 | `Month` | Text | Month of transaction | September |
| 3 | `Store Name` | Text | Store location name | Time Square |
| 4 | `Region` | Text | Region location | Northeast |
| 5 | `Store Type` | Text | Type of store | Mall / Standalone |
| 6 | `Product Name` | Text | Product sold | Playfoam |
| 7 | `Product Category` | Text | Category of product | Toys |
| 8 | `Units Sold` | Integer | Number of units sold | 245 |
| 9 | `Revenue` | Decimal | Revenue amount | $6,638.00 |
| 10 | `Profit` | Decimal | Profit amount | $1,327.60 |

### Data Distribution

| Metric | Value |
|--------|-------|
| Total Columns | 10 |
| Analysis Period | August 2023 - September 2023 |
| Comparison Period | August 2023 vs September 2023 |
| Store Locations | Multiple |
| Product Categories | Multiple |
| Report Type | Monthly Revenue Analysis |

---

## ✨ Features

### 📊 Dashboard Features

- ✅ **Executive KPI Cards** - Total Revenue, YoY Growth, MoM Growth
- ✅ **Revenue Trend Analysis** - Monthly trend comparison
- ✅ **Store Performance** - Current month vs Last month comparison
- ✅ **Product Growth Leaders** - Top 5 revenue-driving products
- ✅ **Product Loss Leaders** - Top 5 products causing revenue decline
- ✅ **Region Analysis** - Performance by region
- ✅ **Store Type Analysis** - Performance by store type
- ✅ **Category Analysis** - Product category performance
- ✅ **Conditional Formatting** - Color-coded performance indicators
- ✅ **YoY & MoM Calculations** - Percentage growth tracking

### 🔧 Technical Features

- ✅ Single-file Excel solution
- ✅ SUMIFS formulas for conditional summing
- ✅ VLOOKUP for store name lookups
- ✅ XLOOKUP for advanced data matching
- ✅ Dynamic named ranges
- ✅ Conditional formatting
- ✅ Interactive charts and visualizations
- ✅ Monthly comparison capabilities

---

## 📌 Business Problem

Retail businesses face challenges in tracking regional revenue performance without a centralized analytics solution. Key questions that remain unanswered:

- ❓ What is the total revenue for the current month?
- ❓ How does revenue compare to last month?
- ❓ How does revenue compare to last year?
- ❓ Which stores are performing best/worst?
- ❓ Which products are driving revenue growth?
- ❓ Which products are causing revenue decline?
- ❓ How do different regions perform?
- ❓ Which store types are most profitable?
- ❓ What are the key growth trends across months?
- ❓ Which product categories are performing best?

**Manual analysis of store and product data is:**
- ⏰ Time-consuming
- 💰 Expensive
- ❌ Prone to errors
- 📉 Lacks actionable insights

---

## 🎯 Dashboard Goal

The objective of this dashboard is to provide a **centralized, formula-based reporting solution** that helps retail businesses:

- 📊 Monitor regional revenue performance
- 🏪 Identify top and bottom performing stores
- 📈 Track product-level revenue trends
- 🔍 Analyze month-over-month changes
- 📊 Compare year-over-year performance
- 💰 Identify revenue growth drivers
- 📉 Detect revenue loss leaders
- 🎯 Support data-driven retail decisions
- 🏷️ Analyze product category performance
- 📍 Compare regional performance

---

## 🏗 Architecture

### Single-File Structure (5 Sheets)

```
┌─────────────────────────────────────────────────────┐
│   Regional_Revenue_Dashboard.xlsx                   │
│                                                     │
│  ┌──────────────────────────────────────────────┐   │ 
│  │ Sheet 1: Requirements                        │   │
│  │ (Dashboard Requirements & Scope)             │   │
│  └──────────────────────────────────────────────┘   │
│                                                     │
│  ┌──────────────────────────────────────────────┐   │
│  │ Sheet 2: Data                                │   │
│  │ (Raw Data - 10 Columns)                      │   │
│  └──────────────────────────────────────────────┘   │
│              ↓ (Excel Formulas)                     │
│  ┌──────────────────────────────────────────────┐   │
│  │ Sheet 3: Dashboard                           │   │
│  │ (Revenue Analysis Dashboard)                 │   │
│  └──────────────────────────────────────────────┘   │
│                                                     │
│  ┌──────────────────────────────────────────────┐   │
│  │ Sheet 4: August 2023                         │   │
│  │ (August Revenue Data)                        │   │
│  └──────────────────────────────────────────────┘   │
│                                                     │
│  ┌──────────────────────────────────────────────┐   │
│  │ Sheet 5: September 2023                      │   │
│  │ (September Revenue Data)                     │   │
│  └──────────────────────────────────────────────┘   │
└─────────────────────────────────────────────────────┘
```

### Data Flow

```
Raw Data (Data Sheet) → Excel Formulas (SUMIFS/VLOOKUP/XLOOKUP) → Dashboard
```

---

## 📝 Excel Formulas

All calculations created using **standard Excel formulas**:

### Core KPI Calculations

**Total Revenue (September 2023)**
```excel
=SUMIFS(Revenue_Range, Month_Range, "September", Year_Range, 2023)
```

**Total Revenue (August 2023)**
```excel
=SUMIFS(Revenue_Range, Month_Range, "August", Year_Range, 2023)
```

**Month-over-Month Growth (September vs August)**
```excel
=((September_Revenue - August_Revenue) / August_Revenue) * 100
```

**Store Revenue (September 2023)**
```excel
=SUMIFS(Revenue_Range, Store_Range, Store_Name, Month_Range, "September", Year_Range, 2023)
```

**Store Revenue (August 2023)**
```excel
=SUMIFS(Revenue_Range, Store_Range, Store_Name, Month_Range, "August", Year_Range, 2023)
```

### Product Performance Calculations

**Product Revenue (September 2023)**
```excel
=SUMIFS(Revenue_Range, Product_Range, Product_Name, Month_Range, "September", Year_Range, 2023)
```

**Product Revenue (August 2023)**
```excel
=SUMIFS(Revenue_Range, Product_Range, Product_Name, Month_Range, "August", Year_Range, 2023)
```

**Product MoM Change**
```excel
=September_Revenue - August_Revenue
```

### Regional Performance

**Region Revenue (September 2023)**
```excel
=SUMIFS(Revenue_Range, Region_Range, Selected_Region, Month_Range, "September", Year_Range, 2023)
```

### Store Type Analysis

**Store Type Revenue (September 2023)**
```excel
=SUMIFS(Revenue_Range, Store_Type_Range, Selected_Type, Month_Range, "September", Year_Range, 2023)
```

### Category Performance

**Category Revenue (September 2023)**
```excel
=SUMIFS(Revenue_Range, Category_Range, Selected_Category, Month_Range, "September", Year_Range, 2023)
```

### VLOOKUP Examples

**Store Region Lookup**
```excel
=VLOOKUP(Store_Name, Store_Lookup_Range, 2, FALSE)
```

**Store Type Lookup**
```excel
=VLOOKUP(Store_Name, Store_Lookup_Range, 3, FALSE)
```

### XLOOKUP Examples

**Find Revenue for Specific Store-Product Combination**
```excel
=XLOOKUP(1, (Store_Range=Selected_Store)*(Product_Range=Selected_Product), Revenue_Range, 0)
```

---

## 📊 Dashboard Walkthrough

#### Executive KPI Cards

| KPI | Value | Description |
|-----|-------|-------------|
| 💰 **Total Revenue** | $44,041 | Revenue for September 2023 |
| 📈 **YoY Growth** | +26.26% | vs. Last Year |
| 📊 **MoM Growth** | +6.71% | vs. Last Month |

#### Revenue Trend Analysis

- 📈 **2023 vs 2022 Revenue Trend** - Line chart showing monthly comparison
- 📊 **Store Performance Comparison** - Top 3 Performing Store s&  Bottom 3 Performing Stores

### Store Performance Insights

#### 🏆 Top 3 Performing Stores

| Rank | Store | Revenue | Key Success Factors |
|------|-------|---------|---------------------|
| 1 | **Times Square** | $20,484 | High foot traffic, tourist location |
| 2 | **Millennium** | $18,238 | Mall location, premium positioning |
| 3 | **O'Hare** | $18,238 | Airport location, high volume |

#### 📉 Bottom 3 Performing Stores

| Rank | Store | Revenue | Improvement Areas |
|------|-------|---------|-------------------|
| 8 | **JFK** | $13,879 | Airport location, seasonal variance |
| 9 | **Hollywood** | $10,010 | Tourist dependency |
| 10 | **Michigan Ave** | $7,722 | Underperforming location |


### Product Performance Analysis

#### 🚀 Growth Drivers (Top 5 Products)

| Product Name | Current Rev | Last Month Rev | MoM Change |
|--------------|-------------|----------------|------------|
| Playfoam | $6,638 | $2,550 | +$4,088 |
| Magic Sand | $16,326 | $12,792 | +$3,534 |
| Nerf Gun | $9,135 | $6,637 | +$2,499 |
| Barrel O' Slime | $4,988 | $3,599 | +$1,389 |
| Mini Ping Pong Set | $4,705 | $3,856 | +$849 |

#### 📉 Loss Leaders (Top 5 Products)

| Product Name | Current Rev | Last Month Rev | MoM Change |
|--------------|-------------|----------------|------------|
| Lego Bricks | $23,034 | $27,913 | -$4,879 |
| Rubik's Cube | $5,497 | $8,376 | -$2,879 |
| Etch A Sketch | $1,868 | $4,030 | -$2,162 |
| Colorbooks | $9,729 | $11,347 | -$1,619 |
| Animal Figures | $6,950 | $8,469 | -$1,520 |

---

## 💡 Key Insights

### 🚀 Growth Opportunities

| # | Finding | Impact | Recommended Action |
|---|---------|--------|---------------------|
| 1 | 🚀 **Playfoam grew by $4,088 MoM** | High | Increase inventory and promotion |
| 2 | 🚀 **Magic Sand up $3,534 MoM** | High | Expand shelf space |
| 3 | 🚀 **Nerf Gun increased $2,499** | Medium | Cross-promote with other toys |
| 4 | 📊 **Total revenue grew 6.71% MoM** | Positive | Continue current strategy |
| 5 | 📊 **YoY growth at 26.26%** | Excellent | Replicate successful strategies |

### 📉 Areas for Improvement

| # | Finding | Impact | Recommended Action |
|---|---------|--------|---------------------|
| 1 | 📉 **Lego Bricks lost $4,879** | Critical | Investigate price/competition issues |
| 2 | 📉 **Rubik's Cube down $2,879** | High | Check inventory and demand |
| 3 | 📉 **Etch A Sketch declined $2,162** | Medium | Evaluate product lifecycle |
| 4 | ⚠️ **Colorbooks down $1,619** | Medium | Review pricing strategy |
| 5 | ⚠️ **Animal Figures down $1,520** | Medium | Assess promotional needs |

### 📈 Key Performance Metrics

| Metric | Value | Status |
|--------|-------|--------|
| Total Revenue | $44,041 | ✅ Healthy |
| YoY Growth | +26.26% | 🟢 Excellent |
| MoM Growth | +6.71% | 🟢 Positive |
| Top Product Growth | $4,088 | 🟢 Strong |
| Largest Decline | -$4,879 | 🔴 Needs attention |

---

## 💼 Business Impact

### 📈 Strategic Benefits

#### 1. Identify Revenue Drivers
- Track product-level growth patterns
- Allocate resources to high-growth products
- Optimize inventory based on demand

#### 2. Address Revenue Declines
- Quick identification of declining products
- Root cause analysis for lost revenue
- Proactive pricing and promotion adjustments

#### 3. Store Performance Management
- Compare store performance month-over-month
- Identify best and worst performing locations
- Share best practices across stores

#### 4. Regional Analysis
- Compare performance across regions
- Identify regional growth opportunities
- Tailor strategies by region

#### 5. Store Type Optimization
- Analyze performance by store type
- Optimize store format strategy
- Identify most profitable store types

#### 6. Product Category Management
- Track category performance trends
- Optimize category mix
- Identify high-growth categories

#### 7. Data-Driven Decisions
- Real-time KPI monitoring
- Executive-level reporting
- Self-service analytics for teams

---

## 🚀 Installation & Setup

### Prerequisites

- Microsoft Excel 2016 or later
- Windows or Mac OS
- ~5 MB free disk space

> ✅ **No Add-ins Required!** This dashboard works with standard Excel.

### Installation Steps

```bash
# 1. Clone the repository
git clone https://github.com/NoreenVizLogix/Regional-Revenue-Dashboard.git

# 2. Navigate to project folder
cd Regional-Revenue-Dashboard

# 3. Open the Excel file
# Double-click Regional_Revenue_Dashboard.xlsx
# OR
start Regional_Revenue_Dashboard.xlsx
```

### File Structure After Download

```
Regional-Revenue-Dashboard/
│
├── Dashboard/
│   └── Regional_Revenue_Dashboard.xlsx  ← Main file (5 Sheets)│
├── Images/
│   └── Regional_Revenue_Dashboard.png  
│
└── README.md
```

---

## 📖 How to Use

### Step 1: Open the File
- Open `Regional_Revenue_Dashboard.xlsx`
- Enable editing if prompted

### Step 2: Review Requirements
- Click on sheet tab **"Requirements"** 
- Review dashboard scope and objectives

### Step 3: View Data
- Click on sheet tab **"Data"**
- Review raw data with 10 columns
- Verify data for August and September 2023

### Step 4: View Dashboard
- Click on sheet tab **"Dashboard"**
- View the complete revenue analysis

### Step 5: Analyze KPIs
- Review total revenue for September 2023
- Check YoY and MoM growth percentages
- Understand overall business performance

### Step 6: Store Performance
- Review store list with current month revenue
- Compare to last month performance
- Identify top and bottom performing stores

### Step 7: Product Analysis
- Review top 5 growth drivers
- Analyze top 5 revenue loss leaders
- Identify product portfolio opportunities

### Step 8: View Monthly Summaries
- Click on sheet tab **"August 2023"** - View August revenue summary
- Click on sheet tab **"September 2023"** - View September revenue summary

### Step 9: Modify as Needed
- Update data in Data sheet
- Formulas update automatically
- Dashboard reflects new data

---

## 📂 Project Structure

```
Regional-Revenue-Dashboard/
│
├── Dashboard/
│   └── Regional_Revenue_Dashboard.xlsx  ← Main Excel file
│       ├── Sheet 1: Requirements (Dashboard Scope)
│       ├── Sheet 2: Data (Raw Data - 10 Columns)
│       ├── Sheet 3: Dashboard (Revenue Analysis)
│       ├── Sheet 4: August 2023 (August Data)
│       └── Sheet 5: September 2023 (September Data)
│
├── Images/
│   └── Regional Revenue Dashboard.png

└── README.md  ← This file
```

---

## 📋 File Specifications

| Property | Value |
|----------|-------|
| 📁 File Name | `Regional_Revenue_Dashboard.xlsx` |
| 📊 File Type | Excel Workbook (.xlsx) |
| 💾 File Size | ~1-2 MB |
| 📋 Sheets | 5 sheets |
| 📈 Columns | 10 columns |
| 📝 Formulas | SUMIFS, VLOOKUP, XLOOKUP |
| 📊 Charts | 5+ |
| 🎯 KPIs | 6+ |
| 📅 Version | 1.0.0 |
| 📅 Last Updated | June 2026 |

---

## 📸 Screenshots

### Regional Revenue Dashboard

<img src="Regional Revenue Dashboard.png" width="100%">

*Figure 1: Complete Revenue Dashboard with KPIs, Store Performance, and Product Analysis*

**Includes:**
- 💰 3 KPI Cards (Total Revenue, YoY Growth, MoM Growth)
- 📈 Revenue Trend Chart
- 🏪 Store Performance Comparison
- 🚀 Top 5 Growth Drivers
- 📉 Top 5 Loss Leaders

---

## ⚠️ Troubleshooting

| Issue | Possible Solution |
|-------|-------------------|
| **"#N/A in VLOOKUP"** | Check if lookup value exists in the lookup range |
| **"Formulas not calculating"** | Enable automatic calculations: `Formulas` → `Calculation Options` → `Automatic` |
| **"Data not updating"** | Check if data range references are correct |
| **"Charts not showing correct data"** | Update chart data ranges |
| **"SUMIFS returning zero"** | Verify criteria matches data exactly |
| **"XLOOKUP not available"** | Use VLOOKUP instead for older Excel versions |
| **"Conditional formatting issues"** | Check rule order and range references |
| **"Cannot open file"** | Ensure Excel 2016+ and enable editing |
| **"Performance is slow"** | Reduce data size or optimize formulas |
| **"Sheets not visible"** | Unhide sheets if needed |

---

## 🔮 Future Enhancements

- [ ] Add regional store comparison
- [ ] Add product category analysis
- [ ] Add forecast projections
- [ ] Create Power BI version
- [ ] Add customer segmentation analysis
- [ ] Add automated email reports
- [ ] Create mobile-optimized version
- [ ] Add inventory analysis
- [ ] Add profit margin tracking
- [ ] Integrate with SQL databases
- [ ] Add What-If analysis scenarios
- [ ] Add interactive store map
