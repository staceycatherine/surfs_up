# surfs_up

For this project, our goal is to gain investors for a surf shop in Hawaii. We wanted to gather as much information as possible to share with potential investors. We started with looking at weather data using SQLite and SQLAlchemy. This allowed us to create tables for our data for easier analysis. 

## Overview
We looked at the dates and levels of precipitation, in a dataframe and in a plot to better show any trends. We included a summary of statistics for the amount of precipitation in a year. In order to provide solid information, we looked at the weather stations to see how active they were and provided details based on the most active station. Then, we looked at the data for temperature, minimum, maxium and average. Concerned that the data and code may not be the best way to present the data to the board of directors, we decided to use Flask to display the results in a webpage. Flask allows us to present the key ideas without getting bogged down in the code itself. Our investor ask for more detailed temperature information for the months of June and December to determine if the surf and ice cream shop business would be sustainable year round. 


## Results shown in tables below
* Average is about 4 degrees warmer in June
* The low in December is 57 degrees, which can feel a lot chillier than the low of 64 degrees in June
* High of 85 degrees in June vs 83 degrees in December

![image](https://user-images.githubusercontent.com/89313168/142741555-fbabf90f-fb91-4b8b-9b29-8bd9c07aebba.png)  ![image](https://user-images.githubusercontent.com/89313168/142741571-13311b0b-f41e-4142-b975-13854166c296.png)

## Summary
Although there is a chance to experience some cooler weather in December, the averages are close enough to suggest that the surf and ice cream shop would be sustainable year round. It might be helpful to look at the amount of precipitation and take a closer look at locations before making a decision. 
