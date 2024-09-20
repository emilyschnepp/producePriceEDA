<h1>Exploratory Data Analysis of Produce Prices</h1>
<h2>Overview</h2>
<p>An exploratory data analysis on the 'produce price index' dataset. The purpose of the project is to explore trends in produce prices between the years 1999 and 2019.</p>
<p>This is an exploratory data analysis on the 'produce price index' dataset. The information contained within the dataset comes from four major cities (Atlanta, Chicago, Los Angeles, and New York) over the span of 20 years (1999-2019).</p>
Aside from the four city retail price columns, the other columns in the dataset include: 
• Product Name - The name of the product, examples provided below. 
• Date - The date when the pricing information was obtained.
• Farm Price - The price the retail product sells for at the farm. 
• Average Spread - Percentage indicating markup from farm price to retail price. 
The dataset includes 22 diverse products such as broccoli crowns, carrots, and Thompson grapes. 
The dataset was obtained from Kaggle, or can be obtained directly from the source at http://www.producepriceindex.com
<h2>Project Summary</h2>
<h3>Coding Languages</h3>
Python
<h3>Libraries</h3>
pandas, seaborn, matplotlib, statsmodels.
<h3>Data Cleaning</h3>
• Checked for null and duplicate values (51 duplicate values were dropped). 
• Renamed columns for readability
• Converted columns with currency and percentages from strings to numeric. 
• Identified cities with zero-dollar products and imputed the mean to price the products. 
• The decision to impute the mean rather than drop the columns was made due to the amount of zero values in the dataset totaling more than 10% of the dataset, which could have a big impact. By imputing the mean we are still able to take advantage of the rest of the data in those rows. 
• Located and removed outliers.
<h3>Analysis Types</h3>
Exploratory Data Analysis and Seasonality
<h3>Visualizations</h3>
Types of visualizations include: 
• boxplot of retail and farm prices with all outliers
• boxplot of price by product with extreme outliers removed. 
• correlation matrix of all numeric variables in dataframe. 
• line chart of average spread (or markup) by year. 
• bar charts of most expensive products in the summer per the four major metro areas (NY, LA, Atlanta, Chicago).
• bar charts of produce with the least and most markup on average. 
• seasonal price trends line charts showing the 5 most and 5 least expensive products. 
• dual axis line chart comparing farm price vs retail price volatility over time. 
• autocorrelation plot of farm price - shows how current pricing relates to past pricing.
• farm decomposition - decomposing the farm price into individual components to identify underlying trends in the data. 
<h3>Key Findings</h3>
New York produce prices are typically the highest.

Despite significant reduction in markup since 2011, produce markup between the farmer and the grocer is still around 200%.
This analysis was meant to provide a glimpse into the world of 'produce prices' from 1999 to 2019. Here are the key takeaways:
•	Prior to 2011 markup on produce hovered between 300 and 350%.
•	Prices tend to vary between cities, which points to some pricing factors being tied to geographic location.
•	Produce is almost always most expensive in New York.
•	Even with a near 50% reduction in markup on produce since 2011, markup still averages around 200%.
•	Consumers can use these findings to make more informed purchases, especially with an understanding of how seasonality and regionality impact prices.
•	These findings could be employed by retailers to drive informed decisions regarding pricing strategy and promotions.
•	Farm Price Decomposition: Farm prices have steadily increased over time, showing regular seasonal cycles, with an unusual price spike around 2012.
•	Autocorrelation of Farm Price: Farm prices are strongly related to recent prices, but this relationship weakens over time.  
•	Farm Price vs. Retail Price Volatility Over Time: Farm prices have risen steadily, but retail price volatility is much more unpredictable, with no clear link between the two trends. 

<h2>Future Improvements</h2>
• Build interactive dashboard
• Use machine learning to predict produce prices.
