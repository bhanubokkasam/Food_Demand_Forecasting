# Food Demand Forecasting( RMSLE 50.0875283203)
### Train.csv
id: Unique ID
week: Week No
center_id: Unique ID for fulfillment center
meal_id: Unique ID for Meal
checkout_price: Final price including discount, taxes & delivery charges
base_price: Base price of the meal
emailer_for_promotion: Emailer sent for promotion of meal
homepage_featured: Meal featured at homepage
num_orders: Orders Count

### Fullfillment_center_info.csv
center_id: Unique ID for fulfillment center (Common in Train.csv)
city_code: Unique code for city
region_code: Unique code for region
center_type: Anonymized center type
op_area: Area of operation (in km^2)

### Meal.csv
meal_id: Unique ID for the meal (Common in Train.csv)
category: Type of meal (beverages/snacks/soups….)
cuisine: Meal cuisine (Indian/Italian/…)

# Problem Statement
<hr>

Your client is a meal delivery company which operates in multiple cities. They have various fulfillment centers in these cities for dispatching meal orders to their customers. The client wants you to help these centers with demand forecasting for upcoming weeks so that these centers will plan the stock of raw materials accordingly.

The replenishment of majority of raw materials is done on weekly basis and since the raw material is perishable, the procurement planning is of utmost importance. Secondly, staffing of the centers is also one area wherein accurate demand forecasts are really helpful. Given the following information, the task is to predict the demand for the next 10 weeks (Weeks: 146-155) for the center-meal combinations in the test set:  

Historical data of demand for a product-center combination (Weeks: 1 to 145)
Product(Meal) features such as category, sub-category, current price and discount
Information for fulfillment center like center area, city information etc.

Click Here for complete problem statement: https://datahack.analyticsvidhya.com/contest/genpact-machine-learning-hackathon-1/#ProblemStatement
 
