# Data Analysis on Singapore Carpark Availability Dataset 

Perform data analysis on the [carpark availability dataset](https://data.gov.sg/dataset/carpark-availability) provided by the Singapore government.

## Details

For better view experience of `ipynb` files, you can use [nbviewer](https://nbviewer.org/).

In Q1, A function for **api call and return values processing** is provided in Appendix. Some features about dataset, code for data values update frequency testing and carpark correlation analyse are also provided.

In Q2, A model for **hourly carpark availability forecast** in the future is built. The reason why we build this model and the analysis on models using different  regressor (i.e., linear regression, support vector regressor and decision tree regressor) are also provided. Some parameter tuning are done for better performance.

In Q3, all the carparks are clustered and  and separate models are built for each cluster. Combined with [geographical information](https://data.gov.sg/dataset/hdb-carpark-information) of these carparks (which is also provided by Singapore government), we can **return the top five closest carparks and their corresponding predicted vacancies for a given location and time**. We have also designed the UI of this application.

## Announcement

This is our team's final report for course EE4211 at NUS for Sem1, AY2022/23. I worked as a team leader, together with [JingkeiHau](https://github.com/JingkeiHau), [xiaolei1998](https://github.com/xiaolei1998) and [WhianGaulin](https://github.com/WhianGaulin). 

**For communication and study use only.** 
