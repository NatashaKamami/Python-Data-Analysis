# World Happiness Project

## Project Overview

This project explores global happiness scores over time and analyzes various factors that influence the happiness levels of countries across different regions. The analysis leverages the *World Happiness Report*, which provides detailed data about factors such as GDP per capita, social support, health (life expectancy), freedom to make life choices, generosity, and perceptions of corruption. Using this data, the project visualizes trends and distributions in happiness scores, identifies the happiest and saddest countries, and highlights regional variations. Interactive visualizations and insights help explain the underlying patterns and provide valuable context to understand what drives happiness in different parts of the world.

## Dataset

The dataset used in this project is sourced from the *World Happiness Report*. It contains information on various countries and their happiness scores, along with several contributing factors such as economic conditions, social support, and political freedom. The dataset spans several years, and each country is associated with a happiness score that reflects its citizens' overall well-being.

### Dataset Columns:
1. **Country**: The name of the country.
2. **Region**: The geographical region the country belongs to (e.g., Western Europe, Sub-Saharan Africa).
3. **reset filters**: An irrelevant column which is dropped during data cleaning.
4. **Year**: The year of the reported happiness data.
5. **Corruption Rank**: The country's ranking in terms of corruption levels.
6. **Economy (GDP per Capita)**: A measure of the country's economic performance based on GDP per capita.
7. **Economy Rank**: The rank of the country based on GDP per capita.
8. **Freedom Rank**: The country's rank in terms of the freedom its citizens have to make life choices.
9. **Freedom to make life choices**: A score representing the freedom people have to make life choices in the country.
10. **Generosity**: A measure of the generosity of the country's population.
11. **Generosity Rank**: The rank of the country based on generosity.
12. **Happiness Rank**: The rank of the country based on the happiness score.
13. **Happiness Score**: The country's happiness score, a measure of the well-being of its citizens.
14. **Health (Life Expectancy)**: The average life expectancy in the country.
15. **Health Rank**: The rank of the country based on life expectancy.
16. **Perception of Corruption**: The perceived level of corruption in the country.
17. **Social Support**: The level of social support available to individuals in the country.
18. **Social Support Rank**: The rank of the country based on social support.

## Data Cleaning

Before proceeding with the analysis, the dataset undergoes several cleaning steps:
1. **Handling Missing Values**: Columns with missing data are identified, and any rows with null values are dropped.
2. **Dropping Unnecessary Columns**: The column `reset filters` is dropped as it does not contribute to the analysis.
3. **Datetime Conversion**: The `Year` column is converted to a datetime format for easier analysis.

## Analysis

The main objective of the analysis is to explore trends, distributions, and relationships in the data.

### 1. Happiness Trends Over Time by Region
The happiness scores for each region are tracked over the years using line plots.

**Insights**:
- Western Europe shows a steady increase in happiness over the years, with countries like Finland, Denmark, and Iceland consistently ranking high.
- Sub-Saharan Africa exhibits more fluctuations in happiness scores, possibly due to economic challenges, political instability, and social issues. However, there has been some improvement in recent years.
- Australia and New Zealand have maintained high happiness levels throughout the years, attributed to strong economic performance, healthcare, and social support systems.
  
### 2. Regional Comparisons of Happiness Scores
A box plot is used to visualize the distribution of happiness scores for each region. This helps in understanding the spread of happiness scores and the impact of outliers. The regional ranking is discussed, with particular attention given to Western Europe’s relatively high ranking in terms of happy countries, but lower regional ranking.

**Insights**:
- While Western Europe contains several high-ranking countries such as Finland and Denmark, the overall regional happiness score is affected by countries with lower scores. This results in the region ranking third globally, despite having many of the world’s happiest countries.
- North America is consistently high, particularly driven by the United States and Canada.
- Latin America shows a relatively high degree of variation in happiness scores, with countries like Costa Rica ranking higher due to better social support systems.
  
### 3. Top Happiest and Saddest Countries
The top 10 happiest and saddest countries are extracted, and a bar plot visualizes their happiness scores.

**Insights**:
- Countries like Finland, Denmark, Norway, and Switzerland consistently rank among the happiest countries, with factors such as strong economies, quality of life, work-life balance, social trust, and environmental sustainability contributing to their success.
- Countries like the Central African Republic, South Sudan, and Syria have some of the lowest happiness scores, primarily due to political instability, war, conflicts, and economic hardship. 

### 4. Correlation Between Happiness and Contributing Factors
A correlation matrix is computed to understand how different factors such as GDP, social support, and life expectancy correlate with happiness in the least happy countries. The matrix is visualized using a heatmap to show the strength of relationships between the variables.

**Insights**:
- GDP per capita shows a strong positive correlation with happiness, meaning wealthier countries tend to have higher levels of happiness.
- Social Support and Life Expectancy are also strongly correlated with happiness, highliting the importance of healthcare systems and social infrastructure in improving quality of life.
- Generosity shows a moderate positive correlation with happiness, suggesting that countries with higher levels of generosity (such as in the Nordic countries) tend to report higher happiness levels.
  
### 5. Geographical Happiness Distribution
A geographical heatmap is created to visualize the happiness scores for different countries across the world, providing a global perspective on happiness.

**Insights**:
- Northern Europe is consistently the happiest region, with countries like Finland, Denmark, and Iceland leading the global rankings.
- Sub-Saharan Africa and parts of South Asia display lower average happiness scores, often due to socio-economic challenges, political instability, and lack of access to healthcare and education.
- South America shows a mixture of high and low happiness scores, with countries like Costa Rica and Brazil at opposing ends of the happiness spectrum, demonstrating the influence of economic factors and social support systems.

## Conclusion

This project offers valuable insights into global happiness trends, highlighting regional variations, the factors that influence happiness, and the correlation between economic, social, and political factors. By visualizing these trends and providing detailed analysis, the project aims to deepen the understanding of global happiness patterns and offer potential avenues for improving well-being worldwide.


