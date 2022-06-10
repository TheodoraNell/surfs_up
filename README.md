# Surf's Up Analysis

Exploring Oahu, Hawaii weather data with SQLite and Pandas

## Purpose

The purpose of this analysis is to isolate weather data for the months of June and December, specifically temperature and precipitaion. The data then explored through summary statistics to uncover trends that coule possibly impact the performance of a business selling ice cream and surf gear. 

## Results

![june_temps](https://user-images.githubusercontent.com/99051640/172963761-4fb04d0c-1f9b-4ba9-9c13-990fad0fc044.png)
![dec_temps](https://user-images.githubusercontent.com/99051640/172963767-baa51032-dcca-46db-b914-89fd6509f0e3.png)

- **Average temperature is fairly consistent in June and December:**  
  The average temperature for June is around 75 degrees and December is around 71 degrees. The maximum temperatures are 85 and 83 degrees respectively. 

- **The temperature values are evenly distributed:**  
  In both June and December the average temperature is almost exactly the same as the 50th percentile, or median. 

- **There is a notable variance in the minimum temperatures:**  
  The minimum temperature for December is 56 degrees which is 8 degrees colder than the minimum for June which is 64 degrees. This could mean that in December there would be days where the demand for ice cream especially may potentially drop considerably. It would be interesting to compare data for ice cream sales vs temperature. 

## Summary 

With temperatures staying relatively consistent and warm throughout June and December, establishing as surf shop / ice cream stand seems a reasonable endeavor. Aside from a few colder days, most days in both months will most likely have weather warm enough for ice cream demand. 

However, since Hawaii can also be known for having rainy days it is also worth exploring the precipitaion data for both months as well: 

![june_prcp](https://user-images.githubusercontent.com/99051640/172965277-85877785-7bed-4e6e-9997-b3dcdc3ecdbb.png)
![dec_prcp](https://user-images.githubusercontent.com/99051640/172965291-9a201307-df9f-4044-9b34-3c01dc5b6041.png)

When comparing the summary statistics, it appears that similar to cold days in December, there are a days where there was a rainfall of several inches. However, looking more closely at the percentiles, most days saw little to no rainfall. A deeper exploration of rainfall by month, especially in the spring and fall months, could provide further insight. Even on warm days, rain may be a detering factor for both purchasing ice cream and surfing. 

