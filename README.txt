
Using Python to Explore US Bikeshare Data

     This Python code is for Project 2 of Udacity's Data Analyst Nanodegree and is used to explore data related to bike share systems for Chicago, New York City, and Washington. It takes in users' raw input to create an interactive experience in the terminal to present descriptive statistics for analytical standpoint.
     
Bike Share Data

     Over the past decade, bicycle-sharing systems have been growing in number and popularity in cities across the world. Bicycle-sharing systems allow users to rent bicycles on a very short-term basis for a price. This allows people to borrow a bike from point A and return it at point B, though they can also return it to the same location if they'd like to just go for a ride. Regardless, each bike can serve several users per day.
     Thanks to the rise in information technologies, it is easy for a user of the system to access a dock within the system to unlock or return bicycles. These technologies also provide a wealth of data that can be used to explore how these bike-sharing systems are used.
     In this project, the data is provided by Motivate, a bike share system provider for many major cities in the United States, to uncover bike share usage patterns. One will explore the usage between three large cities: Chicago, New York City, and Washington, DC.
     
The Datasets

   Randomly selected data for the first six months of 2017 are provided for all three cities. All three of the data files contain the same coreÊsix (6)Êcolumns:

* Start Time 
* End Time 
* Trip Duration 
* Start Station 
* End Station 
* User Type
 
 The Chicago and New York City files also have the following two columns:
* Gender
* Birth Year

Statistics Computed

     In this project, the written code is to compute a variety of descriptive statistics:
#1 Popular times of travelÊ(i.e., occurs most often in the start time)

* most common month
* most common day of week
* most common hour of day

#2 Popular stations and trip

* most common start stations
* most common end stations
* most common trip from start to end (i.e., most frequent combination of start station and end station)

#3 Trip duration

* total travel time
* average travel time

#4 User info

* counts of each user type
* counts of each gender (only available for NYC and Chicago)
* earliest, most recent, most common year of birth (only available for NYC and Chicago)

The Files

To answer these questions, it was needed to write a Python script and using three city dataset files:

chicago.csv
new_york_city.csv
washington.csv

An Interactive Experience

The bikeshare.py file is set up as a script that takes in raw input to create an interactive experience in the terminal that answers questions about the dataset. The experience is interactive because depending on a user's input, the answers to the questions on the previous page will change! 

