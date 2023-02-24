# U.S. Housing Index NSA Analysis: Project Overview
* Analyzed and manipulated over 100,000 housing entries using SQLite, ensuring high-quality data for analysis.
* Utilized Python to display the data on a bar chart and choropleth, providing an intuitive and informative visualization of the data.
* Identified key findings about housing prices for all states in the U.S., providing insights into the overall trends of the housing market.
* Designed an interactive dashboard using Tableau to showcase the key findings, enabling a user-friendly and visually appealing display of the data.
* **Coding Languages:** SQL, Python, Tableau
* **Main Packages:** pandas, matplotlib, plotly


## Description:
Because of my interest to travel around the world, I wanted to know and compare the housing prices of all the states in the U.S. I was able to get a dataset from the Federal Housing Finance Agency website (https://www.fhfa.gov/DataTools/Downloads/Pages/House-Price-Index-Datasets.aspx). 

## Filtering Data with SQL
* Filtered out unnecessary columns and grabbed the necessary state data values with SQL queries
* Calculated a table of the average housing prices per year
* Formed another table of the latest housing state data (Year = 2021, Period = 3)

## Plotting Data with Python
Using Python, I was able plot a bar chart of the housing prices for each state to display the least and most expensive states to live in the U.S.
![image](https://user-images.githubusercontent.com/43764400/147300499-2792d67e-9a8c-4309-ab9c-c159c41f1417.png)

I was also able to plot the above plot as a choropleth to visually see correlations between the housing prices and locations on the U.S.
![newplot](https://user-images.githubusercontent.com/43764400/147300519-3191a742-5bd6-4b61-8106-e367dce76ecd.png)

Finally, I created a fun animated bar chart of how the index nsa changed over time. However, it was too big to display on the github or on the Google Colab. If you run the code, it would take around 15 minutes to make and download. 

## Creating Dashboard with Tableau
Using Tableau, I was able to plot a choropleth, histogram of the distribution of housing prices, and the most and least expensive states in the United States. I created an interactive dashboard which allows the user to view the plots I just listed by different years and periods. Now, I could compare and contrast the previous years and periods to the current housing prices.
Tableau Link: https://public.tableau.com/app/profile/joshua.kim6929/viz/UnitedStatesIndexNSA/UnitedStatesIndexNSA

![United States Index NSA Dashboard](https://user-images.githubusercontent.com/43764400/150911568-6848464b-e888-4d12-95d2-baf4edef3982.png)


## What I Learned:
From a data analytical stand point, I was able to further expand my knowledge in filtering and adjusting datasets using SQL. Moreover, I was able to further my knowledge in creating nice bar charts and choropleths with Python and Tableau to help myself in future data analysis projects. Due to the distribution from my analysis, I am now planning on exploring moving to Texas, Michigan, or any of the central states for cheaper housing prices in the future. Overall, this was a fun data analysis project and hopefully a beneficial reference for future projects.
