# 🧠 Warranty Claims Analytics Using Python and Power BI

### 🔍 Problem Statement
The organization faced increasing **warranty claim costs** despite stable production and shipment levels.  
There was no integrated view of:
- Which **models or parts** failed most frequently  
- How failures varied across **regions, vendors, and time**  
- Which **repairs and replacements** were driving the highest warranty expenses  

The goal of this project is to create a **data-driven analytics framework** combining **Python and Power BI** to identify cost drivers, improve product reliability, and guide preventive actions.

---

### 💡 Project Overview
This end-to-end analytics solution integrates **Python-based data engineering** with **Power BI dashboards**, transforming raw warranty data into business insights.

#### **1️⃣ Data Engineering (Python)**
- Cleaned and merged three datasets — *claims*, *failures*, and *replacements* — totaling **1.4M+ records**.  
- Standardized columns, formatted costs and dates, and linked data via `Claim Number`.  
- Derived analytical fields such as:
  - Failure frequency per model and part  
  - Average claim cost  
  - Vendor-wise failure ratios  

#### **2️⃣ Exploratory Data Analysis (EDA)**
- Performed statistical and visual analysis using **pandas**, **matplotlib**, and **seaborn**.  
- Key EDA highlights:
  - Top failure types include *Cracked*, *Electrical Connection*, and *Shorted*.  
  - Summer months show ~30% more claims than other seasons.  
  - Vendors `547628` and `668200` produce most high-cost failures.  
  - Ohio and Quebec lead in claim volumes.  

#### **3️⃣ Business Intelligence (Power BI)**
Developed a multi-page Power BI dashboard to visualize:
- KPI cards for total claims, total claim dollars, and average claim cost  
- Year-over-year trends in claim counts and cost  
- Failure types and vendor performance  
- Regional and seasonal breakdowns

---

### 📊 Dashboard Preview

**1️⃣ Warranty Claims Overview**  
> Displays overall claim KPIs, cost trends, and top-performing models.

![Warranty Claims Overview](BI%20Dashboards/PowerBI%201.png)

---

**2️⃣ Failure Types & Vendor Insights**  
> Shows top failure causes, vendor performance, and defective part distribution.

![Failure Types & Vendor Insights](BI%20Dashboards/Power%20BI%202.png)

---

**3️⃣ Regional & Seasonal Trends**  
> Compares claim counts across regions and seasons to highlight cost hotspots.

![Regional & Seasonal Trends](BI%20Dashboards/Power%20BI%203.png)

---

### 🧮 Key Insights
| Focus Area | Key Findings |
|-------------|---------------|
| **Models** | 10 models contributed to over 50% of total warranty spend |
| **Vendors** | Vendor IDs `547628` and `668200` had highest failure ratios |
| **Failures** | “Cracked” and “Electrical Connection” were top recurring issues |
| **Regions** | Highest claims in Ohio (USA) and Quebec (Canada) |
| **Seasonality** | Summer months had 25–30% more claims than other periods |

---

### 🚀 Business Impact
- Improved visibility into warranty KPIs with real-time dashboards  
- Identified potential **$8M+ in savings** via vendor quality improvement  
- Provided management with data-backed insights for production and supplier decisions  

---

### ⚙️ Tech Stack
| Category | Tools / Libraries |
|-----------|------------------|
| Data Processing | Python (pandas, numpy) |
| Visualization | matplotlib, seaborn, Power BI |
| Machine Learning | scikit-learn |
| Presentation | PowerPoint (EDA Summary) |
| Version Control | Git & GitHub |

---

### 📁 Repository Structure
