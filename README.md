# Airline Passenger Satisfaction

This dataset contains an airline passenger satisfaction survey. What factors are highly correlated to a satisfied (or dissatisfied) passenger? Can you predict passenger satisfaction? 


## Data

**Gender**: Gender of the passengers (Female, Male)

**Customer Type**: The customer type (Loyal customer, disloyal customer)

**Age**: The actual age of the passengers

**Type of Travel**: Purpose of the flight of the passengers (Personal Travel, Business Travel)

**Class**: Travel class in the plane of the passengers (Business, Eco, Eco Plus)

**Flight distance**: The flight distance of this journey

**Inflight wifi service**: Satisfaction level of the inflight wifi service (0**:Not Applicable;1-5)

**Departure/Arrival time convenient**: Satisfaction level of Departure/Arrival time convenient

**Ease of Online booking**: Satisfaction level of online booking

**Gate location**: Satisfaction level of Gate location

**Food and drink**: Satisfaction level of Food and drink

**Online boarding**: Satisfaction level of online boarding

**Seat comfort**: Satisfaction level of Seat comfort

**Inflight entertainment**: Satisfaction level of inflight entertainment

**On-board service**: Satisfaction level of On-board service

**Leg room service**: Satisfaction level of Leg room service

**Baggage handling**: Satisfaction level of baggage handling

**Check-in service**: Satisfaction level of Check-in service

**Inflight service**: Satisfaction level of inflight service

**Cleanliness**: Satisfaction level of Cleanliness

**Departure Delay in Minutes**: Minutes delayed when departure

**Arrival Delay in Minutes**: Minutes delayed when Arrival

**Satisfaction**: Airline satisfaction level(Satisfaction, neutral or dissatisfaction)

The main purpose of this dataset is to predict whether a future customer would be satisfied with their service and which aspect of the services offered by them have to be emphasized more to generate more satisfied customers. Data consists of total train and test data. 


The whole code is in the file Airline_Passenger Satisfaction.ipynb.


![Gender](https://user-images.githubusercontent.com/62169942/155899290-ecd8b96d-f8c2-41aa-9d24-9f05383973b3.png)
 
 We see that absolutely Genders type are same percent.
 
  
 
 ![Barplot](https://user-images.githubusercontent.com/62169942/155899463-1f81af34-5310-4e0e-9116-5cdf8c59e821.png)

 Outliers for each feature show us what data have in our dataset. 


![algoritm](https://user-images.githubusercontent.com/62169942/155899504-aa463045-5b98-490f-a7ad-2dda5c46d5d9.png)
 
Using the Random Forest model to find only the important features and drop out lowest feature score improved acccuracy score with 96.50 and with KNN is 93.40
