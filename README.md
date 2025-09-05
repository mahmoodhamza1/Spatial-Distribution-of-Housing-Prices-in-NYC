# Impact of Socioeconomic Factors on Housing Prices in New York City

This project analyzes the **spatial distribution of housing prices in New York City (NYC)** and examines how **socioeconomic factors** such as population density, income, and land-use policies influence property values.  

The work combines **exploratory data analysis (EDA)** with **data visualization techniques** to uncover patterns in the NYC housing market. The findings are interpreted in light of prior literature on metropolitan housing price dynamics, highlighting the interaction between **demographics, economics, and policy constraints**:contentReference[oaicite:0]{index=0}.

---

## 📄 Project Overview

Housing markets in dense metropolitan areas are shaped by income inequality, regulatory frameworks, and demographic pressures. This project uses **NYC housing data** to explore:  

- How property values are distributed across boroughs.  
- The relationship between **property size, price, and socioeconomic context**.  
- Whether urban constraints (density, land-use policy) drive smaller but higher-priced properties in Manhattan.  

The analysis integrates **visual insights** with a **theoretical perspective** to better understand why Manhattan exhibits such a premium relative to other boroughs.

---

## ⚙️ Methodology

### 1. Dataset
- **Source:** `NY-House-Dataset.csv`  
- **Variables Included:**  
  - `Price`: Property value in USD  
  - `Sqft`: Property size in square feet  
  - `Bedrooms`: Number of bedrooms  
  - `Borough`: Categorical (Manhattan, Brooklyn, Queens, Bronx, Staten Island)  

### 2. Tools & Workflow
- **Language:** R (Quarto / R Markdown)  
- **Libraries:**  
  - `tidyverse` → for cleaning and transforming data  
  - `ggplot2` → for scatter plots, heatmaps, and treemaps  
  - `dplyr` → for grouping and aggregation  
- **Workflow:**  
  1. Imported and cleaned raw dataset.  
  2. Conducted **univariate analysis** (price distributions, bedroom counts).  
  3. Conducted **bivariate analysis** (price vs. sqft, bedrooms vs. borough).  
  4. Mapped **spatial distributions** to show clustering of high-value properties.  
  5. Interpreted findings with reference to socioeconomic literature.  

### 3. Visualizations
- **Heatmap:** Highlighted concentration of property prices across boroughs.  
- **Scatter Plot:** Examined relationship between property size (sqft) and price.  
- **Treemap:** Showed bedroom distribution across NYC housing stock.  
- **Boxplots (extended analysis):** Compared price distributions across boroughs to visualize premium pricing in Manhattan.  

---

## 📊 Results & Insights

### Spatial Distribution
- **Manhattan:**  
  - Densest cluster of high-value properties.  
  - Prices reflect **income concentration, scarcity of land, and restrictive zoning laws**.  
- **Other Boroughs:**  
  - Brooklyn and Queens had more mid-range values, balancing affordability with accessibility.  
  - Bronx and Staten Island had the lowest prices, consistent with lower income levels and lower demand.

### Property Characteristics
- **Size vs. Price:**  
  - Majority of properties: under **10,000 sqft** and priced below **20M USD**.  
  - Outliers: luxury estates exceeding **40M USD**, primarily in Manhattan.  
  - Scatter plot revealed **nonlinear scaling**: price does not rise proportionally with size — location and neighborhood effects dominate.  
- **Bedrooms:**  
  - Most homes had **≤ 4 bedrooms**, reflecting **urban density**.  
  - Treemap analysis confirmed that larger homes were disproportionately located outside Manhattan, while Manhattan offered smaller but higher-priced units.

### Correlations with Socioeconomic Factors
- **Population Density:** Higher density in Manhattan correlated with higher price concentration.  
- **Income Levels:** Wealth concentration in Manhattan supports premium pricing.  
- **Land-Use Policy:** Restrictive zoning increases scarcity of larger properties, amplifying the price of smaller units.  

### Broader Interpretation
- Findings are consistent with **Donald & Winkler (2002)**, who showed that **demographic and economic shifts strongly shape metropolitan housing prices**.  
- NYC reflects this dynamic: high-income, high-density areas show inflated prices, while peripheral areas remain relatively affordable.  

### 🔑 Key Insight
NYC’s housing prices are not simply a function of property size — they are shaped by **urban economics**:  
- Manhattan’s premium results from a **trifecta of income concentration, density, and zoning restrictions**.  
- Smaller units in Manhattan are often **more expensive than larger units elsewhere**, highlighting the dominance of **location over physical attributes**.  
- Socioeconomic and policy factors combine to explain why NYC is one of the world’s most expensive and spatially unequal housing markets. 

