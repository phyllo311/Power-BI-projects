# Power-BI-projects
This repository stores the projects done with Power BI:
- Finnish drink data collection: Goal: collect all details of Finnish drink on Foodie.fi (Product name, price/unit, price/liter, image, description, ingredients, manufacturer). File "Plant-based drink" is example for plant-based products. Procedure 3 steps:
          1. Scrape main link of Foodie plant-based category using Get Data --> Other --> Web --> "Add Tables Using Examples" --> Select CSS for basic Product information: Name, price, image, link of product (this link contains other detailed information, similarly to when we click the product on main category page).
          2. Using a product's link, we create sample table using same techniques as step 1. targeting the rest details (description, ingredients, manufactures, origin, ratings...). Make a parameter with this link, create a function.
          3. Invoke custome function to all other links. Now we have a table with all information wanted.

- Visual dashboards: 
1. Drink market analysis: Create dashboard highlighting market segmentation of drink (juices). Viz chart used: Sankey box, donut chart, table. File "Drink manufacturer" is example for juices.
2. Supply Chain Analysis: personalized template based on the template of MSFT. Viz chart: key influencers, tree decomposition, donut chart, funnel, stacked bar chart. Creating tooltip to add more details.
3. Telco churn analysis: data https://www.kaggle.com/blastchar/telco-customer-churn. Goal: Experimenting new visual analytics tool of Power BI.


@Disclosure: The template and data involves in this repository are for personal experiementing and exhibition of Power BI skills. Much of the information is derived directly from available open sources, which might not represent the industrial views. Any attempt to act upon the conclusions draw from these visual dashboards are therefore needed careful considerations.
