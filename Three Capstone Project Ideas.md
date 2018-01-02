

# Capstone Project Ideas   headerStyle: { backgroundColor: '#fff', elevation:0 }
#                                                       Reza Taeb



## 1 - TED.com popular areas of talks
  
This idea is about the TED Talks videos. These datasets contain information about all audio-video recordings of TED Talks uploaded to the official TED.com website until September 21st, 2017. The TED main dataset contains information about all talks including number of views, number of comments, descriptions, speakers, titles, description, speaker occupation, number of speakers, duration, event (the place), published date, tags (themes associated with the talk), number of languages which the talk is available, ratings (a dictionary of various rating), related talks (a list of dictionary), the URL. 

Some of the primary questions and area of research that I am thinking about them right now are: 
* What is the most/least popular areas of talks ?
* Which combination of tags can attract the most viewers? (it can be investigated through the tags for each video)
* Predict the number of views for any new uploaded video based on tags/post date/duration/rating and etc. I think it’s better to just limit the prediction for specific time period (like 1st month of release) 

The results can be beneficial for different groups likes : lecturer and speakers, video sharing platforms, content makers, etc. They would figure out what combinations of topics can be more attractive to the viewers.  

Dataset Source : https://www.kaggle.com/rounakbanik/ted-talks



## 2 -  NYC Taxi Trips tips 

The second idea is analysis of trips in NYC based on the pick-up/drop-off of NYC  green and yellow taxis trips. The data which will be used was collected and provided to the NYC Taxi and Limousine Commission (TLC) by technology providers authorized under the Taxicab & Livery Passenger Enhancement Programs (TPEP/LPEP). The datasets are in CVS formats and are separated based on the time (monthly data) and Green or Yellow taxis. The columns of the datasets are: pickup_datetime, dropoff_datetime, passenger_count, pickup_longitude, pickup_latitude, dropoff_longitude, dropoff_latitude, ratecodeID, store and forward flag, payment type, fare amount, extra (surcharges), tip, and total amount. 	 
Some of the primary questions and area of research that I am interested in are: 
* Comprehensive Exploratory Data Analysis on data in order to recognize popular destinations (neighborhoods) in different times (hour and month). 
* Predicting the possible tip rate based on the features of a trip. (I am wondering whether It’s better to predict the “Rate” or just predicting if someone is going to tip or not).  

The output can be beneficial for both NYC visitors and NYC business owners (and future investors) including restaurants, cafes, hotels, hostels, etc . Taxi drivers can also adjust their routes in different hours. 


Dataset Source:http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml ) 


## 3 - Yelp review analysis 

This idea comes up from the challenge which is introduced by Yelp.com. In the challenge, the participants are invited to discover the most used words in both positive and negative reviews of different business categories (like restaurants, cafes, etc.). I want to dig in more and look at the most used words in reviews not only based on the business categories but also few other categories such as neighborhood, time, and rating. For instance, customers may expect a special service along with food when they are eating at the very high rating one and if the restaurant can not meet their expectations they express it in their reviews, however a customer may not expect something similar in low rating restaurants. Also the users are probably different in different neighbourhoods and it can show the priorities of different social classes.  Other variables like time can have remarkable influence on reviews too. 
The data is coming directly from yelp.com and is separated in several main JSON format data sets (business, reviews, user, check in, and tips). You can find all details of the datasets in the link below: 


Data Source: https://www.yelp.com/dataset/documentation/json


Some specific questions and area of research that coming to my mind right now are: 

* What are the most/least important priorities of customers for specific business based on type of service/rating/neighbourhood and etc. 
* How could number of check ins can affect the normal service of a business? In other words, do we notice a significant change in customer reviews when business is so quiet or so busy? 

*** For this idea, I am thinking of so many broad ideas. I highly appreciate if you share your thoughts on some possible specific ideas or direction. The dataset is so rich.  



The output can be useful for both business users, current business owners, and future business owners. The business owners can find out what the main priority of their customers can be based on the address, rating, and other factors. The customers can compare their own priorities with other user’s priorities to figure out whether the specific business is a good fit for them or not, and also when the good time is to use the services of a specific business. 
