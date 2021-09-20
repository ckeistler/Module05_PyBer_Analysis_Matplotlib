# PyBer_Analysis
Module 5's focus was on introducing Matplotlib and Numpy alongside continued use and implementation alongside Pandas.  We were provided ride-sharing data in the form of two CSV files, city_data, which included data on city, driver count per city, and type of city (Urban, Suburban, Rural).  The second file, ride_data, included per ride information by city with date, fare, and ride_id fields.  Once merged, we constructed DataFrames using the groupby().count() and grouby().sum() functions, and we plotted line, bar, scatter, and box plots.
          
![Fig1](https://user-images.githubusercontent.com/88443672/133950993-9e9bbb90-8a34-4208-ae09-29f196117501.png)

![Fig2](https://user-images.githubusercontent.com/88443672/133950848-72876feb-2a21-4d4d-a329-a30f3ca8e771.png)


## Overview
The back story to Module 5's Challenge was the following, "V. Isualize has given you and Omar a brand-new assignment. Using your Python skills and knowledge of Pandas, you’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type. Finally, you’ll submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer."
  - Deliverable 1: A ride-sharing summary DataFrame by city type
  - Deliverable 2: A multiple-line chart of total fares for each city type
  - Deliverable 3: A written report for the PyBer analysis (README.md)

## Process
          - Deliverable 1 - 5 different DataFrames were built, and then a summary DataFrame was constructed from them.  From there, the summary DataFrame was formatted to                   achieve the desired view.
![deliverable1_code](https://user-images.githubusercontent.com/88443672/133951388-f4e98237-8ece-4316-b50e-257d895b7528.png)
![avg_fare_code](https://user-images.githubusercontent.com/88443672/133951394-9ad0afcd-6bd3-42e5-b10d-bf75093c255e.png)
![pyber_summary_code](https://user-images.githubusercontent.com/88443672/133951396-2866976f-27f3-4ca1-8d7a-d01a3211bf68.png)


          

## Results
The ride sharing data showed that the majority of rides were in an urban setting (68.4%), while suburban cities accounted for 26.3% of the total ride count.  Rural cities only accounted for 5.3% of the total data.
![Fig6](https://user-images.githubusercontent.com/88443672/133951019-75311c65-6a69-483f-aeb5-58002fb610eb.png)

As the the total ride data would suggest, total drivers are allocated in a similar fashion.  
          - 80.9% of total drivers are in an Urban setting
          - 16.5% of drivers were listed in Suburban Cities
          - 2.6% of drivers were listed in Rural Cities
![Fig7](https://user-images.githubusercontent.com/88443672/133951021-a58a69a9-784a-4430-9a8e-385dcdf113fb.png)


![PyBer_fare_summary](https://user-images.githubusercontent.com/88443672/133951026-ddada471-e518-41f0-90c0-3f6e437f6eb2.png)



## Summary
