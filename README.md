# Sales-Customer-Tableau-Dashboard

![image alt](https://github.com/SON-Abe/Sales-Customer-Tableau-Dashboard/blob/fa48fc9fe701d9327dedd20db34ff079278c5c56/Designs/Workflow.png)


To create a dashboard for a client I usually follow this diagram that seperates the work into stages. First stage is to collect the requirements of the client and create a user story for what data they want to display and how. Then From my story I determine what chart would best fit the needs of the client and draw mockups with usually 4 colors on display to keep it neat and simple. If the client approves I move onto the next stage.

## User Story
### Introduction
- The user story outlines a need for two dashboards, sales and customer dashboards, to help stakeholders, sales managers, and executives to analyze sales and customers data.

### Sales Dashboard
#### Dashboard Purpose
- The point of the sales dashboard is to display an overview of sales, profits, and quantity metrics measured year over year filtered by categories and location.


#### Key Requirements
##### KPI Overview
- Display a summary of total sales, profit, and quantity for the current and previous year.

The diagram I purpose to display the total sales, profit, quantity, and % difference over last year is a bans chart because I believe it displays the data in a simple and exact manner.

##### Sales Trends
- Display data for each KPI over the current and previous year on top of each other for easy comparison on a monthly basis.
- highlight highest and lowest performing months for easy recognition.

For displaying the key metrics on a monthly basis I chose sparkline for a simple and effective display.

##### Product Subcategory Comparison
- Compare sales performance by subcategory for the current and previous year.
- Include a comparison of sales with profit.

For these metrics I decided on a bar-in-bar diagram that would effectively measure current and previous year sales and profit by subcategories.

##### Weekly Trends for Sales & Profit
- Present weekly sales and profit data for current year.
- Display the average weekly values.
- Highlight weeks that are above and below the average to easily recognize sales and profit performance.

For these metrics I believe line charts would effectively display the data.

![image alt](https://github.com/SON-Abe/Sales-Customer-Tableau-Dashboard/blob/75524abd23aeabf229d58cc001c4d152975eed19/Designs/Sales.png)

- In the second stage I connect the data source to Tableau. I then open the different spreadsheets provided to me to see which of them are dimensions or facts. Facts will usually have IDs, dates, and measures, while files with dimensions usually contains data that can be used as good filters. Then I would connect the dimensions to the fact sheet to create the data model. I would look through the sheets to see if any field or tables need to be renamed then see if any field needs their type changed. I would then add a test worksheets to test the relationship between data sets.
- In the third stage I would start creating the calculated fields I would need to make the chart then format it to make it simple while displaying all necessary information in a clear and interactive manner.
- The fourth stage is where I would create the dashboard and add containers in the dashboard to hold all the charts and data in the way I want displayed. I would then format the dashboard by distributing the charts evenly giving space between them to feel less cluttered, format the colors into 4 options, have the charts fit "Entire View", add legends, add icons, and filters.

![image alt](https://github.com/SON-Abe/Sales-Customer-Tableau-Dashboard/blob/4738408d5736d21cb997c2de6a1f55c8cd3fbd3c/Tableau%20Sales%26Customer%20Dashboard%20pics/Consumer__Distribution%20Filter.png)

![image alt](https://github.com/SON-Abe/Sales-Customer-Tableau-Dashboard/blob/4738408d5736d21cb997c2de6a1f55c8cd3fbd3c/Tableau%20Sales%26Customer%20Dashboard%20pics/Consumer__Filter%20Category.png)

![image alt](https://github.com/SON-Abe/Sales-Customer-Tableau-Dashboard/blob/4738408d5736d21cb997c2de6a1f55c8cd3fbd3c/Tableau%20Sales%26Customer%20Dashboard%20pics/Consumer__Filter%20SubCategory.png)

![image alt](https://github.com/SON-Abe/Sales-Customer-Tableau-Dashboard/blob/4738408d5736d21cb997c2de6a1f55c8cd3fbd3c/Tableau%20Sales%26Customer%20Dashboard%20pics/Consumer__Filter%20Region.png)

![image alt](https://github.com/SON-Abe/Sales-Customer-Tableau-Dashboard/blob/4738408d5736d21cb997c2de6a1f55c8cd3fbd3c/Tableau%20Sales%26Customer%20Dashboard%20pics/Consumer__Filter%20State.png)

![image alt](https://github.com/SON-Abe/Sales-Customer-Tableau-Dashboard/blob/4738408d5736d21cb997c2de6a1f55c8cd3fbd3c/Tableau%20Sales%26Customer%20Dashboard%20pics/Consumer__Filter%20City.png)

![image alt](https://github.com/SON-Abe/Sales-Customer-Tableau-Dashboard/blob/4738408d5736d21cb997c2de6a1f55c8cd3fbd3c/Tableau%20Sales%26Customer%20Dashboard%20pics/Consumer__Filter%20Year.png)

![image alt](https://github.com/SON-Abe/Sales-Customer-Tableau-Dashboard/blob/4738408d5736d21cb997c2de6a1f55c8cd3fbd3c/Tableau%20Sales%26Customer%20Dashboard%20pics/Consumer__Top%20Consumer%20Filter.png)

![image alt](https://github.com/SON-Abe/Sales-Customer-Tableau-Dashboard/blob/4738408d5736d21cb997c2de6a1f55c8cd3fbd3c/Tableau%20Sales%26Customer%20Dashboard%20pics/Sales_KPI.png)

![image alt](https://github.com/SON-Abe/Sales-Customer-Tableau-Dashboard/blob/4738408d5736d21cb997c2de6a1f55c8cd3fbd3c/Tableau%20Sales%26Customer%20Dashboard%20pics/Sales_Filter%20Subcategory.png)

![image alt](https://github.com/SON-Abe/Sales-Customer-Tableau-Dashboard/blob/4738408d5736d21cb997c2de6a1f55c8cd3fbd3c/Tableau%20Sales%26Customer%20Dashboard%20pics/Sales_FilterTrends.png)
