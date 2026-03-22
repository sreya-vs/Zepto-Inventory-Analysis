# Zepto Inventory Stockout Analysis

## Overview
End-to-end inventory analysis of 3,729 SKUs across 14 categories 
for Zepto, India's fastest-growing quick-commerce platform. 
Built a data-driven SKU prioritization framework to support 
replenishment decisions when demand data is limited.

## Key Finding
Stockout rate alone is a misleading metric for replenishment 
decisions. Biscuits had the highest stockout rate (28.6%) but 
only ₹1,650 in revenue exposure. Cooking Essentials had an 
average stockout rate (12%) but the highest revenue exposure 
at ₹5,830 — 3.5x more financial impact.

## Tools Used
- Python (pandas, matplotlib, seaborn)
- Jupyter Notebook
- Excel

## Project Structure
- `zepto_analysis.ipynb` - full analysis notebook
- `Zepto-Case_Study.docx` - business write-up and recommendations
- `zepto_analysis_final.csv` - cleaned dataset with priority scores

## Outputs
- Total revenue exposure identified: ₹39,018
- 453 OOS SKUs prioritized into High/Medium/Low tiers
- 5 visualizations supporting business recommendations
- Structured recommendation report for supply chain teams
