# Project Overview
This project analyzes CRM and sales pipeline data using Google Sheets to uncover insights across accounts, products, and sales teams. Built on a star schema, it helps track deal performance, win rates, and revenue trends in a clear and structured way.

# Key Focus Areas
- Sales performance analysis across accounts, products, and sales teams
- Monitoring deal distribution across pipeline stages (Won, Lost, Open, Prospect)
- Revenue analysis by sector, product series, and sales agents
- Tracking key metrics like win rate, average deal value, and sales cycle time
- Identifying top-performing and underperforming segments
  
# Core Objectives
- Clean and transform raw CRM data using Google Sheets
- Build structured datasets for analysis and reporting
- Develop dashboards to visualize sales trends and KPIs
- Generate actionable insights to improve sales performance

[Download Transformed Sheet](https://github.com/ruchi-010/CRM-Sales-Analysis/blob/main/CRM_SALES_Sheets_File.xlsx)

# Data Structure
The dataset follows a star schema with the Sales Pipeline as the central fact table, connected to dimension tables including Accounts, Products, and Sales Teams. This structure enables efficient analysis of sales performance across multiple dimensions.

<img width="1920" height="1080" alt="Data Structure" src="https://github.com/user-attachments/assets/7ae4ad6c-0a15-4a4b-8c90-f6603650911c" />

# Executive Summary

![Screenshot 2026-04-10 011822](https://github.com/user-attachments/assets/3018af07-745b-4b3f-bf46-91aecb486b8f)

- Business generated **$10M+ in revenue** with a healthy **win rate of ~63%**
- Sales cycle duration (**52 days**) suggests room for faster revenue realization
- Pipeline still holds **~23% of deals (open + prospect)**, representing untapped revenue potential
- Product performance is concentrated, with **GTX series leading growth**
- Clear performance disparity across sales teams, indicating scalability challenges
- High-performing agents demonstrate **replicable success patterns**
- Sector-wise variation suggests **targeted market opportunities**

### Strategic Priorities
- Improve **pipeline conversion efficiency**
- Reduce **sales cycle time**
- Scale best practices from **top-performing agents**
- Focus on **high-value deals and key product lines**

## Insights

- **Revenue is concentrated in a few key sectors**:  
  Retail leads with **$1.86M**, followed by Technology (**$1.51M**) and Medical (**$1.35M**), while sectors like Employment (**$436K**) and Services (**$533K**) lag significantly.

- **Strong dependency on a single product series**:  
  The **GTX series contributes $7.34M (~73% of total revenue)**, far exceeding MG (**$2.26M**) and GTK (**$400K**).

- **Top products dominate revenue contribution**:  
  **GTXPro ($3.51M)** and **GTX Plus Pro ($2.63M)** together account for over **60% of total revenue**, highlighting concentration in a few high-performing products.

- **Leadership impact reflected in revenue outcomes**:  
  Manager-level revenue ranges from **~$1.1M to $2.25M**, suggesting differences in team effectiveness and sales execution.

- **Sales performance is highly skewed toward top agents**:  
  The leading agent generates **$1.15M**, while most agents fall within the **$200K–$500K range**, with some contributing **no revenue**.

## Key Recommendations & Trade-offs
- **Reduce dependency on GTX product line**  
  Diversify the portfolio as the **GTX series contributes $7.34M (~73% of total $10M revenue)**, while MG contributes **$2.26M** and GTK only **$400K**.  
  **Trade-off:** Shifting focus may impact short-term revenue since GTX is currently the strongest performer.

- **Prioritize high-value product sales**  
  Promote premium products like **GTXPro ($3.51M)** and **GTX Plus Pro ($2.63M)**, which together contribute over **60% of total revenue**, to increase deal value.  
  **Trade-off:** Increased focus on high-value deals may reduce total deal volume.

- **Leverage high-performing sectors**  
  Focus on sectors like **Retail ($1.86M)** and **Technology ($1.51M)**, which are the top revenue contributors compared to lower sectors like **Employment ($436K)**.  
  **Trade-off:** Over-investment in top sectors may limit diversification and future growth in smaller markets.

- **Standardize best practices across sales teams**  
  Scale strategies from top performers, where leading agents generate up to **$1.15M**, compared to many agents in the **$200K–$500K range** or even **$0 revenue**.  
  **Trade-off:** Not all high-performer strategies may be applicable across different agents or regions.
  
