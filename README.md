<h1>Exploratory Data Analysis of Produce Prices</h1>
<h2>Overview</h2>
<p>An exploratory data analysis of the 'produce price index' dataset focusing on trends in produce prices across four cities (Atlanta, Chicago, Los Angeles, and New York) over a 20-year span between 1999 and 2019.</p>
Aside from the four city retail price columns, the other columns in the dataset include: <br>
• Product Name - The name of the product, examples provided below. <br>
• Date - The date when the pricing information was obtained. <br>
• Farm Price - The price the retail product sells for at the farm. <br>
• Average Spread - Percentage indicating markup from farm price to retail price. <br><br>
The dataset includes 22 diverse products such as broccoli crowns, carrots, and Thompson grapes. <br><br>
The dataset was obtained from Kaggle, or can be obtained directly from the source at http://www.producepriceindex.com
<h2>Project Summary</h2>
<h3>Coding Languages</h3>
• Python
<h3>Libraries</h3>
• pandas <br>
• seaborn <br>
• matplotlib <br>
• statsmodels.
<h3>Data Cleaning</h3>
• Checked for null and duplicate values (51 duplicate values were dropped). <br>
• Renamed columns for readability <br>
• Converted columns with currency and percentages from strings to numeric. <br>
• Identified cities with zero-dollar products and imputed the mean to price the products. <br>
• The decision to impute the mean, rather than drop the columns with zero values, was made because over 10% of the dataset contained zero values. Imputing allowed the retention of more data for analysis.<br>
• Located and removed outliers.
<h3>Analysis Types</h3>
• Exploratory Data Analysis 
• Seasonality
<h3>Visualizations</h3>
Types of visualizations include: <br>
• boxplot of retail and farm prices with all outliers<br>
• boxplot of price by product with extreme outliers removed.<br> 
• correlation matrix of all numeric variables in dataframe.<br>
• line chart of average spread (or markup) by year.<br>
• bar charts of most expensive products in the summer per the four major metro areas (NY, LA, Atlanta, Chicago).<br>
• bar charts of produce with the least and most markup on average.<br>
• seasonal price trends line charts showing the 5 most and 5 least expensive products.<br> 
• dual axis line chart comparing farm price vs retail price volatility over time.<br>
• autocorrelation plot of farm price - shows how current pricing relates to past pricing.<br>
• farm decomposition - decomposing the farm price into individual components to identify underlying trends in the data. 
<h3>Key Findings</h3>
This analysis was meant to provide a glimpse into the world of 'produce prices' from 1999 to 2019. Here are the key takeaways:<br><br>
• Despite significant reduction in markup since 2011, produce markup between the farmer and the grocer is still around 200%.<br>
•	Prior to 2011 markup on produce hovered between 300 and 350%.<br>
•	Produce prices are almost always highest in New York, and prices tend to vary between cities, pointing to geographic location as a key factor in pricing.
•	Produce is almost always most expensive in New York.<br>
•	Even with a near 50% reduction in markup on produce since 2011, markup still averages around 200%.<br>
•	Consumers can use these findings to make more informed purchases, especially with an understanding of how seasonality and regionality impact prices.<br>
•	These findings could be employed by retailers to drive informed decisions regarding pricing strategy and promotions.<br>
•	Farm prices have steadily increased over time, showing regular seasonal cycles, with an unusual price spike around 2012.<br>
•	Farm prices are strongly related to recent prices, but this relationship weakens over time.<br>
•	Farm prices have risen steadily, but retail price volatility is much more unpredictable, with no clear link between the two trends. 
<h2>Future Improvements</h2>
• Build interactive dashboard in Tableau for more advanced visualizations with filters.<br>
• Use machine learning to predict produce prices based on historical trends and seasonality. Such predictive analytics could provide valuable insights. 
