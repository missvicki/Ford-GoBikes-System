# Ford GoBikes System Data
## by Victor Nomwesigwa


## Dataset

This project focuses on visualizing the [Ford GoBike System data set](https://www.lyft.com/bikes/bay-wheels/system-data) that includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

Features included the data set are:

- Trip Duration (seconds)
- Start Time and Date
- End Time and Date
- Start Station ID
- Start Station Name
- Start Station Latitude
- Start Station Longitude
- End Station ID
- End Station Name
- End Station Latitude
- End Station Longitude
- Bike ID
- User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
- Member Year of Birth
- Member Gender

## Summary of Findings

In the exploration, I discovered that average bike rides take a short duration of about 10 min. I continued to explore and see if weather or seasons affect the trip duration and it turned out that weather has a less significant effect. I attributed this to the good weather of San Francisco which is mostly warm. However, I also noticed that the longest trip durations happen during summer.

I also wanted to find out if the above was due to users subscribing differently considering the fact that we had subscribed customers and customers who just rented bikes every once in a while. Turns out that that is not the case. However, studies showed that there are more customers who are not subscribed than those who are subscribed. Finally, I noticed that subscribed customers usually had long trip durations of above 300 minutes.


## Key Insights for Presentation

For this presentation I focused on studying the trip duration. I had to do a conversion of trip duration to minutes as seconds are hard for any non-mathematician to work with and understand. I made use of histograms to show the distribution of trip duration and scatter plots and heat maps to understand the relationships between trip duration and months and user types. 

## What is needed to run this project?
- Python
- Pandas
- Numpy
- Matplotlib
- Jupyter Notebook
