# <h1 align="center">**`Report on the Behavior of Telecommunications at the National Level`**</h1>

  Strategic Analysis - Claro

# ✏️ Project Description
This repository contains the Dashboard developed in Power BI Desktop for the strategic analysis of telecommunications in Argentina, with a focus on internet access.  
The report visualizes historical trends, technology share, growth objectives, and geographical coverage, using the latest open data from ENACOM for Q2 2024.

Demo video: https://www.youtube.com/watch?v=JAiNO_7fRrk

# 🔎 Main Objectives:

- Analyze the evolution of internet access by technology (ADSL, Cablemodem, Fiber Optic) over time.

- Measure the mandatory KPI: minimum growth of 2% in accesses per 100 households per province in the next quarter.

- Propose and visualize three additional KPIs: Fiber Optic share in AMBA, Fiber Optic market share by province, and Cablemodem market share by province.

- Identify deployment and improvement opportunities in less saturated provinces.

# 🗂️ Repository Structure

Proyecto-Individual-2/

├── Internet.xlsx         # Original dataset with multiple sheets

├── Proyecto Integrador 2.pbix   # Power BI file (model + visualizations)

├── EDA.ipynb             # Jupyter Notebook containing the Exploratory Data Analysis

└── README.md             # Documentation (this file)

# ⚙️ Technologies and Tools

- **Power BI Desktop** (version 2.139.2054.0 or higher)

- **Excel** (for data preparation and review)

- **DAX** (calculated measures for KPIs)

- **Jupyter Notebook** (for exploratory analysis)

- **Python 3.19** (libraries: Pandas, Matplotlib, and Seaborn)

# 🔁 Excel Transformations

- Removed duplicate data from the Dial-BAf sheet and all empty cells, which otherwise made the Power BI workflow heavier than the application could handle.  
- Deleted the last two rows from the "Accesos por Tecnología" sheet, since they contained a message ("Provincial data does not match the national level, as additional information without geographic breakdown was incorporated.") that was irrelevant for both the analysis and the dashboard.

# 📥 Installation and Usage

```bash
git clone https://github.com/JnPFernandez/Proyecto-Individual-2.git
cd Proyecto-Individual-2
````

- Open the project in Power BI Desktop  

  Open `pbix/Proyecto Integrador 2.pbix`.

- Update data sources  

  In the "Transform Data" panel, check the path to `data/Internet.xlsx`.  
  Apply transformations and refresh the model.

- Explore the report  

  Navigate through the four tabs: Presentation, Access by Technology, Access per 100 Households, and Broadband – Dial Up.

# 📊 Pages Description

- **Presentation**: Cover page with project visual description and navigation buttons.  

- **Access by Technology**: Timeline of ADSL, Cablemodem, and Fiber Optic; provincial share of Cablemodem and Fiber Optic; and KPI showing the percentage of Fiber Optic accesses belonging to AMBA based on the latest data.  

- **Access per 100 Households**: Evolution compared with the 2% growth target.  

- **Broadband – Dial Up**: Choropleth map of access growth in each province and a tree map showing the overall distribution of accesses for the last quarter.  

- **Conclusion**: A brief summary highlighting the main findings, providing insights on where current and future company efforts should be directed.  

# 🎯 Key KPIs

- Growth of 2% in accesses per 100 households for the next quarter  

- Percentage of Fiber Optic accesses belonging to AMBA based on the latest data  

- Cablemodem market share by province  

- Fiber Optic market share by province  

# ℹ️ Sources:

- https://www.enacom.gob.ar  
- https://www.redusers.com/noticias/que-operador-de-telefonia-celular-tiene-mejor-cobertura-en-cada-provincia/#:~:text=Utilizando%20estos%20datos%2C%20fuimos%20a,75%20por%20ciento%20en%20promedio

# 📬 Contact

Email: juanpablofernandez132@gmail.com

![Static Badge](https://img.shields.io/badge/LinkedIn-blue?link=https%3A%2F%2Fwww.linkedin.com%2Fin%2Fjpfv2%2F) ![Static Badge](https://img.shields.io/badge/Youtube-darkred?link=https%3A%2F%2Fwww.youtube.com%2F%40JuanPabloFern%25C3%25A1ndez-e6e) ![Static Badge](https://img.shields.io/badge/Notion-black?link=https%3A%2F%2Fsecond-wave-17e.notion.site%2FJuan-Pablo-Fern-ndez-Data-Analytics-Portfolio-2294eeb9829e80c39fb7e702609719a7)
