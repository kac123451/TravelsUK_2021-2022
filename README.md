# TravelsUK_2021-2022

# Ask
As we know Covid affected all of us, I was wondering how it impacted Travels and people behaviours to them, also show how big impact lockdown on people spending had

Goal of this analysis is to find out how UK residents travels changed before and after covid in 2020, is there any consequences in people behaviours to travel more often after lockdowns or change travel destinations and what could cause it, also as verfiy trends and exploratory analysis of UK travel behaviours, by forecast we will predict futher years of predicted travels
# Prepare
Source - https://www.ons.gov.uk/peoplepopulationandcommunity/leisureandtourism/datasets/travelpac

Release date:
20 July 2023


# Process

Download Data 3 files
travelpac
travelpac2021
travelpac2022

Export Excel File into 1 Folder TravelData and PDF Documentation into Information
TravelPac 2009-2019 Labelled
TravelPac 2021
TravelPac 2022

- Combine data 453,530 rows 14 columns

Create new Excel file 
Copy and Paste Each year dataset
Change Sheet Name - Travels 2009-2022

Modifications in PowerQuery:

Changed Age "D/K" to Unknown                        
Changed Sex "Dont know" to Unknown                 
Apply "Unknown" to Blanks                          
Some of rows didnt get moidified:
TRIM function on Quantitive data columns
Remove all rows with duration "Stay not known"  (-14451 rows)
Remove blanks rows from visits, nights, expend
Remove sample column
Cloan and Load 
439,079 rows






# Analysis

# Share

# Act
