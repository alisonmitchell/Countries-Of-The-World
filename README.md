# Countries of the World
The [Countries of the World](https://www.kaggle.com/fernandol/countries-of-the-world) dataset comprises [US Government data](http://gsociology.icaap.org/dataupload.html) from the [World Factbook](https://www.cia.gov/library/publications/resources/the-world-factbook/). The investigation focuses on GDP ($ per capita), Literacy (%) and Phones (per 1000) to test the hypothesis that there would be a significant positive relationship between these variables.

This notebook demonstrates Exploratory Data Analysis techniques learned on a face-to-face machine learning course and from various resources including blogs, tutorials, documentation and textbooks.

Importing and exploring the dataset using Pandas revealed issues for data cleaning including renaming of columns, changing data types from string to float, filling missing values, and removing spaces in the Region column. 

Visualisation using Matplotlib and Seaborn showed number of countries per region and a correlation heatmap showed strength of correlation between pairs of numerical variables (GDP and Phones, Literacy and Phones and GDP and Literacy). Boxplots visualised data distribution indicating how the values in the data were spread out for GDP per capita , Literacy (%) and Phones by Region and categorical plots were also used to show the relationship between a numerical and one or more categorical variables. Scatterplots highlighted the strongest (positive) correlation between GDP and Phones which could be seen even more clearly by fitting a linear regression model and plotting the resulting regression line. Other visualisations included bar charts, a frequency histogram and Kernel density estimation (KDE) plot to encode the density of observations on one axis with height along the other axis.

## Data source
[US Government data](http://gsociology.icaap.org/dataupload.html) from the [World Factbook](https://www.cia.gov/library/publications/resources/the-world-factbook/).

## Libraries
Numpy, Pandas, Matplotlib and Seaborn.