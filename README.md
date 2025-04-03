# Data-Visualisation-Empowering-Business-with-Effective-Insights
## Creating a visual of an online retail store which is performing well in the business to know the KPI of that Business
An online retail store has hired me as a consultant to review their data and provide insights that would be valuable to the **CEO** and **CMO** of the business. The business has been performing well and the management wants to analyse what the major contributing factors are to the revenue so they can strategically plan for next year.

The leadership was interested in viewing the metrics from both an operations and marketing perspective. Management also intended to expand the business and was interested in seeking guidance into areas that are performing well so they can keep a clear focus on what’s working. They would also like to view different metrics based on the demographic information that is available in the data.

### I have Created Few Questions after revewing Their data for CEO and CMO You Can Check Below
# Questions(KPI) of interest to the CEO 
*	Which region is generating the highest revenue, and which region is generating the lowest?
*	What is the monthly trend of revenue, which months have faced the biggest increase/decrease?
*	What is the monthly trend of revenue, which months have faced the biggest increase/decrease?
*	Which months generated the most revenue? Is there a seasonality in sales?

# Questions(KPI) of interest to the CMO 
*	What is the percentage of customers who are repeating their orders? Are they ordering the same products or different?
*	For the repeat customers, how long does it take for them to place the next order after being delivered the previous one?
*	What revenue is being generated from the customers who have ordered more than once?
*	Who are the customers that have repeated the most? How much are they contributing to revenue?

  ### After Revewing my questions(KPI) they decided to four questions that they want to know 
## Question 1
The CEO of the retail store was interested to view the time series of the revenue data for the year 2011 only. He would like to view granular data by looking into revenue for each month. The CEO was interested in viewing the seasonal trends and wants to dig deeper into why these trends occur. This analysis will be helpful for the CEO to forecast for the next year.

## Question 2
The CMO  was nterested in viewing the top 10 countries which were generating the highest revenue. Additionally, the CMO was also interested in viewing the quantity sold along with the revenue generated. The CMO did not want to have the United Kingdom in that visual.

## Question 3
The CMO of the online retail store wanted to view the information on the top 10 customers by revenue. He was interested in a visual that shows the greatest revenue generating customer at the start and gradually declines to the lower revenue generating customers. The CMO wanted to target the higher revenue generating customers and ensure that they remain satisfied with their products.

## Question 4
The CEO was looking to gain insights on the demand for their products. He wanted to look at all countries and see which regions have the greatest demand for their products. 

## Now the Task that I have done to the data 

### Data Cleaning and Transforming 
* First i had Cleaned the unwanted data means i have deleted the value which was not making any sense to the data e.g. in product there many product that are not in the coulmn i have cleaned them
* After that have set the unit price , **I Created a check where quantity should not be below 1 unit** and **Create a check that the Unit price should not be below $0**
* Created a new column of revenue by multiplying **Unit price** with **Quantity**

## Visualisation Part
* **Line Chart** : If you see the question 1 the chart that will fit is line chart , if any one talk about time series the line chart will be fit for that
* **Column Chart** : question 2 will be solved by column chart because here was two category that we have to show side by side country-wise 
* **Bar Chart** : Question 3 was the easy task we have to see the revenue of top 10 customer the bar chart will be fit for that
* **Map** : question 4 was all about the countries that showing higher revenue if we talk about Region wise things then easily we choose map to know abou
