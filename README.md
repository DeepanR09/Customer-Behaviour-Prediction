For predicting customer behaviour, predictive modeling and exploratory data analysis was performed.

Packages used: pandas,sklearn (scikit-learn), matplotlib and numpy

Algorithm used: Random Forest Classificaton (XBG Classifier is another alternative)

To provide more context, below is a more detailed data description, explaining exactly what each column means:

num_passengers = number of passengers travelling    
sales_channel = sales channel booking was made on    
trip_type = trip Type (Round Trip, One Way, Circle Trip)    
purchase_lead = number of days between travel date and booking date    
length_of_stay = number of days spent at destination    
flight_hour = hour of flight departure    
flight_day = day of week of flight departure    
route = origin -> destination flight route    
booking_origin = country from where booking was made    
wants_extra_baggage = if the customer wanted extra baggage in the booking    
wants_preferred_seat = if the customer wanted a preferred seat in the booking    
wants_in_flight_meals = if the customer wanted in-flight meals in the booking    
flight_duration = total duration of flight (in hours)    
booking_complete = flag indicating if the customer completed the booking    


Procedure:

1.Dataset is imported     
2.Unique attribute is days ,so they are mapped     
3.Statistical and arithmetic methods are performed for all attributes with respect to instances    
4.All the attributes data types are converted into int64 (few were objects earlier)    
5.Mutual Information scores are generated    
6.Bar graph is plotted with mi scores    
7.Train Test Split is done    
8.Random forest is implemented    
9.Accuracy and AUC score is generated    

RESULT:
    Accuracy : 84.91 = 85%
    AUC score: 0.5545467812791867
