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

## Technologies Used -
        Pandas
        Jupiter Notebook
        Visual Studio Code
        Tableau Public Server (to publish)
        Tableau Desktop

## Project Split up -
    (1) CitiBike analysis for (the summer month of) September of 2019 - Dashboard and Story 
    (2) CitiBike analysis for September of 2021-22 - Dashboard and Story
    (3) CitiBike analysis for September of pre- and post-Pandemic years (2019, 2020, 2021) - Mini Project
    

# CitiBike analysis for September of 2019 - Dashboard and Story

Data chosen for this part of the project was September 2019. The selection of this dataset was done (1) to avoid any affects from adverse weather conditions and (2) also to capture what the CitiBike stats have been for this month, before the Pandemic hit NewYork.

![citibike 1](https://github.com/fbrowther/Tableau-Citi-Bike-Project/blob/main/Images/CitiBike%202019.png)

(1) Interactive dashboard -
https://public.tableau.com/app/profile/farjana.rowther/viz/CitiBikeDataAnalytics-Summer2019/Dashboard-CitiBikeSep2019

(2) Interactive Story - 
https://public.tableau.com/app/profile/farjana.rowther/viz/CitiBikeSep2019-Story/Sep2019

## Summary of the findings -
        (1) Users rode bikes between the window of 6:00 - 22:00 with a peak hours of commute between (8:00-9:00)am and (17:00-18:00)pm
        (2) User numbers remained consistent through the week. The ratio of Subscribers to Casual users remained higher throughout the week. Suscribers 
            used more during weekdays and casual riders over the weekends.
        (3) The average duration of trip by subscribers remained under 1000 Seconds (~15 mins). The (Pay As You Go) customers however used bikes for an
            extended duration of time ranging from 30-45mins. 
        (4) The age of users (born from 1970-2005) didnot affect the trip time.
        (5) Male riders (abbreviated as 1) were 2.5 times more compared to female riders (abbreviated as 2). Approx 10% users didnot provide the gender
            information.
        (6) Citi Bike's top 20 starting tations in Sep 2019 concentrated in Manhattan Borough. The top station was 'West St & Chambers St'.
        (7) Top 20 Ending Stations in Sep 2019 concentrated again in Manhattan Borough. The top ending station was also 'West St & Chambers St'.
        (8) Most importantly the top 10 Starting and Ending Stations remained almost the same, indicating customers used this mode of transport between
            these stations more often for commute.

# CitiBike analysis for September of 2021-22 - Dashboard and Story

For this part of the analysis, September 2021 and 2022 data was collected, combined and analysed to see any insights that was evident (for these post pandemic years). The choice of these post pandemic summer months were done in order to compare them with Sep 2019 data. 

Citibike has started to archieve the data since 2021 in a different format than all the previous years. These changes included no availability of data for gender, birthyear information of the riders and tripduration. Hence, the comparison couldnot be done for these variables. However, for these two years, Citibike started to include information about the type of bike (Classic, Electric, or Docked) which was handy for some extra analysis.

![citibike 1](https://github.com/fbrowther/Tableau-Citi-Bike-Project/blob/main/Images/CitiBike%202021-22.png)

(1) Interactive dashboard -
https://public.tableau.com/app/profile/farjana.rowther/viz/CitiBikeDataAnalyticsSep2021-22/Dashboard1

(2) Interactive Story - 
https://public.tableau.com/app/profile/farjana.rowther/viz/CitiBikeDataAnalyticsSep2021-22-Story/Story-202122

## Summary of the findings -
        (1) Electric bikes accounted for 1/5 of the total bikes available to use.
        (2) Two distinct peak of travel times around (8-9am) and (5-6pm) slowly returned after the Pandemic.
        (3) Total trips was appr. 3.3 Million per year for both 2021 and 2022
        (4) The relationship of top 10 starting and end stations was interesting to note.
            Central Park was on the top for both starting and ending journey in Sep 2021-22.
        (5) Top 10 starting stations concentrated primarily in the Manhattan area similar to previous occasions.
        

## CitiBike User Analysis for the Summer of pre- and post-Pandemic years (2019, 2020, 2021)-Mini Project

(1) Top 10 Starting Stations
![citibike 1](https://github.com/fbrowther/Tableau-Citi-Bike-Project/blob/main/Images/PrePost-StartStations.png)

For interactive visualization:

(https://public.tableau.com/app/profile/farjana.rowther/viz/CitiBikeT10StartingStationsPrePostPandemic/Dash-T10StartingStations)


(2) Top 10 Ending Stations
![citibike 1](https://github.com/fbrowther/Tableau-Citi-Bike-Project/blob/main/Images/PrePost-EndStations.png)

For interactive visualization:

(https://public.tableau.com/app/profile/farjana.rowther/viz/CitiBikeT10EndingStationsPrePostPandemic/Dash-T10EndStations)

(3) Peak time of ride
![citibike 1](https://github.com/fbrowther/Tableau-Citi-Bike-Project/blob/main/Images/PrePost-Peaktime.png)

For interactive visualization:

(https://public.tableau.com/app/profile/farjana.rowther/viz/CitiBikePeakTravelTimePrePostPandemic/Dash-PeakTimeofTravel)

(4) Ride duration
![citibike 1](https://github.com/fbrowther/Tableau-Citi-Bike-Project/blob/main/Images/PrePost-Tripduration.png)

For interactive visualization:

(https://public.tableau.com/app/profile/farjana.rowther/viz/CitiBikeTripDurationPrePostPandemic/Tripduration)


## Limitations of the Project -

(1) Working initially on these projects on tableau public and saving to tableau public server was very slow.  Sometimes the server crashed only to loose the analysed data. The work had to be repeated on Tableau Desktop which allows to save local copies of the files at every stage of the project.

(2) The format of data archived by Citi Bike has changed. These changes included no data availability for gender, birthyear or tripduration since 2021. 
Citibike has now started to archieve information about the type of bike (Classic, Electric, or Docked) from 2021 which came handy for some extra analysis.
These changes in data format and information availability also meant that data for all the years (2019-2022) could not be combined to carryout the analysis.

## Data files used -
The data files were too large to be uploaded onto this repository. Hence, the details of the data files that were used (from the CitiBike website) are provided.

(1) 201909-citibike-tripdata.csv.zip

(2) 202009-citibike-tripdata.csv.zip

(3) 202109-citibike-tripdata.csv.zip

(4) 202209-citibike-tripdata.csv.zip
 

