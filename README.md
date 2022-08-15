# US-Bikeshare-case-study
Analysing the US Bike-share data and deriving deeper data-driven insights from the same using python


The case-study was taken from Udacity(https://classroom.udacity.com/nanodegrees/nd002-ent-masterschool-assessment/parts/beb03bbd-b039-422b-9245-c8e753e58f7c/modules/444df3e3-ea30-47cb-ac03-b1a08ab6e828/lessons/ls1727/concepts/a0828bef-066b-4c29-8184-752ff1d2300c ) pre-course on Data Analysis

## Overview
In this project, you will make use of Python to explore data related to bike share systems for three major cities in the United States—Chicago, New York City, and Washington. You will write code to import the data and answer interesting questions about it by computing descriptive statistics. You will also write a script that takes in raw input to create an interactive experience in the terminal to present these statistics.

## What Software Do I Need?
To complete this project, the following software requirements apply:

You should have Python 3, NumPy, and pandas installed using Anaconda
A text editor, like Sublime or Atom.
A terminal application (Terminal on Mac and Linux or Cygwin on Windows).


# CASE STUDY

Bike Share Data
Over the past decade, bicycle-sharing systems have been growing in number and popularity in cities across the world. Bicycle-sharing systems allow users to rent bicycles on a very short-term basis for a price. This allows people to borrow a bike from point A and return it at point B, though they can also return it to the same location if they'd like to just go for a ride. Regardless, each bike can serve several users per day.

Thanks to the rise in information technologies, it is easy for a user of the system to access a dock within the system to unlock or return bicycles. These technologies also provide a wealth of data that can be used to explore how these bike-sharing systems are used.

In this project, you will use data provided by Motivate, a bike share system provider for many major cities in the United States, to uncover bike share usage patterns. You will compare the system usage between three large cities: Chicago, New York City, and Washington, DC.

## The Datasets
Randomly selected data for the first six months of 2017 are provided for all three cities. All three of the data files contain the same core six (6) columns:

Start Time (e.g., 2017-01-01 00:07:57)
End Time (e.g., 2017-01-01 00:20:53)
Trip Duration (in seconds - e.g., 776)
Start Station (e.g., Broadway & Barry Ave)
End Station (e.g., Sedgwick St & North Ave)
User Type (Subscriber or Customer)
The Chicago and New York City files also have the following two columns:

Gender
Birth Year

Data for the first 10 rides in the new_york_city.csv file

The original files are much larger and messier, and you don't need to download them, but they can be accessed here if you'd like to see them (Chicago, New York City, Washington). These files had more columns and they differed in format in many cases. Some data wrangling has been performed to condense these files to the above core six columns to make your analysis and the evaluation of your Python skills more straightforward.

Statistics Computed
You will learn about bike share use in Chicago, New York City, and Washington by computing a variety of descriptive statistics. In this project, you'll write code to provide the following information:

## #1 Popular times of travel (i.e., occurs most often in the start time)

most common month
most common day of week
most common hour of day
## #2 Popular stations and trip

most common start station
most common end station
most common trip from start to end (i.e., most frequent combination of start station and end station)
## #3 Trip duration

total travel time
average travel time
## #4 User info

counts of each user type
counts of each gender (only available for NYC and Chicago)
earliest, most recent, most common year of birth (only available for NYC and Chicago)
The Files
To answer these questions using Python, you will need to write a Python script. To help guide your work in this project, a template with helper code and comments is provided in a bikeshare.py file, and you will do your scripting in there also. You will need the three city dataset files too:

chicago.csv
new_york_city.csv
washington.csv
All four of these files are zipped up in the "all_project_files" document in the Resources tab in the sidebar on the left side of this page. (You may need to scroll down inside the Resources tab to see the "all_project_files" doc.) You can choose to download and unzip that "all_project_files" doc to access all four project files, and do your project work on your local machine.

If you'd prefer, the later Project Workspace page in the classroom here also has the bikeshare.py file and all the city dataset files included in it, and you can do all your work on the project with them there. If you choose this option, you don't need to download the files from the Resources tab.

;
