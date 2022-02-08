# Linear Regression Bike Sharing Assignment
> This case study harnesses Linear Regression to find out 
> - Which variables are significant in predicting the demand for shared bikes.
> - How well those variables describe the bike demands


## Table of Contents
* [Business Understanding](#business-understanding)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Contact](#contact)

<!-- You can include any other section that is pertinent to your problem -->

## Business Understanding
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system. 
>
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
>
> In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits. They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. 
>
> The company wants to know:
> - Which variables are significant in predicting the demand for shared bikes.
> - How well those variables describe the bike demands

## Business Objective
> You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Data 
1. `day.csv` - Bike sharing dataset that is based on year 2018 and 2019
2. `Readme.txt` - Data dictionary for the dataset `day.csv`

## Conclusions:
1. year : We can see that with every passing year, we have more rentals.
2. workingday: There are higher chances of renting a bike on workingdays
3. temp: More bikes are rented when temperature is higher
4. humidity: Rentals are more if the humidity is less
5. windspeed: Rentals drop with rise in windspeeds
6. season: Rentals are high when there is winter, but less when it is spring.
7. weather: There are high rentals when the weather is clear, but low when cloudy or has light rains/snow


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python (3.9.7)
- Numpy (1.20.3)
- Pandas (1.3.5)
- Seaborn (0.11.2)
- matplotlib (3.5.0)
- statsmodels (0.12.2)
- scikit-learn (1.0.2)

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@saurabhdugdhe](https://github.com/saurabhdugdhe)


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
