# Socio Economic Indicator Analysis(2018-2024)-World bank Api

Project Type: Data retrieval → cleaning/EDA → interactive visualization

Scope: African economies, 2018–2024

Tools: Python (wbdata, pandas, matplotlib/seaborn), Power BI

## Project Overview
This project analyzes socio-economic performance across African countries using the World Bank’s open data API. 
I automated the data pull in Python,reshaped and cleaned the data, performed light EDA (distributions, outliers, correlations), 
and built an interactive Power BI dashboard to compare growth, inflation, Unemployment, and other development indicators.

## Aim and Objectives
### Aim

The aim of this project is to gather, analyze and visualize key socio-economic indicators of few African countries between 2018 and 2024, using World Bank open data,
in order to uncover trends, highlight disparities, and provide insights into how major global economies are evolving.

### Objectives

Automate Data Retrieval Collect socio-economic data directly from the World Bank API to ensure accuracy, reproducibility, and transparency.

Clean and Transform Data Normalize values (e.g., monetary indicators into billions), restructure datasets, and handle missing values to prepare analysis-ready data.

Perform Exploratory Data Analysis (EDA) Investigate distributions, detect outliers, and explore correlations between indicators such as GDP growth, inflation, and poverty.

Develop Comparative Insights Compare socio-economic performance across G20 countries, identifying both convergences and divergences.

Build an Interactive Dashboard Design a Power BI dashboard that allows stakeholders to explore economic trends, filter by country, and answer guiding analytical questions.

Support Policy and Research Discussions Provide a data-driven foundation for understanding how global economic giants are balancing growth with social development.

## Data Sources
World Bank Open Data API via the Python package wbdata.<a href="https://github.com/Me1rem/Socio-economic-analysis/blob/main/Socio%20economic%20parameters-1.ipynb">Python Analysis Notebook</a>

Pulls are performed programmatically for a fixed date window (2018–2024).

## Indicators Tracked
World Bank series IDs used in the notebook:

NY.GDP.MKTP.CD — GDP (current US$)

NY.GDP.MKTP.KD.ZG — GDP growth (annual %)

NY.GNP.MKTP.CD — GNI (current US$)

NY.GNP.MKTP.KD.ZG — GNI growth (annual %)

FP.CPI.TOTL.ZG — Inflation, consumer prices (annual %)

BX.KLT.DINV.CD.WD — FDI, net inflows (BoP, current US$)

NE.GDI.TOTL.CD — Gross capital formation (current US$)

SL.UEM.TOTL.ZS — Unemployment rate (overall unemployment)

SI.POV.NAHC — Poverty headcount ratio at national poverty lines (% of population)

SE.ADT.LITR.ZS — Adult literacy rate (% ages 15+)

SP.DYN.LE00.IN — Life expectancy at birth (years)

SP.POP.GROW — Population growth (annual %)

SE.XPD.TOTL.GB.ZS — Government expenditure on education (% of GDP)

## Countries
Filtered to 15 country members from the World Bank: Angola, Botswana, Burundi, Cameroon, Cote d'Ivore, Egypt, Ethiopia, Ghana
,Morocco, Namibia, Nigeria, Rwanda, Senegal,South Africa, Uganda.

## Key Analytical Questions
How does Education expenditure drive national income growth?

How does population growth influence economic expansion?

Does Foreign investment impact Gross capital formation ?

Where is FDI concentrated and how has it shifted since 2018?

What socio-economic factors (inflation, education spend) track with Unemployment?

## Notes & Limitations
API availability: The World Bank API occasionally returns missing values for certain series/years. Visuals handle gaps, but analyses should note coverage differences.

The literacy indicator and Poverty indicators were dropped because it contained large null values.

## Data Visualization
The data was exported as an excel file,then extracted on Power BI

Wireframing was done on Figma.
<a href="https://github.com/Me1rem/Socio-economic-analysis/blob/main/Socio%20economic%20analysis2.pbix">Interact with the dashboard</a>

<a href="https://github.com/Me1rem/Socio-economic-analysis/blob/main/Screenshot%202025-09-23%20123514.png">View dashboard</a>





