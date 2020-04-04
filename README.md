Inspired by google community mobility report https://www.blog.google/technology/health/covid-19-community-mobility-reports that provided insights into what has changed in response to policies aimed at beating the propagation of COVID-19 by showing trends over time by geography, across different categories of places such as retail and recreation, groceries and pharmacies.
### What it does
It models the occupancy of the supermarkets using real-time analysis of Swiss telecom companies location data in compliance with the Swiss Law on Data Confidentiality and Protection.

In a period where social distancing is needed this application will allow us to do it in an effective way especially for the post quarantine period. 
This application will allow users to monitor the movement of the people going to the stores and gives a better recommendation to optimize the reduction of affluence in the stores.
### How we would build it
We will first provide a proof of concept using randomized data simulating people's visits to local supermarkets ( inspired by Google Popular Now features ) and by showing people the closest “available”* shop to them.
The goal is also to have a dummy heatmap with manually generated data deployed on a platform built with common web development tools. 

*available : we define a shop as available when it is not near full capacity. During this pandemic period many supermarkets adapted a queue system where each shop had a specific capacity and people coming after that would have to wait in a queue.

### How to Optimize 
- Find a mathematical model to accurately represent the movement of the users. 
- Leverage the data collected from the users.
- Motivate Swiss Telecom Companies to provide us access to anonymized location data.
