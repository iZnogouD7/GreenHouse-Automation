This project is done using arduino Uno. We have used DHT sensor to read humidity and temperature of
the greenhouse, soil moisture sensor to read moisture level of the soil, fan to cool the environment,
heater to warm the environment, relays as switches, pump to deploy water and lcd display to display 
all the datas.
The Threshold are assumed according to our envirnoment condition.
if temp is higher then upper_thres then fan is turned on to cool the place. once it cools then if 
temp is less than upper_thres then fan is turned off.
if temp is lower then low_thres then heater is turned on to heat the place. once it heats then if 
temp is greater than low_thres then heater is turned off.
if soil_value is less then soil_thres then pump is turned on to water the place. 
if soil_value is graater then soil_thres then pump is turned off. 
