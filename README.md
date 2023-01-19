# Tableau-Citi-Bike-Analytics Project

![citibike 1](https://user-images.githubusercontent.com/111912050/213473240-0ad6b610-bb5b-4f40-a2b1-d04f7a9f3b2d.jpeg)


## Brief Introduction:
The Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, data is collected, organized, and made public on the Citi Bike Data webpage (https://citibikenyc.com/system-data). 

As a part of this project, I was required to analyse the chosen data (month/year) to look for significant insights to report. 

## Important questions that was asked, included -
    (1) How many trips have been recorded in total during the chosen period?
    (2) By what percentage has total ridership grown?
    (3) How have the proportions of short-term customers and annual subscribers changed?
    (4) What are the peak hours when bikes are used during the summer months?
    (5) What are the top 10 stations in the city for starting a journey?
    (6) what are the top 10 stations in the city for ending a journey? 
    (7) How does the average trip duration change by age?
    (8) What is the average distance in miles for a bike trip?

## Technologies Used -
        Jupiter Notebook
        Tableau Public Server (to publish)
        Tableau Desktop

## Project Split up -
    (1) CitiBike analysis for (the summer month of) September of 2019 - Dashboard and Story 
    (2) CitiBike analysis for September of 2021-22 - Dashboard
    (3) CitiBike analysis for September of pre- and post-Pandemic years (2019, 2020, 2021) - Mini Project
    

# CitiBike analysis for September of 2019 - Dashboard and Story

The data was chosen for the month of September, for this part of the project. The selection of this dataset was done (1) to avoid any affects from adverse weather conditions and (2) also to capture what the CitiBike stats have been for this month before the Pandemic hit NewYork.

(1) Interactive dashboard -
https://public.tableau.com/app/profile/farjana.rowther/viz/CitiBikeDataAnalytics-Summer2019/Dashboard-CitiBikeSep2019


![citibike 1](https://github.com/fbrowther/Tableau-Citi-Bike-Project/blob/main/Images/CitiBike%202019.png)


(2) Interactive Story - 
https://public.tableau.com/app/profile/farjana.rowther/viz/CitiBikeSep2019-Story/Sep2019

## Summary of the findings -
        (1) Users commuted between the window of 6:00 - 22:00 with a peak hours of commute i.e., (8:00-9:00)am and (17:00-18:00)pm
        (2) User numbers remained consistent through the week. The proportion of Subscribers/Casual users is higher throughout the week. Suscribers used 
            more during weekdays and  casual riders
        (3) The average duration of trip by subscribers remained under 1000 Seconds (~15 mins). The (Pay As You Go) customers used for an extended duration
            of time (~30-45mins). The age of users didnot affect the usage time.
        (4) Male (1) riders were 2.5 times compared to female (2) riders. App 10% users didnot provide the gender information.
        (5) Citi Bike's top 20 Starting Stations in Sep 2019  concentrated in Manhattan Borough. The top station was West St & Chambers St.
        (6) Top 20 Ending Stations in Sep 2019  concentrated in Manhattan Borough. The top ending station was West St & Chambers St.
        (7) The Top 10 Starting and Ending Stations remained almost the same!

# CitiBike analysis for September of 2021-22 - Dashboard and Story

For this part of the analysis, data for the month of September 2021 and 2022 was collected, combined and analysed to see distinct insights that was evident for these post pandemic years. Citibike started to archieve the data for the years 2021 onwards a little bit differently to all the previous years. These changes included no data availability for gender, birthyear information of the riders and tripduration. However, for these two years, Citibike started to archieve information about the type of bike (Classic, Electric, or Docked).

Interactive dashboard -
https://public.tableau.com/app/profile/farjana.rowther/viz/CitiBikeDataAnalyticsSep2021-22/Dashboard1

![citibike 1](https://github.com/fbrowther/Tableau-Citi-Bike-Project/blob/main/Images/CitiBike%202021-22.png)

(2) Interactive Story - 
https://public.tableau.com/app/profile/farjana.rowther/viz/CitiBikeDataAnalyticsSep2021-22-Story/Story-202122

## Summary of the findings -
        (1) Electric bikes accounted for 1/5 of the total bikes available.
        (2) Two distinct peak of travel times around (8-9am) and (5-6pm) slowly returned after the Pandemic.
        (3) Total trips per year (for 2021 & 2022) was appr. 3.3 Million.
        (4) The relationship of top 10 starting and end stations. Central Park was on the top for both starting and ending the journey in 2021-22.
        (5) Top 10 starting stations concentrated primarily in the Manhattan area.
        

## CitiBike analysis for the summer of pre- and post-Pandemic years (2019, 2020, 2021) - Mini Project

(1) Top 10 Starting Stations
(https://public.tableau.com/app/profile/farjana.rowther/viz/CitiBikeT10StartingStationsPrePostPandemic/Dash-T10StartingStations)
![citibike 1](https://github.com/fbrowther/Tableau-Citi-Bike-Project/blob/main/Images/PrePost-StartStations.png)

(2) Top 10 Ending Stations
(https://public.tableau.com/app/profile/farjana.rowther/viz/CitiBikeT10EndingStationsPrePostPandemic/Dash-T10EndStations)
![citibike 1](https://github.com/fbrowther/Tableau-Citi-Bike-Project/blob/main/Images/PrePost-EndStations.png)

(3) Peak time of ride
(https://public.tableau.com/app/profile/farjana.rowther/viz/CitiBikePeakTravelTimePrePostPandemic/Dash-PeakTimeofTravel)
![citibike 1](https://github.com/fbrowther/Tableau-Citi-Bike-Project/blob/main/Images/PrePost-Peaktime.png)

(4) Ride duration
(https://public.tableau.com/app/profile/farjana.rowther/viz/CitiBikeTripDurationPrePostPandemic/Tripduration)
![citibike 1](https://github.com/fbrowther/Tableau-Citi-Bike-Project/blob/main/Images/PrePost-Tripduration.png)


## Limitations of the Project -

(1) Working initially on these projects on tableau public and saving to tableau public server was so slow.  Sometimes the server crashed only to loose the analysed data. The work had to be repeated on Tableau Desktop which allows to save local copies of the files.

(2) The format of data archived by Citi Bike has changed. These changes included no data availability for gender, birthyear or tripduration since 2021. Citibike has now started to archieve information about the type of bike (Classic, Electric, or Docked) from 2021 which came handy for some extra analysis. 


 

