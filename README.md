# IBM-Data-Science---Capstone-Project-SpaceX

## Introduction

* Project background
Space X advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because Space X can reuse the first stage. Therefore, if we can determine whether the launch will be a successful one or if the launch will fail, whether the the first stage will land or not,  we can determine the cost of a launch. The goal of the project predict if the SpaceX can reuse the first stage by using public data and machine learning models.

* Problems to solve:
How payload mass, launch site, number of flights, and orbits affect first-stage landing outcome.
What is the rate of successful landings over time.
What is the best predictive model for successful landing.

## Executive Summary

* Methodology:
Data Collection through SpaceX REST API and Web Scarping
Data Wrangling to create success/fail outcome variables
Exploratory Data Analysis with Visualization techniques factors such as: Payload, Launch Site, Flight Number and Yearly trend.
Exploratory Data Analysis with SQL to calculate Total Payload, Payload range for successful launch, and total number of successful and failed outcomes.
Interactive Visual Analytics with Folium for Launch Site success rates and proximity to geographical markers
Interactive Dashboard with Plotly Dash for Launch Site with the most success and successful Payload ranges
Machine Learning Predictive Analysis using Logistic Regression, SVM, Decision Tree and KNN

* Results:
  
* Exploratory Data Analysis:
Launch success rates have improved over time
KSC LC-39A has the highest success rate among Landing Sites
Orbits ES-L1, GEO, HEO and SSO have a 100% success rate 
* Visualization/Analysis:
Most Launch Sites are near the equator and are also close to the coast
* Predictive Analytics:
All the models performed similarly on the test set. However, the Decision Tree model provided a more accurate result

## Conclusion

* Model Performance: The models performed similarly on the test set with the decision tree slightly outperforming the rest.
* Equator: Most of the launch sites are near the equator for an additional natural boost - due to the rotational speed of the earth – which helps reduce the overall cost of the launch
* Coast: All launch sites are close to the coast
* Launch Success: Increases over time
* KSC LC-39A: Has the highest success rate among launch sites. Has a 100% success rate for launches less than 5,500 kg
* Orbits: ES-L1, GEO, HEO, and SSO have a 100% success rate
* Payload Mass: Across all launch sites, the higher the payload mass (kg), the higher the success rate
