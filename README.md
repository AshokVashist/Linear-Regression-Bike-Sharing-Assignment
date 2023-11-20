# Project : Bike Sharing Demand Prediction

## Problem Statement
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario.So they decided to go with data based analysis approach to figure out what is impacting Shared Bike Demands.
- We have received a Survey data which covers a lots of informations about the Bike Sharing Deamnd and associated factors across US
 
##Business Objective
- Model building and Evaluation on Survey Data
- Analyse the factors influencing the Bike Sharing demand 
- Business would leverage this Model to estimate Future Demands


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Factors influencing Bike Sharing Demand:
- Season : ‘Spring’, ‘Summer’ & ‘Winter’ has negative corelation  with BikeSharing demand, it indicates that these season have low demand of Bike sharing.
- Month : ‘January’ month is having negative coefficient; it indicates that Bike Sharing demand decreases during Jan month where ‘September’ month is having positive coefficient and have maximum demand of Bike sharing.
- Weather Situation : ‘Light Snow with rain’ and ‘Mist’ weather having negative coefficient which indicates bike sharing demands decreases during these weather conditions.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusion
- Count has high impact from year column as data shows growth from 2018 to 2019
- Shared Bike Demand rises considerably in the month of September Month (+Ve Correlation)
- Windspeed, Spring, Summer, Winter, Jan, Tuesday, Light-Snow & Mist shows -Ve Correlation. As the values of these variables increases,the demand decreases
- Linear regression model is  able to predict bike demand precisely with an R2 Score of 79.1%

## Python Libraries 
- Seaborn (Python Library)
- MatPlotLib (Python Library)
- Stats Model (Python Library)
- SkLearn (Python Library)


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@AshokVashist]

