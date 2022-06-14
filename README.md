# Project Name
> A bike-sharing prediction using Linear Regression for BoomBikes



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- BoomBikes is a bike-sharing system in which bikes are made available for shared use to individuals on a short term basis for a price or free. It allows people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

- BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end. 

- The objective of this assignment is to model the demand for shared bikes with the available independent/predictor variables. It will be used by the management to understand how demand varies with different features. They can accordingly manipulate the business strategy to meet the demand levels and customer's expectations. The model would also be used by management to understand the demand dynamics of a new market. 

- The dataset used for Linear regression contains bike sharing data for 2018 and 2019.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- As per the final model, the top 3 predictor variables that influences bike booking are:
-
    - Temperature (atemp) : A coefficient value of ‘0.44183’ indicated that a temperature has significant impact on bike rentals
    - Light_rainsnow (weathersit =3) : A coefficient value of ‘-0.265918’ indicated that the light snowrain deters people from renting out bikes
    - Year (yr) : A coefficient value of ‘0.241595’ indicated that a year wise the rental numbers are increasing
    
- Conclusion on categorical variable -
  - The demand of bike is less in Spring season, as compared to other seasons. The demand of bike is more in Fall season as compared to other seasons
  -	The demand of bike is more in year 2019 as compared to year 2018
  - The demand of bike is lowest in month of January and it is highest in month of August. 
  - Bike demand is more in Clear weather (Clear, Few clouds, Partly cloudy, Partly cloudy) as compared to other weather condition. For Light Snow (Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds), the demand of bike is lowest (there isn’t any data available for heavy snow in the input dataset provided)
  - Bike demand is more in holidays as compared to not a holiday
  - The demand of bike is more on a weekday Friday followed by Thursday
  - Bike demand is more in not-working day as compared to working days


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.7.3

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- References : referred to the previous session on Linear Regression


## Contact
Created by [@sahuipsita] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
