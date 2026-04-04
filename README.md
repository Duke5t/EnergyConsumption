# EnergyConsumption
A ML project which predicts state-level residential energy consumption by leveraging engineered features from weather and temporal data, integrating API-sourced datasets. 

How to Run:

It should be noted the notebook can be run without the accompanying datasets using API interactions; however, due to API call limits (minute, hourly, daily), it may take quite some time to run due to the volume of weather data acquired from openmeteo. The API interaction uses sleep functions to traverse API call limit times.

A public api key is included but, if the user has a higher limit key available, it can replace the existing key to allow smooth and fast acquisition of weather data. Using only the public key, the program may take several days to acquire all necessary data from scratch. (But its free)
