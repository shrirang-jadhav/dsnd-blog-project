# DSND - Writing a blog-post Project

### Project Motivation:
This is part of portfolio projects for DSND.

Key objective of this projec is to write a blog which will answer few business questions for a non-technical audience.
Hence a dataset which will not only allow to perform detailed EDA but also allow to possibly build a ML model to answer one of questions, was required.
Considering this criterion, "Seattle Airbnb Open Data" available on kaggle seemed to qualify for this analysis.


Hence, we are using "Seattle Airbnb Open Data" available on Kaggle for this Analysis.
In this analysis, we focus on answering following questions :

1. What is the trend wrt Availability of listing on Airbnb in different Neighbourhoods of Seattle ?
2. What is the trend wrt listing-prices on Airbnb in different Neighbourhoods of Seattle ?
3. Do we see Seasonality as well as Day-of-week influencing Prices ?
4. Can we determine important factors which influence listing-price the most on Airbnb ?



### Important Files:
1. `data/listings.csv` : airbnb seattle listings details. this file has detailed information about the listings such as property details & description, host details, neighborhood, pricing, availability, reviews, listing policies,
2. `data/calendar.csv` : Date wise listing info wrt price, availability of airbnb seattle listings for one entire year.
3. `data/reviews.csv`  : listing-reviews details for airbnb seattle listings. this data has detailed info of listings reviews, date of review, reviewer_id, review description.
3. `code/DSND-blog-project.ipynb` : python3 code to perform EDA as well as model building exercise to find answers to quesions listed above. Using above mentioned data files with this notebook, one can replicate the analysis done for this project.

### Results and Summary:

Following is summary for each of questions listed above
1. Availability of listing does show trend of few neghbourhoods offering as low as 2 listing and also few one offering as high as ~380 listing
2. With seattle only, there is wide spread of listing-prices from $67 to $230 depending on a neighborhood
3. Month wise as well as weekday wise seasonality exist which can be seen by variation in pricess over different months / weekdays 
4. We can successfully identify important factors which influence listing-price using ML techniques


The main findings of the code can be found at this post - 
https://medium.com/@shrirang16/top-things-to-know-while-you-plan-to-become-airbnb-host-in-seattle-fdce48730882?source=friends_link&sk=85a74c5674e7cb4631ec675aac7aa659

### Libraries used from python3
- pandas
- matplotlib
- seaborn
- sklearn

