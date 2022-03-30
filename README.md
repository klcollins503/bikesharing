# bikesharing
## Purpose
This study was commissioned to analyse NYC CitiBike bikesharing program and assess its adaptability to other potential metro areas. Public data was used from August 2019. Tableau Public and Jupyter Notebook were the tools used.
## Overview
This project consisted of 2 phases, the first phase was all in Tableau. Graphs and charts we created showing different user groups, start/stop times and locations. After phase 1, it was decided that the Duration integer field would be better represented as a datetime. A pandas dataframe was created in Jupyter Notebook and the integer field was converted to datatime.

## Results
The newly created datetime ride duration field was used to create the following graphic showing trip duration and number of rides:

<img width="442" alt="checkoutTimeUsers" src="https://user-images.githubusercontent.com/95047485/160747647-5d3ee6c5-de29-46f1-98b3-28f798ffec5c.PNG">

This shows the most frequent ride duration in hours and minutes.

Next, it would be important to show the gender breakdown of the riders, so this next graphic was created by adding gender as a filter in the checkout times graphic.


<img width="440" alt="checkoutTimeGenders" src="https://user-images.githubusercontent.com/95047485/160747869-f322d767-ced6-4988-a5a9-b3d24b0012bb.PNG">


The results give an excellent view into the types of users, see story for subscribers vs customers breakouts, in the Citibike program in NYC. While these results look promising for future bikeshare programs, there is more data needed to assess vitality in other metro areas. Traffic data should be assessed in the target city, as well as bike path infastructure, number of ridable days due to weather, and possibly even a consumer survey to gauge interest levels. In smaller metros where property and apartments are more spacious people might be more likely to own a bike rather than rent or share. And the tendency to ride a bike could be influenced by the overall city footprint and how long the average commutes are.

Please visit the following link for interactive charts in the NYC Citibike data story:

[Link to Tableau Story](https://public.tableau.com/app/profile/kim.collins3319/viz/BikeShare_16478156580320/NYCCitybike?publish=yes)
