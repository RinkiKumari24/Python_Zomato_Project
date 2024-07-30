#**Exploratory Data Analysis of Swiggy**


**What is Exploratory Data Analysis?**


Exploratory Data Analysis (EDA) is an approach to analyzing and summarizing datasets, with the goal of discovering patterns, anomalies, and other insights that can inform further analysis and modeling efforts.EDA typically involves visualizing data using plots and graphs, as well as statistical summaries and tests to uncover patterns and relationships in the data.

**By Using Kaggle swiggy dataset**



**Swiggy** is an Indian online food ordering and delivery platform. Founded in July 2014, Swiggy is based in Bangalore and operates in 500 Indian+ cities. Besides food delivery, Swiggy also provides on-demand grocery deliveries under the name Instamart, and a same-day package delivery service called Swiggy Genie.
The company had to prepare for some competition when the app went live in a small area because of Foodpanda and Ola Cafe. When Swiggy first began operations only six delivery boys and more than 20 eateries were on board. It was only reasonable at this time to be unable to tell a good restaurant from a bad one. As a result, the crew only chose respectable eateries that did not offer internal delivery.



**The basic steps of any EDA project**

Select the real-world data set from Kaggle.
Download and read the file using Pandas.
Select the required columns from the dataset.
Perform data preparation and cleaning using Pandas and NumPy.
Plot interactive graphs using Matplotlib, Seaborn, Plotly, and WordCloud.
Ask and Answer interesting questions from the dataset.
Summarize your work and provide a conclusion.
Ideas for future work.



**Data Preparation & Cleaning**

Load the file using pandas.
Select required columns from the dataset.
Viewing basic information for the dataset.
Handling missing and duplicate data.
Split city column and create two new column as town and cities.
Conversion of data-type in dataset.
Check for Outliers.
Filtering Final DataFrame with required columns for Data Analysis.


**Performing Expolaratory Analysis & Visualization**

The barplot shows count of top 20 restaurant's franchise situated in different cities of India and are available for service on swiggy app.
Dommino's Pizza, Pizza Hut, KFC,Kwality Walls Frozen Desert and Ice Cream Shop, Baskin Robbins and Subway are the top 5 restaurant's franchise situated in different cities of India and are available on swiggy app.
It is found that customer's has not given rating for more than 80,000 restaurants. (Too Few Ratings)
There are nearly about 20,000 restaurants in India where customer's have given less rating. i.e (50+ rating to 20+ rating)
There are few restaurant where customer's has given good ratings. i.e (500+ rating and 1K+ rating)
There are very few restaurants where customer's has given very good ratings i.e (5K+ rating and 10K+ rating)
There are 54.5% available restaurants with rating between 3.1 to 4.0.
There are 40.3% available restaurants with rating between 4.1 to 5.0.
There are 4.8% available restaurants with rating between 2.1 to 3.0.
There are 0.344% available restaurants with rating between 1.1 to 2.0.
There are 0.00163% available restaurants with rating <1.0.
Chinese is the most popular cuisine that are available with restaurant in swiggy across India.
North Indian, Indian and Snacks are the followed cuisine that are available with restaurant in swiggy across India.
Bangalore, Delhi, Pune, Hyderabad and Chennai are the top 5 cities in India with maximum number of restaurants available on swiggy.
Coimbatore, Lucknow, Surat, Vijayawada and Ludhiana are the cities that has average cost of restaurant as ₹250 which is cheaper.
We can also say that Hyderabad is the top cities in India that has 100 restaurants with rating below 2.5.
Bangalore, Chennai and Delhi are the cities that has 30 to 40 restaurants with rating below 2.5.
Chandigarh and Kolkata are the cities that has 20 to 30 restaurants with rating below 2.5.
Pune and Gurgaon has about 15 restaurants with rating below 2.5.
Chennai has the maximum restaurants with higher ratings between 4.2 to 5.0
Bangalore, Hyderabad, Pune & Kolkata are the following cities with maximum rating of restaurants between 4.2 to 5.0.
Restaurant from Chennai city where customer has given maximum rating (i.e 5K rating). This barplot is stacked considering restaurant outlets
Chennai, Bangalore and Hyderabad cities has maximum number of outlets of Domminos Pizza.
Pune, Delhi & Kolkata are the next following cities with maximum Domminos Pizza outlets.
Mumbai and Chennai has maximum restaurants with cost upto ₹3000
Kolkata and Delhi has maximum restaurants upto ₹700 and there are very less restaurant above ₹1500
Hyderabad and Bangalore has maximum restaurants upto ₹1500.
Bangalore and Pune has maximum restaurants upto ₹1500 and there are very few restaurants between ₹1500 to ₹2000.
Delhi, Pune and Bangalore are the cities with more than 8000 restaurants where customer has not given ratings.
Hyderabad, Kolkata and Chennai has nearly about 5000 restaurants where customer has not given ratings.
Mumbai has 3722 restaurants with no ratings.
Ahmedabad, Chandigarh and Lucknow has nearly about 2000 restaurants where customer has not given ratings.
Bangalore, Delhi, Kolkata, Chennai and Pune are the common top 5 cities where customer like to order Chinese and Fast Food.



**Summary**:

The rating column in the dataset shows -- as there is no rating values below 1.0
There are a few names of the restaurant with the same name in upper case and lower case.
The restaurant data contains cuisine in pairs like Chinese, and Indian. So it is necessary to provide unique cuisine details.
The id values for the restaurant are unique.
The cost column in the dataset contains values like ₹300,350, ₹8,000, ₹7,000, and ₹5,000 where the price is incorrect.
After placing the order, most of the customers have not given ratings to the restaurant.



**Conclusion**:

Domminos, Pizza Hut, and KFC has the largest restaurant franchise across India on swiggy app.
There are more than 80,000 restarant counts where customer has not given ratings.
There are 54.5% restaurants with rating between 3.1 to 4.0.There are 40.3% restaurants with rating between 4.1 to 5.0.
Chinese is available with maximum number of restaurants across India.
The top most expensive restaurants are in Mumbai.
Coimbatore, Lucknow, Surat, Vijayawada and Ludhiana are the top 5 cities where average cost of restaurant is cheaper.
Bangalore, Delhi, Pune, Hyderabad & Chennai are the cities having top 5 maximum restaurants across India.
Hyderabad is the top cities in India that has maximum restaurants with rating less than 2.5.
Bangalore, Delhi, Pune, Hyderabad and Chennai are the top 5 cities in India with maximum number of restaurants available on swiggy.
Bangalore, Chennai, Pune and Hyderabad are the cities that has maximum number of Dominno's Pizza outlet.
The customers living in Delhi, Pune & Bangalore cities has not given ratings to the maximum restaurants.
There are very few restaurant for which customer's has given high ratings. i.e (5K+ rating and 10K+ rating)
