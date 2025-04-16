# 📊 EDA – Industry-Level Sales Trends (2024, Seoul)

This notebook explores quarterly sales patterns across various service industries in Seoul, using public business data from 2024. The goal of this EDA is to uncover **macro-level trends** that inform downstream sales prediction models.

---

## 📌 Objectives

- Identify the **highest-grossing industries** per quarter
- Visualize **seasonal patterns** and industry trends over time
- Pinpoint **top 5 industries** in each quarter based on total sales
- Lay the groundwork for more localized analysis (e.g., by district)

---

## 🧪 Data Overview

- **Source**: Seoul Open Data Platform  
- **Columns used**:
  - `기준_년분기_코드` (Quarter code)
  - `서비스_업종_코드_명` (Service industry name)
  - `당월_매출_금액` (Monthly sales)
  - `행정동_코드_명` (Administrative district)

---

## 📈 Key Insights

- **Top-performing industries** like 한식음식점 (Korean restaurants) and 수산물판매 (seafood sales) dominate certain quarters.
- Industry rankings can fluctuate significantly **between quarters**, reflecting strong **seasonality**.
- A small number of industries generate the majority of sales, suggesting that a few dominant sectors drive the economy.

---

## 📂 Files

- `sales_EDA.ipynb`:  
  Full notebook with clean plots, grouped bar charts, and labeled insights.  
  All comments and outputs are written in English.

---

## 🧩 Next Steps

This notebook is Part 1 of a two-stage EDA:
1. **[✓ Done]** Industry-level trend analysis  
2. **[🔜 Upcoming]** District-level analysis:  
   "How much does each neighborhood make?" and  
   "How much would a typical business (e.g., 치킨집) earn in a given district?"

---

Feel free to explore the plots and logic in the notebook, or reuse the cleaned code blocks in other notebooks.
