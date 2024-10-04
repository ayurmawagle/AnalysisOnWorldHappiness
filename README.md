# The Pursuit of Happiness: Insights from World Happiness Report 2024

World Happiness Repository contains a comprehensive analysis of the World Happiness Report 2024 using Microsoft Power BI. The data for this project was sourced from the World Happiness Report 2024, published by the Wellbeing Research Centre at the University of Oxford. 

## Data Preparation, Cleaning and Transformation:
1. Imported the data into Power Query Editor.
2. Removed unnecessary columns such as upper whisker and lower whisker of happiness score, dystopia/residual, and positive and negative affect.
3. Removed duplicate entries and missing values.
4. Renamed columns for clarity (Eg: "Ladder score" to "Happiness Score")
5. Checked the data types for each column and their column profile to check distribution and errors.
6. Created a calculated column for categorising countries based on happiness score where;
   - Happiness score more than or equal to 7 means "Very Happy"
   - Happiness score between 4.1 to 6.9 means "Moderately Happy"
   - Happiness score less than or equal to 4 means "Less Happy"
7. Filters and slicers created to make the visuals interactive based on region and happiness category.

## Data Visualisation:

### 1. Global Happiness Overview:
- Card and gauge visual created for happiness score, social support score, freedom to make life decision score and GDP per capita.
- Color gradient global map to visually identify happiest to unhappiest countries.

### 2. Top 10 Happiest and Unhappiest Country:
- Created an interactive bar chart that displays the top 10 happiest countries by default, featuring a slider that allows users to seamlessly transition to view the 10 countries with the lowest happiness scores.

### 3. Social Support and Wellbeing:
- Comparison of healthy life expectancy and social support based on world regions.

### 4. Correlation Analysis:
- A scatter plot illustrating the correlation between national happiness scores and GDP per capita, revealing potential economic influences on overall well-being across countries.

### 5. Key Influencers:
- The key influencers chart ranking the key influencers of happiness score.
- Based on the aggregated data on freedom, generosity, healthy life expectancy, GDP per capita, social support, and perception of corruption scores.

## Key Findings:
- Regional disparities in happiness is evident, with North America and Australia reporting the highest happiness scores, while South Asia has the lowest.
- Finland is celebrated as the happiest country in the world, while Afghanistan ranks as the unhappiest, reflecting contrast in social stability and overall well-being.
- The regional bar chart reveals a positive correlation between social support and healthy life expectancy, suggesting that as social support increases, so does life expectancy across different regions.
- The scatter plot reveals a strong positive correlation between GDP and happiness scores across countries, with a clear linear trend indicating that higher GDP generally corresponds to increased happiness.
- However, notable outliers such as Lebanon, Mozambique, Venezuela, Afghanistan, and Hong Kong deviate from this trend, suggesting that factors beyond economic prosperity significantly influence happiness in these nations
- Key influencers such as social support and healthy life expectancy can be seen.
- Happiness score is most likely to be high where GDP is greater than 1.84 and social support is greater than 1.35.

## Conclusion:
This Power BI project on the World Happiness Report offers valuable insights into global well-being:
- Utilised a comprehensive dataset covering happiness scores and related factors across nations.
- Rigorous data preparation, cleaning, and transformation processes ensured high-quality analysis.
- Interactive visualizations, including bar charts, scatter plots, and key influencer analyses, provide an engaging exploration of happiness trends.

This analysis offers a data-driven perspective on happiness, providing valuable insights on Global well-being.
   
