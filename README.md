# Space_X_Falcon9_Landing_Prediction
## Project Overview
  Companies are making space travel more affordable for every one. Virgin galactic, Blue origin and Space x are some the companies that proveide space travel and satelite services. One of the most succesful companies at space travel is Space X, Space X rocket launch are cheaper compared to rockets from other companies. Space x falcon 9 launch is advertised on their website at a cost of $62million, while other companies that provides rockets costs about $160 million and above each. Main reason for the difference in price is Space X Falcon 9 ability to reuse its first stage. Hence if we can determine if the first stage will land, we can determine the cost of each launch.
In this project i'm working as a data scientist with a new company Space Y, the goal of this project is to build a model to predict if Space X Falcon 9 launches first stage will land as it can be used to determine the price of a launch.

## Data Sources
1. Data will be collected using Space X REST api, this data will give details about launching, rocket used, payload, launch specifications, landing specification and landing outcome. Our goal is to use this data to determine if Space X Falcon 9 will land a first stage successfullly or not.
2. Webscrapping wikipedia page on space X historical launch data to get relevant data for Space X launches

## Methodology
<ul>
  <li>Data collection</li>
  <li>Data wrangling and cleaning</li>
  <li>Exploratory Data Analysis (EDA)</li> 
  <li>Interactive visual analytics using Folium</li>
  <li>Predictive analysis using classification models</li>
</ul>

## Project Summary
<ul>
  <li>Space X launch data was collected using Space X REST API. Launch Data collected includes the following details about each launch: Flight Number, Date, Booster Version, Payload Mass, Orbit, Launch Site, Flights, Grid Fins, Reused, Legs, Landing Pad, Block, Reused Count, Serial, Longitude and Latitude. Historical Falcon 9 Launch were collected from a Wikipedia page titled List of falcon 9 Heavy Launches. The data collection process was web scraping the page to collect relevant data for our project. Data collected from the web scraping includes; Flight No., Launch site, Payload, Payload mass, Orbit, Customer, Launch outcome, Version Booster, Booster landing, Date and Time</li> 
  <li>Falcon 9 launches saw steady increase in succesfull first stage landing from 2013 to 2020. It has a total of 4 Launch sites and payload ranges between 0 – 16000 kg. The launch orbits are LEO, ISS, PO, GTO, ES-L1, SSO, HEO, MEO, VLEO, SO, GEO. These parameters and other parameters with significant relationships were used to develop a classification model.</li>
  <li>Trained a model with a prediction accuracy of 83.33% The models were trained and tested using GridsearchCV as it picks the best suited parameters for our model.</li>
</ul>
