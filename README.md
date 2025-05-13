# 🌍 Industry Carbon Emissions Analysis (SQL)

A data analytics project exploring carbon emissions across various industries using SQL. This analysis identifies which sectors contribute most to greenhouse gas emissions, how emissions are distributed across the supply chain, and how many companies drive these emissions.

## 📌 Objective

To analyze product-level carbon emissions data from companies across industries, and uncover patterns in total emissions, contributing companies, and emissions distribution across upstream, operational, and downstream processes.

## 🧰 Tools & Technologies

- SQL (PostgreSQL)
- DataCamp Workspace
- GitHub

## 📄 Project Summary

Using SQL queries, this project investigates the `product_emissions` table containing Product Carbon Footprints (PCFs). The key focus areas include:

- Total carbon footprint per industry
- Number of companies contributing to each industry's footprint
- Emission breakdown by production phase (upstream, operational, downstream)

## 📊 Dataset Highlights

- **Table:** `product_emissions`
- **Key Fields:**
  - `company`, `country`, `industry_group`, `carbon_footprint_pcf`
  - `year`, `product_name`, `weight_kg`
  - Emission breakdown: `upstream_percent_total_pcf`, `operations_percent_total_pcf`, `downstream_percent_total_pcf`

The dataset spans multiple companies, products, and years, providing a comprehensive view of industrial emissions.

## ✅ Key Insights

- Industries like **Chemicals**, **Construction**, and **Manufacturing** were top contributors to carbon emissions.
- Emissions are not evenly distributed; certain industries account for the majority of total emissions.
- A small number of companies within each industry often drive a large share of emissions.
- The upstream and downstream phases in many cases contribute significantly to the total footprint, highlighting supply chain issues.


## 🔚 Conclusion

This project demonstrates how SQL can be used to extract insights from sustainability-related data. The results can help stakeholders prioritize emission reduction efforts within high-emitting industries and phases of production. Future work could include time-series analysis, data visualization with Python, or integration with policy targets like the UN SDGs.

## 🚀 Future Improvements

- Add Python/Plotly visualizations for industry comparisons
- Connect with APIs like CDP or GHG Protocol for real-time emissions data
- Expand analysis across multiple years for trend detection

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request with improvements or new features.


