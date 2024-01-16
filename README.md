# Smart Device Project
Working on interpreting insights and trends from smart devices data.

## Table of Contents
1.[Introduction](#introduction)

2.[Getting Started](#getting-started)

3.[Features](#features)

4.[Data](#data)

5.[Analysis](#analysis)

6.[Results](#results)

7.[Recommendations](#recommendations)

##  Introduction
Welcome to the Smart Devices Project, the complete data analysis process is performed on R, this project delves into the intricate details of participants' daily activities,focusing on aspects such as hourly steps,average daily steps, sleep duration and caloric expenditure. By analyzing these key metrics we aim to uncover trends,patterns and insights that provide a holistic view of participants' lifestyles.

## Getting Started

You are a junior data analyst working on the marketing analyst team at Bellabeat, a high-tech manufacturer of health-focused
products for women. Bellabeat is a successful small company, but they have the potential to become a larger player in the
global smart device market. Urška Sršen, cofounder and Chief Creative Officer of Bellabeat, believes that analyzing smart
device fitness data could help unlock new growth opportunities for the company. You have been asked to focus on one of
Bellabeat’s products and analyze smart device data to gain insight into how consumers are using their smart devices. The
insights you discover will then help guide marketing strategy for the company. You will present your analysis to the Bellabeat
executive team along with your high-level recommendations for Bellabeat’s marketing strategy.

These questions
will guide your analysis:
1. What are some trends in smart device usage?
2. How could these trends apply to Bellabeat customers?
3. How could these trends help influence Bellabeat marketing strategy?

Sršen encourages you to use public data that explores smart device users’ daily habits. She points you to a specific data set:
● FitBit Fitness Tracker Data (CC0: Public Domain, dataset made available through Mobius): This Kaggle data set
contains personal fitness tracker from thirty fitbit users. Thirty eligible Fitbit users consented to the submission of
personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring. It includes
information about daily activity, steps, and heart rate that can be used to explore users’ habits.
Sršen tells you that this data set might have some limitations, and encourages you to consider adding another data to help
address those limitations as you begin to work more with this data.



## Features
1.**Hourly Steps Trend:**
-Explore trends and patterns in steps recorded per hour throughout the day.

2.**Average Daily Steps:**
-Gain insights into participants' overall activity levels through the evaluation of average daily steps.

3.**Sleep Duration Analysis:**
-Uncover patterns and trends in participants sleep habits with an indepth analysis of sleep duration data.

4.**Calories Analysis:**
-Explore variations in participants' energy expenditure by analyzing trends in calories burned.

5.**Average Weight:**
-Understanding the average weight distribution among particiants.

6.**Results and Insights:**
-Summarize key findings and insights obtained from the analysis to draw meaningful conclusions.


## Data

### Cleaning and Preprocessing
Data was downloaded from Kaggle as a zip folder containing 18 csv files, files containing varying numbers of columns and rows which were sorted,cleaned and merged for further analysis

## Analysis

### Hourly Steps Trend
After cleaning and analyzing data,a line chart was created using the R software package, it was observed that most participants had the highest number of steps at the 18th hour,totalling 542,828 steps from all participants combined.

### Average Daily Steps
Using a line chart plotted in R, the highest points are noticed at April 16th and May 5th which indicates that most people walked more around those periods, however the chart was more at the consolidation period of 7,000 - 8-000 steps.

### Sleep Duration Analysis
Using a histogram to display the frequency and total minutes of sleep, it was noticed that the peak period of the sleep duration falls highly around 400 minutes which is around 6hours daily.

### Calories Analysis
Loking for a trend in the average calories burned by all participants, a ine charted was plotted which shows the average calories burned was around 2,250 from April to May.

### Average Weight Analysis
Using R,to find the mean of the participants' weight and a bar graph to plot the Average ID against Weight, it was observed the average weight is 77.8kg.

## Results

### Insightful from hourly steps
From the analysis, it was observed that the maximum number of steps were taken at 6pm and 7pm, 542828 and 528552 steps respectively while the least amount of steps were taken at 3 and 4am,5996 and 11836 respectively

### Key Findings from Daily Steps and Sleep Duration
Using insights from the correlation matrix calculated between Total steps taken and Total Minutes asleep, there is negative correlation between the two variables with the value at -0.09854146 which is very close to zero, indicating that as the steps increases the minutes of asleep reduces and vice versa. The weak negative correlation suggests that there is a slight tendency for people with more steps to have fewer total minutes of sleep and vice versa. However, the correlation is not strong enough to make definitive conclusions about the relationship between these two variables.

### Calories Burned Trends
Observing the calorie trend, the average distribution of calories burned daily is between 2,250 and 2,300 calories while the total calories arranged in descending order by participants has shown that the most calories burned is 106,534 and 7,895 as the least burned.

# Summary
After careful analysis of the various trends observed from the data,the following marketing strategies are suggested for Bellabeat:

-Engaging in marketing more sleep-related products and emphasizing how the products suppport healthy sleep habits as the mean values for sleep duration are typically between 300-400minutes

-Target more fitness groups as the trend shows that most people tend to walk more, hence they tend to be more active around 6 and 7pm which could either be as a result of evening activities or actively engaging in fitness and wellness.

-More features should be integrated that resonates with tracking daily activties and sleep monitoring, the analysis suggests an opportunity to also integrate marketing messages to emphasize how Bellabeats products provide a holistic approach to health by addressing both sleep quality and physical activity.

-Focusing on creating educational content which tells people about the importance of balanced sleep and physical activity, Bellabeats product can be positioned as that tool which can help users make informed decisions with regualr updates and suggestions on how to achieve those goals

-Incorporating customer testimonials and success stories into the marketing strategy will be helpful in letting potential customers see the benefits and how Bellabeats products hace increased physical activity, improved sleep and overall wellbeing of an indivual
