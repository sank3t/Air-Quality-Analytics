## Air Quality Analytics

Analyzing the impact on air quality by the COVID-19 lockdown.

## Dataset Description

### Data Source

The data is collected from [Berkeley Earth](http://berkeleyearth.org). Berkeley Earth provides open access to the high quality hourly **PM2.5** data by different countries.

### Data Dictionary

| Column        | Description                                 |
|:--------------|:--------------------------------------------|
| timestamp_utc | Data collected at hourly granularity in UTC |
| pm2.5         | concentration of pm2.5 in μg/m<sup>3</sup>  |


### Locations for analysis

For the analysis following cities are picked:

* [Aligarh](https://en.wikipedia.org/wiki/Aligarh)

* [Bengaluru](https://en.wikipedia.org/wiki/Bangalore)

* [Gurgaon](https://en.wikipedia.org/wiki/Gurgaon)

* [Mohali](https://en.wikipedia.org/wiki/Mohali)

#### Reason for picking the above location

* **Aligarh** is my hometown and is also known as _City of Locks_. Having a numerous large scale manufacturing units in this city, will like to study the how lockdown really impacted the air quality in this city.

* **Bengaluru** is known as _Silicon Valley of India_ and most of the tech companies has their headquarter in this city. This city is also known as most [traffic-congested city](https://timesofindia.indiatimes.com/city/bengaluru/bengaluru-has-worlds-worst-traffic-congestion-says-study/articleshow/73753146.cms).

* **Gurgaon** is the second largest IT Hub of India and is home to the many startups. Apart from IT it is also home to huge manufacturing units like Maruti Suzuki.

* **Mohali** is the place where I spent most of the time from the beginning of 2019. This city is closed to the hilly areas and most of the part is covered by trees.

## Notebooks

* [Data Collection](https://nbviewer.jupyter.org/github/sank3t/Air-Quality-Analytics/blob/main/notebooks/1.%20Data_Collection.ipynb)

* [Data Cleaning](https://nbviewer.jupyter.org/github/sank3t/Air-Quality-Analytics/blob/main/notebooks/2.%20Data_Cleaning.ipynb)

* [Data Preparation](https://nbviewer.jupyter.org/github/sank3t/Air-Quality-Analytics/blob/main/notebooks/3.%20Data_Preparation.ipynb)

* [EDA](https://nbviewer.org/github/sank3t/Air-Quality-Analytics/blob/main/notebooks/4.%20EDA.ipynb)

## References

[1] [Bengaluru has world’s worst traffic congestion, says study](https://timesofindia.indiatimes.com/city/bengaluru/bengaluru-has-worlds-worst-traffic-congestion-says-study/articleshow/73753146.cms) (accessed Oct. 6, 2021).

[2] [What Is PM 2.5 and How Can You Reduce Your Exposure?](https://molekule.science/what-is-pm-2-5-and-how-can-you-reduce-your-exposure/) (accessed Oct. 7, 2021).

[3] [Revised PM2.5 AQI breakpoints](https://aqicn.org/faq/2013-09-09/revised-pm25-aqi-breakpoints/) (accessed Oct. 7, 2021).
