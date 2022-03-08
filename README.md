
# Air Quality Index (AQI) across stations and cities in India from 2015 to 2020
 
I have taken an AQI dataset from Kaggle and performed some EDA on it as well as implemented a decision tree classiifer to classify the air quality into one of the six buckets:

1. Good
2. Moderate
3. Satisfactory
4. Poor
5. Very Poor
6. Severe
- The dataset is taken from Kaggle.
- It contains air quality data and AQI (Air Quality Index) at hourly and daily level of various stations across multiple cities in India from 2015 to 2020.
- For this particular project, I have used just a part of the datasets provided in Kaggle, which contains day-wise city air pollution data.

Libraries used:

```bash
1. Numpy
2. Pandas
3. Seaborn
4. Chart Studio
5. Plotly
6. Pandas Profiling
7. PyCaret
```

I have used Pandas for performing exploratory data analysis and PyCaret for performing the machine learning classification task.

# Some Exploratory data analysis (EDA)

1. Dataframe

![Dataframe](https://github.com/RoshanKrSharma/AQI-Data-analysis/blob/main/images/dataframe.png)

2. Plotting of top 10 most polluted cities v/s various pollutants
 
![cities v/s PM](https://github.com/RoshanKrSharma/AQI-Data-analysis/blob/main/images/1.%20plotting%20top%2010%20cities%20vs%20pollutants.png)
![cities v/s Nitric](https://github.com/RoshanKrSharma/AQI-Data-analysis/blob/main/images/2.%20plotting%20top%2010%20cities%20vs%20pollutants.png)
![cities v/s SO](https://github.com/RoshanKrSharma/AQI-Data-analysis/blob/main/images/3.%20plotting%20top%2010%20cities%20vs%20pollutants.png)
![cities v/s NH3](https://github.com/RoshanKrSharma/AQI-Data-analysis/blob/main/images/4.%20plotting%20top%2010%20cities%20vs%20pollutants.png)
![cities v/s O3](https://github.com/RoshanKrSharma/AQI-Data-analysis/blob/main/images/5.%20plotting%20top%2010%20cities%20vs%20pollutants.png)
![cities v/s SO2](https://github.com/RoshanKrSharma/AQI-Data-analysis/blob/main/images/6.%20plotting%20top%2010%20cities%20vs%20pollutants.png)
![cities v/s BTX](https://github.com/RoshanKrSharma/AQI-Data-analysis/blob/main/images/7.%20plotting%20top%2010%20cities%20vs%20pollutants.png)

3. Top 10 cities v/s AQI plotting

![cities v/s AQI](https://github.com/RoshanKrSharma/AQI-Data-analysis/blob/main/images/8.%20plotting%20top%2010%20cities%20vs%20pollutants.png)

4. Yearly trend of air quality in each cities

![Yearly trend](https://github.com/RoshanKrSharma/AQI-Data-analysis/blob/main/images/yearly%20trend%20of%20air%20quality%20in%20each%20cities.png)

5. Now we will see difference of AQI in 2019 and 2020

_As we know complete lockdown was there in India from march 2020, so there must be significant decrease in AQI_
![AQI difference in 2019 and 2020](https://github.com/RoshanKrSharma/AQI-Data-analysis/blob/main/images/AQI%20between%202019%20and%20march%202020.png)

6. Analysing which pollutant was most decreased in year 2020 in comparision to 2019
![](https://github.com/RoshanKrSharma/AQI-Data-analysis/blob/main/images/2020%20in%20comparision%20to%202019.png)
where BTX = Benzene + Toluene + Xylene



