## Possible research question: How does Cologne's population (density) compare to other cities in North Rhine-Westphalia and Europe?

## Selection and description of the datasets

### Title & Source
The analysis combines three open datasets from different administrative levels:

1. **City Level – “Population Statistics of the City of Cologne”**  
   **Source:** [Offene Daten Köln](https://offenedaten-koeln.de/dataset/statistischer-datenkatalog-k%C3%B6ln)  
   Provides annual population numbers by district and year within the city of Cologne.

2. **Regional Level – “Population of Municipalities in North Rhine-Westphalia (NRW)”**  
   **Source:** [Open.NRW Portal](https://open.nrw/dataset/bevolkerungsstand-gemeinden-stichtag)  
   Contains annual population counts for all municipalities in NRW.

3. **European Level – “Urban Audit: City Statistics / Population Density”**  
   **Source:** [data.europa.eu (Eurostat)](https://data.europa.eu/data/datasets/o2d9ur8oecotscnsldx3g)  
   Provides comparable data on population and land area for European cities.

### File Format(s)
All datasets are provided as **CSV files**, which can be easily processed using spreadsheet tools or data analysis software such as Python (pandas) or R.  
- Cologne: CSV (semicolon-separated)  
- NRW: CSV (comma-separated)  
- EU: SDMX/CSV (standardized time series format)

### Size
Approximate dataset sizes:
- **Cologne:** tbd  
- **NRW:** tbd  
- **EU:** tbd  

Combined total: tbd

### Basic Statistics (Example Values)
Based on preliminary inspection:
- **Population Cologne:** 1.097.078 inhabitants (source: [Stadt Köln](https://www.stadt-koeln.de/artikel/70400/index.html)) 
- **Area Cologne:** 405.15 km²  
- **Population Density Cologne:** 2.707,5 inhabitants/km²  
- **Population NRW Cities:** 18.011.826 inhabitants (source: [Statistik.nrw](https://statistik.nrw/))  
- **Population European Cities:** 450,4 Mio. inhabitants (source:[destatis](https://www.destatis.de/Europa/DE/Thema/Basistabelle/Bevoelkerung.html))   

These data provide a solid basis for comparing urban growth and population concentration across different regions.

### Geographic & Temporal Coverage
- **Geographic coverage:**  
  Cologne (city level), municipalities of North Rhine-Westphalia (regional level), and major European cities (EU-wide/EU-27).  

- **Temporal coverage:**  
  Most datasets cover the years **2010–2023**.

### License
All datasets are released under **open data licenses**, allowing free reuse with attribution:

- Cologne & NRW: **Datenlizenz Deutschland – Namensnennung 2.0**  
- Eurostat / data.europa.eu: **Open Data Licence (EU Open Data Portal)**  

**Reuse conditions:**  
Data may be reused, shared, and modified for educational and research purposes, provided the source is cited.

---
## Augment the Dataset

### Additional Data Integration
Although the main analysis already combines three datasets — for Cologne, North Rhine-Westphalia (NRW), and Europe — these can be further enriched by aligning them into a single comparable structure. This augmentation step focuses on creating consistency between local, regional, and European data sources.

### How the Datasets Could Be Linked or Compared
The datasets share similar attributes such as *population*, *area*, and *year*, which allow for direct comparison after standardization.  
They can be linked conceptually as follows:

- **Cologne dataset** provides detailed local population and area data.  
- **NRW dataset** includes data for all municipalities in the region, including Cologne.  
- **European dataset** offers population and area data for major European cities.

By harmonizing variable names and units (e.g., converting all areas to km² and ensuring population counts are for the same year), a combined dataset can be created to compare **population densities across different geographic levels**.

### Research Question
This integration directly supports the core research question:

> **How does Cologne’s population density compare to other cities in North Rhine-Westphalia and Europe?**

Combining the datasets enables a consistent comparison between Cologne and cities at both the regional and European levels, using population per km² as the main indicator.

### Next Steps for Merging
To prepare the datasets for analysis, the following steps are necessary:

1. **Select common variables** — population, area, and year.  
2. **Standardize units** — ensure all area values are in km² and population values are absolute counts.  
3. **Align timeframes** — choose a shared reference year (e.g., 2020 or 2023) across all datasets.  
4. **Clean city names** — harmonize naming conventions (e.g., “Köln” vs “Cologne”).  
5. **Merge datasets** — use city or municipality names as keys to create a unified table.  
6. **Calculate population density** — compute inhabitants per km² for each city.  
7. **Visualize results** — create charts or maps showing Cologne’s density compared to other cities.

**Outcome:**  
By augmenting and harmonizing the three chosen datasets, it becomes possible to perform a robust comparative analysis of population density — positioning Cologne within the broader urban context of NRW and Europe.

---

## Review the Dataset Using FAIR Principles

The combined datasets — from *Offene Daten Köln*, *Open.NRW*, and *Eurostat (data.europa.eu)* — were assessed using the FAIR principles: **Findable**, **Accessible**, **Interoperable**, and **Reusable**.

### Findable
Each dataset is **easy to locate** through its respective open data portal:
- Cologne and NRW datasets are indexed on the **official regional open data platforms** with descriptive titles and metadata (e.g., publisher, update frequency, geographic scope).
- The Eurostat dataset is **well-documented** and searchable via the *data.europa.eu* portal with clear metadata identifiers and dataset descriptions.

Overall, the datasets meet the *Findable* criterion, as they include sufficient metadata, persistent URLs, and searchable identifiers.

### Accessible
All three datasets are **openly accessible without registration**:
- Files can be downloaded directly in standard formats (CSV or SDMX/CSV).
- Access does not require authentication or restricted APIs.
- Metadata and documentation are also publicly available.

Therefore, the datasets are **highly accessible**, supporting transparency and reproducibility.

### Interoperable
The datasets are provided in **machine-readable and widely used formats**:
- CSV is compatible with most analytical tools (Python, R, Excel).
- Column structures and encoding (UTF-8) are suitable for automated processing.
- Minor differences exist in delimiters and naming conventions, but these can be standardized easily during data cleaning.

The datasets are **mostly interoperable**, requiring only minimal preprocessing to ensure full compatibility.

### Reusable
Each dataset is published under an **open license**:
- Cologne and NRW datasets: *Datenlizenz Deutschland – Namensnennung 2.0*  
- Eurostat dataset: *EU Open Data Licence*  

Licenses are clearly stated, allowing reuse with proper attribution.  
The datasets include **sufficient documentation and metadata** (source, update date, variables, and measurement units), enabling future analyses beyond this project.

The datasets are **fully reusable**, provided that proper citation practices are followed.





