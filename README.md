# Data-Visualization-Project-using-Tableau

## About The Project

Simply presenting raw data from the World Happiness Report fails to convey the complex relationships between factors like GDP, social support, and a nation's happiness. This project aimed to translate these numerical relationships into accessible visual patterns.

The primary goal was to compare different visualization techniques to identify the most effective approach for answering the central research question. The final selected visualization is an interactive Tableau dashboard designed to reveal and compare the relative influence of various factors on happiness across different geographical regions.
Research Question

> "Which factors have the highest influence on the happiness score across different regions for the period 2005-2022?"

## How to View the Visualization

The interactive dashboard is a Tableau Packaged Workbook (.twbx). It cannot be viewed directly on GitHub.

> If you have Tableau Desktop, you can download and open the .twbx file directly.

## Dataset
        

  Source: World Happiness Report (2005-Present) on Kaggle

  Description: The dataset aggregates annual data for numerous countries from 2005 to 2022, primarily based on the Gallup World Poll.

  Key Features Analyzed:

- Life Ladder (Happiness Score)

- GDP Per Capita

- Social Support

- Healthy Life Expectancy

- Freedom to Make Life Choices

- Perceptions of Corruption

- Positive and Negative Affect

## Methodology and Key Findings
### Methodology

To determine the "influence" of each factor, the data was first grouped by region. For each region, a linear regression model was built using standardized features. The relative importance of each factor was then computed as a percentage of the total absolute impact of all factors. This approach accounts for interdependencies between variables, providing a more robust measure of influence than simple pairwise correlations.

### Key Findings

The analysis revealed significant regional differences in the drivers of happiness:

- Economic factors like Log GDP Per Capita are extremely influential in regions like East Asia (38%) and Central & Eastern Europe (35%), but surprisingly insignificant in Western Europe (2%).

- In Western Europe, happiness is most strongly shaped by Negative Affect (25%) and Perceptions of Corruption (24%).

- Social Support is a crucial driver in the Commonwealth of Independent States (22%) and Southeast Asia (22%).

- Affective variables (Positive/Negative Affect) play a major role in Latin America & Caribbean and the Middle East & North Africa.
