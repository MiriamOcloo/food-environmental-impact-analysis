# Environmental Impact of Food Production Analysis

## Project Overview
Food production is one of the largest contributors to environmental degradation, impacting **climate change, water scarcity, land use, and biodiversity loss**.  
This project analyzes the environmental impacts of 43 common foods across different lifecycle stages (farm, processing, transport, etc.), using data from [Azubi Africa Data Analytics Project 3].

The goal is to provide **data-driven insights** to support sustainable food systems and informed policy/consumer decisions.

---

## Objectives
- Identify which foods have the **highest and lowest carbon emissions**.
- Compare **plant-based vs animal-based foods** in terms of sustainability.
- Analyze the **biggest contributors** to emissions across the food lifecycle.
- Examine trade-offs between **water use and emissions**.
- Highlight foods with the **lowest environmental footprint** as sustainable alternatives.

---

## Dataset
- **Source:** Provided by Azubi Africa (43 food products × 23 environmental metrics).
- **Key columns:**
  - Lifecycle emissions: `land_use_change`, `animal_feed`, `farm`, `processing`, `transport`, `packaging`, `retail`
  - Total emissions: `total_emissions`
  - Land use: `land_use_per_kilogram_(m²_per_kilogram)`
  - Water use: `freshwater_withdrawals_per_kilogram_(liters_per_kilogram)`
  - Eutrophication metrics

---

## Business Questions
1. Which foods have the **highest carbon footprint**?
2. How do **plant-based foods compare to animal-based foods**?
3. Which **lifecycle stage** contributes most to emissions?
4. Which foods consume the most **land and water resources**?
5. Is there a **trade-off between water use and emissions**?
6. Which food categories contribute most to **eutrophication**?
7. Which foods have the **lowest footprint** and can be promoted as sustainable?

---

## Tools & Libraries  

- **Google Colab**  
  - *Why:* Cloud-based, requires no setup, and integrates with Google Drive for easy dataset access.  
  - *How used:* As the main environment for writing, running, and documenting Python code.  

- **Python**  
  - *Why:* Industry-standard language for data analysis and visualization.  
  - *How used:* Core programming language for cleaning data, performing calculations, and generating plots.  

- **Pandas**  
  - *Why:* Provides powerful tools for working with tabular data (CSV, Excel, etc.).  
  - *How used:* To load the dataset, clean missing values, preprocess columns, create new variables, and manipulate data for analysis.  

- **NumPy**  
  - *Why:* Efficient for handling numerical operations and statistical calculations.  
  - *How used:* For aggregations (e.g., means, medians), filling missing values, and supporting Pandas calculations.  

- **Matplotlib**  
  - *Why:* Provides customizable static plots for clear data storytelling.  
  - *How used:* For bar charts, scatter plots, and side-by-side comparisons to present insights.  

- **Seaborn**  
  - *Why:* Builds on Matplotlib with simpler syntax and better default visuals.  
  - *How used:* For clean and visually appealing barplots, boxplots, and distribution charts.  

- **Plotly (optional, interactive)**  
  - *Why:* Enables interactive exploration of data, making visualizations dynamic and engaging.  
  - *How used:* For scatter plots where hovering over points reveals food names and details.  

- **GitHub**  
  - *Why:* Essential for version control, collaboration, and sharing project results.  
  - *How used:* To store the notebook, dataset (if allowed), README, and visualizations, ensuring the project is accessible and reproducible.  

---

## Key Visualizations
- Top 10 foods by total emissions  
- Plant-based vs animal-based comparison  
- Lifecycle stage contributions  
- Land vs water use (side-by-side)  
- Water vs carbon trade-off (scatter plot)  
- Top 10 foods by eutrophication  
- Bottom 10 sustainable foods  

---


