# 📊 Adidas Sales Analysis — Power BI Dashboard

> **Team 1 | Mini Project | Power BI**

---

## 📌 Project Overview

This project is an interactive **Adidas Sales Analysis Dashboard** built using Microsoft Power BI. It provides a comprehensive view of Adidas's sales performance across the United States, enabling data-driven insights into revenue, profitability, regional distribution, product performance, and retailer contributions.

The dashboard is designed for business stakeholders and analysts who need quick, visual access to key sales metrics without digging through raw data.

---

## 👥 Team Members

- Ankit
- Samir
- Sushant
- Mahesh
- Pooja

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **Microsoft Power BI** (v2026.02) | Dashboard creation & report publishing |
| **Power Query (M Language)** | Data cleaning & transformation |
| **DAX (Data Analysis Expressions)** | Custom KPI calculations & measures |
| **Power BI Cloud** | File hosted and created via Power BI Cloud |
| **Microsoft Excel / CSV** | Source data (`Data Sales Adidas` dataset) |

---

## 📁 File Structure

```
TEAM_1_POWER_BI_MINI_PROJECT_Adidas_dashboard.pbix
│
├── Report/
│   └── Layout                        # Page layout & visual configurations
│   └── StaticResources/
│       └── raw_background_image.png  # Dashboard background
│       └── Adidas-Free-PNG.png       # Adidas brand logo
│
├── DataModel                         # Data model (tables, relationships)
├── Metadata                          # Report metadata (version, origin)
├── Settings                          # Query & report settings
└── Version                           # Power BI version: 1.31
```

---

## 📊 Dashboard Features

### KPI Cards (Top Row)
| Metric | Description |
|--------|-------------|
| **Total Sales** | Overall revenue from all products |
| **Operating Profit** | Profit after operational costs |
| **Units Sold** | Total units sold across all regions |
| **Price per Unit** | Average selling price per unit |
| **Operating Margin** | Profitability as a percentage of sales |

### Visualizations
| Chart Type | Fields Used | Insight |
|------------|-------------|---------|
| **Area Chart** | Invoice Date (Month) × Total Sales & Units Sold | Sales & volume trend over time |
| **Filled Map** | State × Sales, Profit, Margin, Units, Price | Geographic performance by US state |
| **Donut Chart** | Region × Total Sales | Regional sales share breakdown |
| **Bar Chart** | Product × Total Sales | Best-selling Adidas products |
| **Donut Chart** | Retailer × Total Sales | Revenue contribution per retailer |

### Filters / Slicers
- **Region** — Filter all visuals by US region
- **Invoice Date** — Filter by specific date or date range

---

## 📂 Dataset

**Source Table:** `Data Sales Adidas`

**Key Columns Used:**
- `Total Sales` — Revenue per transaction
- `Operating Profit` — Profit after expenses
- `Units Sold` — Quantity sold
- `Price per Unit` — Unit selling price
- `Operating Margin` — Profitability ratio
- `Invoice Date` — Transaction date
- `Region` — Geographic region (e.g., West, South, Northeast)
- `State` — US state
- `Product` — Adidas product category
- `Retailer` — Sales channel / retailer name

---

## 🚀 How to Open

1. Install [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).
2. Download the `.pbix` file from this repository.
3. Open Power BI Desktop → **File → Open** → select the `.pbix` file.
4. The dashboard will load with all visuals and data pre-configured.

> **Note:** No external data connection is required. All data is embedded within the `.pbix` file.

---

## 🎨 Design Highlights

- Custom **dark-themed background** with Adidas branding
- **Adidas logo** integrated into the report header
- Title: `ADIDAS SALES ANALYSIS` in bold, styled typography
- Consistent color palette aligned with Adidas brand identity
- Inner drop-shadow effects on the title for visual depth

---

## 📅 Project Info

| Field | Detail |
|-------|--------|
| **Project Type** | Academic Mini Project |
| **Tool Version** | Power BI 2026.02 |
| **Report Pages** | 1 (Page 1) |
| **Created From** | Power BI Cloud |
| **Last Modified** | February 23, 2026 |

---

## 📝 License

This project is created for **educational purposes only**. Adidas branding assets are the property of Adidas AG and are used solely for academic demonstration.
