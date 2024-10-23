# Uppgift_001
Ai-uppg
Final project for the Building AI course.

## Summary
This project aims to develop an AI solution that helps drivers find the best gas prices near their current location. By analyzing data from various gas stations and users can quickly access the most cost effective options.

## Background
I have noticed that gas prices often vary between different stations and it can be frustrating to manually search for the cheapest price. My idea is to help drivers save both time and money by automatically showing the nearest station with the best price. This is especially useful for drivers who are frequently on the road and need to optimize their refueling.

## How it is used
The user opens a mobile app that activates location sharing, and the AI service retrieves data from nearby gas stations. The stations are then sorted by price and distance and the user receives a list of the cheapest options nearby.

## Data and AI methods
* Data is retrieved from open APIs that provide gas price information from various stations.
* The AI uses geolocation to determine the users position and an algorithm to sort stations by price.

## Challenges
* Gas price data may not always be up to date or available for all stations.
* GPS accuracy can be a challenge in areas with poor coverage which may affect the precision of station locations.
* Ethical concerns may arise regarding how users location data is handled and protected.

## What next?
The next step is to build a working prototype that can collect and display real time gas price data for the user. I will also explore additional data sources and potential collaborations with gas stations to ensure that the data is accurate and up-to-date.
