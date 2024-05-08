# SolarData
Here I will give an overview of this project performed in April 2023.

## Problem:
We have unconventional datasets that cannot be simply read into R or other languages with a premade function like read.table(). The goal is to not manually read in each dataset by specifying which lines to read in each time, but to systematically find the data we need in each of the files and read it into R that way such that, hypothetically, if we had to read in hundreds of files simultaneously, we can use these functions I have built.

## Data:
Here are the file formats we will be reading and extracting data from: ".wea", ".pvsyst", and ".stat"

I will upload the files such that readers can view the full format of the files, but previews will be within the project. 

## Solution:
The goal of this project was to ease myself back into learning R and cleaning data with it. I also gained a lot of experience with regular expressions which made capturing the correct data frames possible. I used some basic ggplot2 to visualize the data for validation purposes, but there will be later projects that focus more on visualizations. The solution code is only shown on one of the data files, however it is validated across other files with the same format.
