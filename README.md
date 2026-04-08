# unicef-report
# Every Child. Every Home. Every Day.
### Children & Violent Discipline Worldwide — A UNICEF Data Report

**Author:** Daksha Gujral  
**Course:** Data Analytics for Business  
**College:** Dublin City University (DCU)  
**Date:** April 2026

---

## 📌 About This Report

This report was created as part of the assignment using UNICEF data.
It investigates the global issue of **violent discipline against children aged 1–14**,
examining how rates vary across countries, genders, and income levels.

**Key finding:** Nearly **3 in 4 children** globally experience violent discipline
at home — rising to **9 in 10** in the worst-affected countries.

---

## 🌐 Live Report

👉 **[Click here to view the published report](https://daksha-gujral.github.io/unicef-report/report.html)**

---

## 📊 Visualisations Included

| Chart | Description |
|---|---|
| 🗺️ World Map | Violent discipline rate by country (choropleth) |
| 📊 Bar Chart | Top 15 most affected countries |
| 🔵 Scatterplot | GDP per capita vs discipline rate with regression line |
| 📈 Time Series | Average global rate trend from 2013–2023 |

---

## 📁 Files in This Repository

| File | Description |
|---|---|
| `report.qmd` | Main Quarto report file with all code and narrative |
| `styles.css` | Custom CSS styling for the HTML report |
| `unicef_indicator_1.csv` | UNICEF child overweight indicator data |
| `unicef_indicator_2.csv` | UNICEF violent discipline indicator data |
| `unicef_metadata.csv` | Country-level metadata (GDP, population, life expectancy) |
| `.github/workflows/publish.yml` | GitHub Actions workflow to render and publish the report |

---

## 🛠️ Built With

- **Python** — pandas, geopandas, plotnine, matplotlib
- **Quarto** — for rendering the `.qmd` file to HTML
- **GitHub Actions** — for automated rendering and deployment
- **GitHub Pages** — for hosting the live report

---

## 📚 Data Sources

- [UNICEF Data Warehouse](https://data.unicef.org/) — Violent discipline indicator
- [World Bank via UNICEF](https://data.unicef.org/resources/data_explorer/) — GDP per capita, population, life expectancy
