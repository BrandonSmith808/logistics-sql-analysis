# logistics-sql-analysis

Project Title:
  Logistics SQL Analysis

Project Description:
  SQL analysis of a logistics and trucking dataset, exploring profitability, driver efficiency, and truck performance

Tools Used: 
  SQL through Microsoft SQL server, VS Studio Code, PowerBI

Dataset:
  Logistics Operations Database
  3-Year Trucking Operations (2022-2024)
  https://www.kaggle.com/datasets/yogape/logistics-operations-database

Questions Answered:
  1. What is the total revenue, operational costs, and gross profit of our company?
  2. Are our drivers actually working to standard and working efficiently?
  3. How efficient are our trucks running?

Key Findings:
  Gross Profit Analysis:
    Gross profit margin is at 60.4% netting $158,549,063.19 after fuel purchases, maintenance costs, and incident costs. 
    However, other expenses such as driver salaries, insurance, truck payments, etc, not included as data is not present. 
    Higher Fuel and maintenance costs thought to be caused by driver habits and/or truck make and model year but were not definitive indicators.
    
  Driver Efficiency:
    Drivers overall perform similarly other than two outliers based on average on time delivery.
     -Outliers: Lowest Performer: Mary Wilson (37% on time), Standard  Performer: Jessica Johnson (50% on time)
    Fleet average on time delivery is at 45%. Analysis is needed to find if this is a systemic or individual issue.
    Idle hours similar across all drivers. Analysis focused on driver habits and route conditions needed to identify better habits/routes.

  Truck Analysis:
    Maintenance costs below industry standard across fleet.
    Model year of trucks did not seem to definitively determine future potential maintenance costs or downtimes. 
    Truck makes were analyzed as well to determine potential inefficient makes. Results varied with model year and make.
      -  Volvo generally a bad performing make, yet 2019 model year had best performance across entire fleet. Further analysis needed.
    Individual truck condition or acquisition mileage may be better for identifying depreciating trucks.
    Full cost analysis is limited due to missing acquisition and depreciation data. 

  Files in this Repository:
   01_gross_profit_analysis - Data showing total revenue and costs to identify gross profit. Excludes certain expenses due to missing data.
   02_driver_efficiency_analysis - Data showing driver performance. Showcases average MPG, idle hours, on time delivery of fleet and individual drivers.
   03_truck_efficiency_analysis - Data showing truck efficiency, Showcases average downtime hours per trip and maintenance cost per mile for each make and model year.






        
