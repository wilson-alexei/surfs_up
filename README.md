# surfs_up
Utilizing `Python`, `Jupyter Notebook`, `SQLAlchemy`, `SQLite`, and `Flask` to properly analyze data and run analytics on a weather dataset. 

## Overview
W. Avy likes your analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round. We will be using the `hawaii.sqlite` database to create the report, analysis, and summary stastistics for Module 9 challenge. 

## Results
In Deliverables 1 and 2, we have filtered the temperatures for the month of June and December using `Python` and `Jupyter Notebook` and transform into a DataFrame where we can create a summary statistics to accurately and efficiently analyze and see the difference in weather between the month of June and December. 

> For Deliverable 1, we filtered the temperature of the Oahu island in the month of **June** for analysis. Here is the summary statistic: 
<img width="845" alt="juneDF" src="https://user-images.githubusercontent.com/95068439/155815248-3a702c9e-4496-46f7-87d7-648d49da9ec8.png">

> For Deliverable 2, we filtered the temperature of the Oahu island in the month of **December** for analysis. Here is the summary statistic: 
<img width="889" alt="decemberDF" src="https://user-images.githubusercontent.com/95068439/155815351-c04c37ee-693f-46ab-be34-b383331593be.png">

As we can see from the summary statistics, there is a significant differences in the temperatures between June and December:
  * The MINIMUM temperature in June (64˚F) is much lower than in December (56˚F). This is about 8˚F difference between thw two months. December temperature is lower than June as it is the winter season while June is the summer season where the weather is nicer and potentially attract more tourists and visitors. 
  * The STANDARD DEVIATION of December is approximately 3.746 while the month of June's STANDARD DEVIATION is approximately 3.257. The difference between the two months or seasons is roughly about 0.50
  * The difference of the MEAN between the months/seasons is not that huge which is interesting considering it is winter and summer as the temperature is usually significantly different. The MEAN of temperature in June is approximately 75.0˚F while in December is approximately 71.0˚F which is only about 4.0˚F different. This data determines that the surf and ice cream shop business is sustainable year-round. 


## Summary
With the data analysis created, it will help us determine if the surf and ice cream shop business is sustainable year-round. It will also help us decide on which areas we would make this location attractive for tourists and vistors to stop by and for the shop to consistently have good number of sales and bringing in enough revenues. We can potentially improve our data analysis by adding two more additional queries that will analyze the precipitation data and the stations data that record the daily temperatures. These two queries can increase the accuracy of data in terms of picking the right location that can bring in good traffic and interaction tourist and visitors all year long to bring in more sales and revenue without having the seasons significantly affecting the shop operation.




`LinkedIn: /www.linkedin.com/in/wilson-alexei/`

`Email: wils.alexei@gmail.com`
