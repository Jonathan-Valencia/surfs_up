# surfs_up

- Advanced Data Storage and Retrieval with Jupyter Notebook, SQLite and SQLAlchemy

# Overview

- This project explores the power of Advanced Data Storage and Retrieval to efficently produce an analyis of temperature trends in Oahu, Hawaii. Specifically, summary statistics of temperature data were requested for the months of June and December, in order to determine if a prospective surf and ice cream shop business can sustainably operate year-round as opposed to a seasonal business.

# Deliverables

- Delivarable 1: Determine the Summary Statistics for June 
- Deliverable 2: Determine the Summary Statistics for December 
- Deliverable 3: A written report for the statistical analysis

## Results

- Summary Statistics DataFrame: June vs December Temperatures

<img width="509" alt="121727758-52fd6c80-caba-11eb-8e12-33676aa48ae8" src="https://user-images.githubusercontent.com/53058061/178880819-7293a0f0-4e3f-40df-a560-019dcdff19d9.png">


- June Recorded Temps Visualization (Temperature and Frequency)

<img width="503" alt="121729372-63aee200-cabc-11eb-81ad-075fa0e35b82" src="https://user-images.githubusercontent.com/53058061/178880853-5f7a7290-c4c6-4e7c-979c-30a52e0cab64.png">


- December Recorded Temps Visualization (Temperature and Frequency)

<img width="495" alt="121729393-69a4c300-cabc-11eb-853a-667622c4c960" src="https://user-images.githubusercontent.com/53058061/178880899-a786780d-0867-4f43-b0a4-76b0b016e718.png">


### Key Differences in Weather: Oahu, Hawaii

- The average recorded temperature in June is about 75 degrees F, 4 degrees higher than the average temp in December. This represents a -5% change in average temperature from June to December

- The frequency of temperatures recorded in June tends to have a much more normal, tight bell curve distribution, cooroborated by the smaller std measure of June temps vs December temps

- The December temperatures seem to be more variable than those in June given its larger range in recorded temperatures (comparing the max vs min temp of each month)
However, when looking at the plotted distribution of Dec Temps, we can see that the median temperature in Dec is more inline with the average, and there are not many outliers skuing the average temperature higher or lower than the actual recorded frequency.

# Summary

- Temperatures recorded in December seem to vary more than those of June, December would still provide appropriate weather conditions for both surfing and demand in ice cream. The average temperatures in June and December only differ by 4 degrees, and looking at the December histogram, I feel more confident in this decision--December's median temperature, with the highest frequency recorded across a span of years, is about 72 degrees, at least double the frequency of the next highest recorded temperatures, 75 and 67 respectively. It would be ill advised to not open the surf and ice cream shop based on at first clance temperature minimums.


Additional queries to get more color on weather conditions in these two months.Summary statistics of temperatures recorded by station for each month. This can help determine geopgraphically where in Oahu to build the prospective shop. By comparing the variances in temperatures and the frequencies recorded, we can narrow in on an optimal location.

- Stations vs Temps for June and December Starting Point

<img width="656" alt="121732019-af16bf80-cabf-11eb-90b5-a7918402c3b7" src="https://user-images.githubusercontent.com/53058061/178880977-2ce5bce9-f475-4baa-8072-96a3c912287d.png">



