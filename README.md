# ETL_Project
EXTRACT
Datasets: 
1 - CSV from https://www.kaggle.com/chicago/chicago-food-inspections
2 – API - https://developers.google.com/places/web-service/supported_types

TRANSFORM
Create database in pandas and store CSV in MYSQL. Take out all facility types that are not restaurants (use group by to do that). 
Run API on second dataset using lat/lng as join from first dataset and store in Mongo (looking for Cuisine).

LOAD
Load combo database back into MySQL which will include column names – Name of restaurant, cuisine, address, , lat/lng, results of inspection, inspection ids, and risk and import the joined csv in Mongo. Then display the Restaurants and Ratings by rendering the data in front end using the Flask App and Pymongo module.

HTML ideas with three routes
First page/button – EXTRACT include steps above and screen shots/ go to the flask app and grab the application 
Second page/button – TRANSFORM include steps above and convert pandas to html
Third page/button – LOAD show the final results and the rendered Restaurants and its ratings from the flask app.





	




