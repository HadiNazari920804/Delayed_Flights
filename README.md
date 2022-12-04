# Delayed_Flights
Delayed flights dataset:

It's a Dataset of flight delays in the United States from 2003-2020

73282 rows – 22 features

Features

Date and Time – 2 features

'year', ' month

Categorical – 4 features

'carrier', 'carrier_name', 'airport', 'airport_name'

Numerical – 15 features

'arr_flights', 'arr_del15', 'carrier_ct', ' weather_ct', 'nas_ct',
'security_ct', 'late_aircraft_ct', 'arr_cancelled', 'arr_diverted',
' arr_delay', ' carrier_delay', 'weather_delay', 'nas_delay',
'security_delay', 'late_aircraft_delay'

Null – 1 feature

'Unnamed: 21'



Features Descriptions:

year : Year

month : Month

carrier : The airline's code

carrier_name : The airline's full name

airport : The airport's code

airport_name: The airport's full name, including city & state & name of airport

arr_flights : Number of flights arriving at airport

arr_cancelled : Number of cancelled flights

arr_diverted : Number of flights that were diverted

arr_del15 : Number of flights more than 15 minutes late

carrier_ct : Number of flights delayed due to air carrier. (e.g. no crew)

weather_ct : Number of flights delayed due to weather

nas_ct: Number of flights delayed due to National Aviation System (e.g. heavy air traffic)

security_ct : Number of flights delayed due to a security breach

late_aircraft_ct : Number of flights delayed as a result of another flight on the same aircraft delayed

arr_delay : Total time (minutes) of delayed flight

carrier_delay : Total time (minutes) of delay due to air carrier

weather_delay : Total time (minutes) of delay due to inclement weather

nas_delay : Total time (minutes) of delay due to National Aviation System

security_delay : Total time (minutes) of delay as a result of a security issue

late_aircraft_delay : Total time (minutes) of delay flights as a result of a previous flight on the same airplane being late


