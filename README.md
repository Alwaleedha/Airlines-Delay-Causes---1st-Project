# Airline Arrival Delay Time Prediciton


# Introduction

Flights delays are major problem affecting airlines, passengers, and countries all over the world that causes economic losses in billions.
Why solving this problem? To predict the delays before it happens so airlines action accordingly and satisfies passengers by other recommendation


# Problem

The airlines inability to inform passengers of the delays or cancellation prior to flights due to weather, NAS, or others reasons.


# Dataset

The source of the data set is Kaggle >> https://www.kaggle.com/omarhossam214/us-airline-delay-causes
The dataset has 21 features and 292669 rows.

#Features description

* year 
* month 
* carrier : Abbreviation of carrier 
* carrier_name : the actual carrier name 
* airport : Abbreviation of airbort 
* airport_name : the actual airport name 
* arr_flights: Number of flights arrived the airport.
* arr_del15 : Number of flights delayed.
* carrier_ct: Number of flights delayed due to air carrier
* weather_ct: Number of flights delayed due to weather.
* nas_ct: Number of flights delayed due to National Aviation System ( non-extreme weather conditions, airport operations, heavy traffic volume, and air traffic control ) check more in [here](https://www.bts.gov/topics/airlines-and-airports/understanding-reporting-causes-flight-delays-and-cancellations#:~:text=National%20Aviation%20System%20(NAS)%3A,volume%2C%20and%20air%20traffic%20control.)
* security_ct: Number of flights delayed due to security 
* late_aircraft_ct: Number of flights delayed due to a previous flight.
* arr_cancelled: Number of  flight that has been cancelled.
* arr_diverted: Number of  flight that has been diverted.
* arr_delay: time of delayed flights.
* carrier_delay:time  of delayed flights due to air carrier.
* weather_delay: time of delayed flights due to weather.
* nas_delay:time of delayed flights due to National Aviation System.
* security_delay:time of delayed flights due to security.
* late_aircraft_delay:time of delayed flights due to a previous flight.


# Machine learning  Algorithm
- Linear Regression LR Algorithm


# Tools

* Python is the programing language for this project

* JUPYTER/Google colab is the notebooks used to perform the coding. 

* The libraries will be used are:
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - SkLearn



