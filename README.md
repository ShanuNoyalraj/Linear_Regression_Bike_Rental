# Bike sharing Assignment
> 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems   allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system..
  
- Goal is to build a model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

- Dataset used is Bike Sharing dataset - https://ml-course2-upgrad.s3.amazonaws.com/Linear+Regression+Assignment/Bike+Sharing+Assignment/day.csv

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 Count of bikes is positiviley correlated with the variables temperature,month (September,October) and Year(2019)
- Conclusion 2 Count of bikes is decreases for variables like Holidays, Sundays,Spring,Mist cloudy_Broken clouds_Few clouds,Light rain_Light snow_Thunderstorm_Scattered clouds
- Conclusion 3 The best fit obtained for predicting count of bikes is 
Count = 0.2356 *Year + 0.3670 *Temp- 0.1457 *spring- 0.0813 *Mist cloudy_Broken clouds_Few clouds + 0.0828 *September- 0.3146 *Light rain_Light snow_Thunderstorm_Scattered clouds + 0.0683 *October- 0.1013 *holiday- 0.0502 *Sunday 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- EDA
- Linear regression
- Numpy, Pandas, Matplotlib, Seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [Shanunoyalraj@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
