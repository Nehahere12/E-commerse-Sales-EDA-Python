E-COMMERCE SALES ANALYTICS & PROFITABILITY OPTIMIZATION | PYTHON & PLOTLY <br>
<br>
PROJECT OVERVIEW <br>
This repository contains an exploratory data analysis (EDA) and business intelligence project evaluating 9,994 transaction records from the "Sample - Superstore" dataset. Built using Python, Pandas, and Plotly, the analysis examines seasonal sales spikes, product category margin gaps, loss-making sub-categories, and segment conversion efficiencies to drive strategic retail decision-making. <br>
<br>
DATASET SUMMARY & ETL PREPARATION <br>
- Dataset Scope: 9,994 rows across 21 feature columns, including Order/Ship Dates, Customer Segments, Geographic Locations, Product Hierarchy, Sales, Quantity, Discount, and Profit. <br>
- Date Parsing & Feature Engineering: Standardized order dates to datetime formats and engineered derived time dimensions (`Order Month`, `Order Year`, `Order Day of Week`). <br>
- Quality Assurance: Confirmed zero null values across all features and validated data types prior to aggregation. <br>
<br>
KEY BUSINESS ANALYTICS COVERED <br>
- Monthly Sales & Profit Seasonality: Evaluated month-by-month performance tracking the Q4 surge (September–December) led by November sales (~$352.5K) and December profits (~$43.4K). <br>
- Category & Sub-Category Margin Analysis: Identified revenue vs profit disparities—highlighting Technology as the top overall performer (~$836.2K Sales / ~$145.5K Profit) versus Furniture's margin erosion (~$742K Sales / only ~$18.5K Profit). <br>
- Loss-Making Product Detection: Isolated sub-categories driving margin drag, specifically Tables (–$17,725 loss) and Bookcases (–$3,473 loss). <br>
- Customer Segment Conversion Efficiency: Computed Sales-to-Profit conversion ratios across segments, revealing that while Consumer drives volume (~$1.16M Sales), Home Office operates with the highest profit efficiency (7.13 ratio). <br>
<br>
TECH STACK AND TOOLS USED <br>
- Language & Environment: Python 3.x / Jupyter Notebooks <br>
- Data Manipulation & Aggregation: Pandas <br>
- Data Visualization: Interactive Plotly Express & Plotly Graph Objects <br>
