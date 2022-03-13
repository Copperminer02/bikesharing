# bikesharing

## Overview

CitiBike is company which provides street side bike rentals with 1 time or subscription based services.  The rental bikes are available on street corners and can be rented via an app.  Such companies are currently operating in New York City, and as part of our exploration into creating a CitiBike in Des Moines, Iowa; August CitiBike ride data from NYC was evaluated for trends which could be applied to our venture.  

Using **Tableau**, a data visualization software, a online story of the visualization was created.  The description of these visualizations and their meaning will be detailed below.

## Resources

1. **NYC_Citibike_Challenge.ipynb** - jupter notebook code to convert trip duration into datetime data type.
2. **CitiBike Research** *Tableau story*  acessible with this link:  [link to dashboard](https://public.tableau.com/app/profile/josh.shutey/viz/CitibikeResearch/NYCityBikeData)

## Results

1.   **Basic Summary**
   ![image](https://user-images.githubusercontent.com/91850824/158039294-2ac4768d-f630-41f1-a49e-4969223f4f33.png)
   Defines basic summary number of rides and rides by time of Day.  In general, the peak demands sit around 5-6 PM and 8-9 AM.  These corespond with commuting hours.  Also, the low period from 2-4 AM provides an excellent window for maintenance.  Subscription based rentals appear to be the most popular, and the vast majority of the 2.2 M customers are male.

2.  **Start Locations**
  ![image](https://user-images.githubusercontent.com/91850824/158039442-8e05cf7f-1f2d-49de-ae2b-40cea66a2072.png)
  By plotting the start locations in NYC and sizing the markers by the number of rides from each location, a clear trend is present.  Downtown areas with high density and, in the case of NYC, high tourist potential are more frquently utilized.  THe outer burrows and areas are noticeably less used.
  
3. **Trip Duration**
   ![image](https://user-images.githubusercontent.com/91850824/158039495-28ea600d-37d3-40e3-80ec-8fd06a8bb299.png)
  This chart counts the frequency of rides compared by trip duration.  As can be seen, the majority if trips occur around 5 minutes.  Bike staging should consider placement within at least a half our from major downtown or entertainment districts.
  
4.  **Trip Duration by Gender**
  ![image](https://user-images.githubusercontent.com/91850824/158039604-b52ee883-5bf2-49bc-973a-3afb8e856618.png)
  Identical to trip duration, but filtered by gender type: male, female, and unknown.  This chart mirrors **Trip Duration** and confirms, most riders are male, and most trips are aimed at destinations with 5-10 minutes worth of riding.
  
5.  **Trip Heatmat by Day and time**
![image](https://user-images.githubusercontent.com/91850824/158039654-7232c65b-b343-4cf9-8f68-6eb66a1b863b.png)
This visualization creates a grid of hour and day.  The trip counts within the grid are colored by the amount of rides in teh period.  Not surprisingly the weekends from 10 AM and 8 PM are very popular, but more interesting, the dark bands at 8-9 AM and 5-6 PM are indications of the system being used in monring and evening commutes.

6.  **Trip Heatmat by Day, time, and gender**
  ![image](https://user-images.githubusercontent.com/91850824/158039746-7070141c-28fe-477c-bfdb-bc8a6f84876b.png)
  Again, this is a mirror image of **Trip Heatmat by Day and time** except three different heatmaps split the data by gender.  Again the data follows the same trend as the original across all genders.
  
7. **Heatmap Customer Type Compared to Day and Gender**
  ![image](https://user-images.githubusercontent.com/91850824/158039830-daa0a2c8-7aa6-4638-ba3c-a138ccedc540.png)
  This visualization compares ride counts for all genders by each day of the week.  The data is also split between wether the customer was a suscriber or a one use payemnt.  Looking at the customer data on top, the color looks pretty even indicating that one time payers use it fairly evenly during the week.  There are slightly darker colors on the weekends, but like the overall data suggests, most of the rides are subscriber based.  THe trends are also similar across genders.  
  
  Subscribers, although the weekends are still busy, have heavier usage Monday through Friday.  THese indiacte that subscribers are using this as transportation and not just for fun on the weekends.  
  
## Summary

### Visulatization Summary

  The above visualizations provide us with a lot of insight.  It appears that subscription services are the majority of the income and that placement of these bikes in high density downtown areas, colleges and entertainment districts are key.  Likewise, bike staging areas should be within 30 minutes ride distance to these hubs.  Given peak demand around commuting hours, it may be beneficial to stage these bike more towards commute location during the week (downtowns, colleges, hig density office spaces) and moved towards tourist and entertainment areas Friday through Sunday.  Maintenance and staging hours should be focussed between 3-5 AM.  
  
### Suggestions for future visualizations

1.  Compare trip start and end locations to day of week and time per day.   This could give more insight on placement opprtunities.
2.  We want to know what our main customers (subscribers) are doing.  Explore trip duration by subscriber category and map loactions for just subscribers.  THey take the most trips, any strategy should involve their trends and usage.  
  


  
  
  
