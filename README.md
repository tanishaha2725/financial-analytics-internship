# Financial & Operational Performance Analytics System
CS Vision Data Analytics Internship Program (Set A), 20 Oct – 20 Dec 2026

## Dataset
Global Superstore (Kaggle, `apoorvaappz/global-super-store-dataset`):
51,290 order lines, 2011–2014, 7 markets, 13 regions, 3 product categories.

## Project structure
- `data/raw/` – original dataset (unmodified)
- `data/clean/` – cleaned analytical dataset (CSV and Excel, 51,290 rows × 40 columns)
- `notebook/` – Jupyter notebooks (Week 1: data preprocessing)
- `report/` – written reports (Week 1: dataset description and preprocessing report)
-  `visualizations/` – 15 charts from the Week 2 exploratory analysis (PNG)
- `notebook/` – Jupyter notebooks (Week 1: data preprocessing; Week 2: exploratory data analysis)
- `report/` – written reports (Week 1: dataset and preprocessing; Week 2: exploratory financial analysis)

## Progress
- [x] Week 1: Data collection and preprocessing
- [x] Week 2: Exploratory data analysis and visualisation
- [x] Week 3: KPI development and profitability analysis
- [ ] Week 4: Interactive dashboard (Power BI / Tableau)
- [ ] Week 5: SQL analytics
- [ ] Week 6: Advanced NumPy, Pandas and visualisation
- [ ] Week 7: Reporting and data storytelling
- [ ] Week 8: Final integration and presentation

## Week 1 key findings
- Total sales 12.64M; gross profit 11.6% of sales, but net margin only 0.91% after shipping costs.
- 41.2% of order lines are loss-making; discounts above 20% average a net loss.
- Net profit is negative in EMEA, Southeast Asia, South, Caribbean and Oceania.

## Week 2 key findings
- Sales grew from 2.26M (2011) to 4.30M (2014), but net margin stayed around 1%.
- Discounts above 20% lose money: 22% of order lines, about 1.02M in total losses.
- Furniture (especially Tables) is loss-making; Technology is the most profitable category.
- Southeast Asia, EMEA and South are loss-making regions.
- Same Day and First Class shipping cost about twice as much, relative to sales, as Standard Class.

## Week 3 key findings
- 10 KPIs developed: revenue 12.64M, gross margin 11.6%, net margin 0.91%, revenue CAGR 23.9%, average order value 505.
- Discounts above 20% cover 22% of order lines and lose about 1.02M; all other lines earn a 10.6% margin.
- Tables, Chairs, Machines and Storage lose about 200K together; Copiers generate 86% of net profit.
- LATAM and EMEA are loss-making markets; 1,435 anomaly lines (2.8%) were detected.

## Tools
Python, NumPy, Pandas, Matplotlib, Seaborn, Jupyter, Git.
