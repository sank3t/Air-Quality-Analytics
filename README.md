## Air-Quality-Analytics

Analyzing the impact on air quality by the COVID-19 lockdown.

## Dataset Info

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

* **Bengaluru** is known as Silicon Valley of India and most of the tech companies has their headquarter in this city. This city is also known as most [traffic-congested city](https://timesofindia.indiatimes.com/city/bengaluru/bengaluru-has-worlds-worst-traffic-congestion-says-study/articleshow/73753146.cms).

## Notebooks

* [Data Collection](https://nbviewer.jupyter.org/github/sank3t/Air-Quality-Analytics/blob/main/notebooks/1.%20Data_Collection.ipynb)

* [Data Cleaning](https://nbviewer.jupyter.org/github/sank3t/Air-Quality-Analytics/blob/main/notebooks/2.%20Data_Cleaning.ipynb)

* [Data Preparation](https://nbviewer.jupyter.org/github/sank3t/Air-Quality-Analytics/blob/main/notebooks/3.%20Data_Preparation.ipynb)

## References

[1] [Bengaluru has world’s worst traffic congestion, says study](https://timesofindia.indiatimes.com/city/bengaluru/bengaluru-has-worlds-worst-traffic-congestion-says-study/articleshow/73753146.cms) (accessed Oct. 6, 2021).
