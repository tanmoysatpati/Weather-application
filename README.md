# Weather Forecast Flask App

Live Weather Forecast Flask App which takes a city name and returns various weather characteristics like Temperature in C, Temperature in F, Humidity, Wind, and many more.

# Source Codes for the Live Weather Forecast Flask App
- app.py
- home.html

# Getting API_KEY from RapidAPI
- Get your API KEY, API HOST, and links from RapidAPI.
- Open RapidAPI and search for WeatherAPI.com.
- Now click on Subscribe to Test and Subscribe to the Basic Plan which is FREE.
- Now copy your API_KEY, API_HOST, and URL from here and add that in app.py

# Deployment in GCP 
  - We need to create trigger in cloud build and it it will create a CI/CD pipeline.
  - It will also create docker image in comtainer registry in GCP.
  - We need to app.yaml file and it will deploy the falsk app in GCP app engine.
  - Make sure that all the permissons are granted using IAM role and all API's are enabled.
