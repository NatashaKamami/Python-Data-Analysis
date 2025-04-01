# Food Carbon Footprint Project

## Overview
This project analyzes the carbon footprint of food consumption across different countries. The analysis provides insights into how food consumption patterns influence CO2 emissions, and the impact of animal-based and non-animal-based products on global carbon emissions. The findings from this analysis can help policymakers and environmental groups implement more sustainable dietary and agricultural practices.

## Dataset
The dataset used in this project includes the following columns:
- **Country:** The country where the food consumption data was recorded.
- **Food Category:** The type of food consumed (e.g., beef, poultry, dairy, vegetables, etc.).
- **Consumption:** The amount of food consumed per person (kg/person/year).
- **CO2 Emission:** The carbon footprint of the food consumption per person (kg CO2/person/year).

## Project Workflow

### 1. Analyzing CO2 Emissions by Food Category in East Africa
- Filtered the dataset to include five East African countries: Kenya, Uganda, Tanzania, Rwanda, and Ethiopia.
- Computed the average CO2 emissions per person for different food categories.
- Visualized the results using a bar chart to identify the biggest contributors to emissions in the 5 countries.

**Key Findings:** Beef, dairy, and lamb & goat were identified as the highest contributors to emissions in East Africa. This suggests that policies aimed at reducing reliance on these foods or encouraging sustainable livestock practices could help mitigate emissions.

### 2. Highlighting the Difference Between Consumption and Emissions in Lamb & Goat
- Focused on lamb & goat consumption in East African countries.
- Compared the CO2 emissions and consumption levels across the countries.
- Used a grouped bar chart to visualize these metrics.
  
**Key Findings:** Rwanda and Kenya showed the highest consumption levels. However, the emissions did not scale proportionally, suggesting efficient production practices in the region.

### 3. Comparing Animal vs. Non-Animal Product Consumption and CO2 Emissions
- Categorized food into **Animal** and **Non-Animal** groups.
- Aggregated total emissions and consumption per category.
- Visualized the data using a bar chart.

**Key Findings:** Non-animal products were consumed in higher quantities but had significantly lower CO2 emissions. This highlights the environmental benefits of plant-based diets.

### 4. Mapping Global CO2 Emissions from Beef Consumption
- Extracted CO2 emissions related to beef consumption globally.
- Merged the data with a world map GeoJSON file to visualize emissions geographically.

**Key Findings:** South America, North America, and Australia had the highest per capita beef-related emissions. This aligns with the large-scale cattle farming practices in these regions.

### 5. Box Plot Analysis of CO2 Emissions by Food Category
- Created a box plot to show the distribution of emissions for each food category.
- Highlighted outliers in different food groups, such as rice in Bangladesh and beef in Brazil and Argentina.

**Key Findings:** Animal-based foods had higher emissions with significant variability across countries. Beef and dairy were the most impactful categories.

### 6. Identifying the Top 10 Countries with the Highest Food-Related CO2 Emissions
- Computed total CO2 emissions per country.
- Extracted the top 10 countries based on total emissions.
- Created a bar chart to visualize country-wise emissions and their food category contributions.

**Key Findings:** Argentina had the highest emissions, primarily from beef. Iceland showed high emissions from lamb & goat due to traditional farming practices.

## Recommendations
1. Encourage plant-based diets to reduce emissions.
2. Implement sustainable livestock farming practices to improve efficiency.
3. Develop policies that promote alternative protein sources to mitigate food-related CO2 emissions.

## Dependencies
- **Pandas**: Data manipulation and analysis.
- **Seaborn & Matplotlib**: Data visualization.
- **GeoPandas**: Geospatial analysis for mapping CO2 emissions.
- **Plotly**: Interactive visualizations for deeper insights.


