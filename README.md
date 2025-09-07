# NURSING HOME INVESTMENT DASHBOARD

## Overview
This dashboard analyzes over **14,400 nursing homes across the United States (2015–2021)** to:
1. Provide a **data-driven presentation** into nursing home investment opportunities.  
2. Deliver an **interactive Tableau tool** to help investors explore the data themselves.  
3. Share insights on **financial health, geographic distribution, and investment risks/opportunities**.
4. 
The goal is to support **investment decisions** in the nursing home industry, which is positioned for growth due to America’s rapidly aging population.  

The final deliverable is an **interactive Tableau dashboard** that allows stakeholders to understand data in 3 levels:
1. **Industry** – Opportunities vs. Challenges view.  
2. **Geographic** – State-level investment potential.  
3. **Company** – Filterable company-level benchmarking.  

The dashboard is available online: [NURSING HOME INVESTMENT DASHBOARD](https://public.tableau.com/views/HealthInvestment_060325/1-Industry?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## Dataset
The primary dataset was provided by the [**Business Analytics Competition at Manhattan College (2024)**](https://drive.google.com/file/d/1R46JYLJSq2kKiF3QKW3fcbHrdUogD6zM/view), compiled from [**CMS Nursing Home data (2015–2021)**](https://data.cms.gov/provider-data/topics/nursing-homes).  

It includes:
- **Cost Reports** (financial statements)  
- **Provider Information** (ownership, capacity, type)  
- **Health Deficiencies** (violations reported)  
- **Quality Measures** (service quality)  
- **Penalties** (fines and sanctions)  

Supplementary datasets:
- [**IBISWorld industry reports**](https://my.ibisworld.com/us/en/industry/62311/) (external market insights)  
- [**U.S. Census Bureau population data**](https://data.census.gov/table/ACSST1Y2023.S0101?q=population%20by%20age%20by%20state&tp=false) (aging trends by state)  

---

## Tools & Workflow
- **Excel:** Quick reformatting and adjustments for external datasets.
- **Python (Jupyter Notebook):** Data engineering, preprocessing, and integration across 200+ attributes.
- **Tableau:** Dashboard design, visualization, and storytelling.  
- **SQL:** Establishing data relationships as per the entity–relationship model below.  
![image](https://github.com/user-attachments/assets/619cf072-d914-4e91-8003-8a274b86105e)

---

## Key Insights
- **Nursing homes are resilient:** They generated stable revenues even during COVID-19, compared to other healthcare businesses.  
- **Government support is high:** The industry is regulated but also heavily funded.  
- **Best investment regions:** Northeast, Midwest, and Florida.  
- **Investor risks:** Rising labor costs and increasing competition.  

---
## Dashboard Descriptions

The interactive Tableau product consists of three main dashboards, each answering a specific research question:  

#### 1. Industry Dashboard – *Overall Market Performance*
<img width="1428" height="806" alt="image" src="https://github.com/user-attachments/assets/7830620a-2a56-4522-acbf-deb4ef965b98" />

- Provides a **high-level overview of the U.S. nursing home industry** between 2015–2021.  
- Split into **Opportunities vs. Challenges** to help investors quickly identify growth drivers versus risks.  
- Key features:
  - **Revenue and profitability trends** compared with other healthcare services.  
  - **Government assistance and regulation insights**, showing both support and constraints.  
  - **Customer growth potential** (aging population data).  
  - **Compensation and competition challenges** for long-term sustainability. 

#### 2. Geographic Dashboard – *Best States for Investment*
<img width="1433" height="807" alt="image" src="https://github.com/user-attachments/assets/de72bd02-a06b-4217-9325-d97c1f1cda6c" />

- A **map-based dashboard** with interactive filters and highlight features that helps identify **which states have the strongest investment potential** based on both financial performance and demographic growth. 
- Key features:
  - **State-level nursing home distribution** across the U.S.  
  - **Financial ratios and service quality** by location.  
  - Ability to compare regions (e.g., Northeast vs. Midwest vs. Florida).  

#### 3. Comparison Dashboard – *Facility-Level Benchmarking*
<img width="1431" height="808" alt="image" src="https://github.com/user-attachments/assets/674e1879-1b7a-43bf-bd58-b846c4914a29" />

- Enables **direct comparisons between different nursing homes** to **shortlist providers** that match their strategic and financial criteria. .  
- Key features:
  - Multi-select filters (by state, ownership type, facility size, etc.).  
  - Side-by-side **financial and quality measure comparison**.  
  - Drill-down into specific providers for detailed insights.
  
---

## Reflections
Through this project, I developed:
- A deeper **understanding of the U.S. healthcare system** from both financial and operational perspectives.  
- **Strong Tableau skills**, including interactive dashboards and user-focused design.  
- The ability to bridge **data science, domain research, and investor storytelling**.  

---

## Credits

Author: **My Nhien Tang**  

Gratitude to: 
- Dr. Emily Knowles, for your insights and knowledge from from CSCN 323 (Data Visualization course)
- Anh Bình & anh Bách, for being super-users with #1 thorough feedback 
- Bình Minh & anh Brandon Nguyễn, for the support along the way

---

Last updated 09/07/2025



