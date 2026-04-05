# Brazil Real Estate Analysis

**Author:** Youssef Magar  
**Objective:** Explore the Brazilian real estate market, analyze pricing, and understand key factors influencing home values.

---

## 1. Project Overview

This project analyzes real estate data in Brazil to explore the key factors affecting housing prices.  

**Main Goals:**

1. Identify the most expensive regions in Brazil
2. Explore the relationship between property size and price
3. Analyze the impact of location (state/region) on housing prices

The dataset comes from multiple sources and required cleaning, transformation, and consolidation.

---

## 2. Data Cleaning & Transformation

- Removed missing values to ensure data quality
- Split `lat-lon` into separate `lat` and `lon` columns
- Extracted `state` information from hierarchical location names
- Converted all prices to USD for consistency
- Merged multiple datasets into a single DataFrame for analysis

---

## 3. Exploratory Data Analysis (EDA)

### 3.1 Geographical Distribution
- Interactive map shows property locations across Brazil
- Most properties cluster around major urban areas
![Map Placeholder](images/map_placeholder.png)

### 3.2 Summary Statistics
- Analyzed `area_m2` and `price_usd`
- Price distribution is right-skewed due to few high-value properties
- Most homes are medium-sized (50–200 m²)
![Histogram Placeholder](images/histogram_placeholder.png)
![Boxplot Placeholder](images/boxplot_placeholder.png)

### 3.3 Mean Price by Region
- South and Southeast regions have higher average prices
![Bar Plot Placeholder](images/barplot_placeholder.png)

### 3.4 South Region Case Study
- Analyzed homes specifically in the South region
- Count of homes per state and correlation between area and price
- Some states show strong correlation between size and price

---

## 4. Key Findings

1. Property prices vary significantly across regions.  
2. Larger properties generally cost more, but correlation differs by state.  
3. South region shows strong correlation between area and price.  
4. Price per square meter is a more reliable metric for comparison across states.

---

## 5. Technologies Used

- **Python** – Main programming language
- **pandas** – Data manipulation
- **matplotlib** – Static plots (histograms, boxplots)
- **plotly** – Interactive maps for geospatial visualization

---

## 6. How to Run

1. Clone this repository:

```bash
git clone https://github.com/yousef-magar/brazil-real-estate-analysis.git
cd brazil-real-estate-analysis