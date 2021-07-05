# Power-BI-projects
This repository stores the projects done with Power BI:
- Finnish drink market analysis:
+ Web scrapping: Goal: collect all details of Finnish drink on Foodie.fi (Product name, price/unit, price/liter, image, description, ingredients, manufacturer). This pbix is example for plant-based products. Procedure 3 steps:
          1. Scrape main link of Foodie plant-based category using Get Data --> Other --> Web --> "Add Tables Using Examples" --> Select CSS for basic Product information: Name, price, image, link of product (this link contains other detailed information, similarly to when we click the product on main category page).
          2. Using a product's link, we create sample table using same techniques as step 1. targeting the rest details (description, ingredients, manufactures, origin, ratings...). Make a parameter with this link, create a function.
          3. Invoke custome function to all other links. Now we have a table with all information wanted.

+ Visual dashboard: Goal: market segmentation to have general view of the drink, in this sample, juices. Viz chart used: Sankey box, donut chart, table

- Supply Chain Analysis: personalized template based on the template of MSFT. Viz chart: key influencers, tree decomposition, donut chart, funnel, stacked bar chart. Creating tooltip to add more details.




