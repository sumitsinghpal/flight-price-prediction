# flight-price-prediction
For purchasing an airplane ticket, the traditional purchase approach is to buy a ticket far in advance of the flight’s departure date to avoid the risk that the price may increase quickly before the date of departure. However, this is not always the case; if airline corporations wish to increase sales, they can lower prices. Airlines employ a variety of factors to decide flight ticket rates, including whether the trip is around the holidays, the quantity of available seats on the plane, and even the month. Some of the variables can be seen, while others are hidden. In this context, customers are attempting to discover the best day to purchase a ticket, while airline firms, on the other hand, are attempting to maximize overall revenue.

Created a tool that estimates Flight Prices to help users look for best prices when booking flight tickets.
Engineered features from the Departure Time, Date of Journey, to quantify the data and make it more understandable.
Optimized multiple Regression models using GridsearchCV to reach the best model.
Built a client facing API using flask

# Codes and Resources Used
Python Version: 3.8.5
Packages: pandas, numpy, sklearn, matplotlib, seaborn, flask, json, pickle
For Web Framework Requirements: pip install -r requirements.txt

# problem statement
Size of test set: 2671 records
FEATURES: Airline: The name of the airline.
Date_of_Journey: The date of the journey
Source: The source from which the service begins.
Destination: The destination where the service ends.
Route: The route taken by the flight to reach the destination.
Dep_Time: The time when the journey starts from the source.
Arrival_Time: Time of arrival at the destination.
Duration: Total duration of the flight.
Total_Stops: Total stops between the source and destination.
Additional_Info: Additional information about the flight
Price: The price of the ticket

# data collection 
collected data buy using data scraping tool octoprase and used insta data scraping google extender
websites like make my trip and ixigo were used to collect data

# Cleaning the Data
I needed to clean it up so that it was usable for our model. I made the following changes and created the following variables:
Made Columns for Day and Month out of Date of Journey
Calculated the total flight duration
Removed the null values
Removed the outliers

# Technologies Used
octoparse
python
flask
pandas
matplotlib
seaborn
sklearn
pickle

