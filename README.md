# UCSD Data Science and Visualization, 2019

Goals: To find, explore, clean, and analyze a large dataset

Inquiries:
1) To determine if there was a significant difference in the hourly temperature between New York and Philadelphia
2) To determine if a relationship exists between crime rates and temperature in various cities 

Measured hourly temperature data for various cities from Weather API and OpenWeatherMap from Kaggle: https://www.kaggle.com/selfishgene/historical-hourly-weather-data#humidity.csv 

Needed data of crime rates across multiple cities to be able to compare to the temperature, falling in the same year for the temperature data. Data collected from various Kaggle sources in different formats had to be cleaned up. Example of a Crime dataset: https://www.kaggle.com/currie32/crimes-in-chicago

Data was collected from 6 different sources mentioned in the references with various different formats. Large crime databases parsed using Python and Pandas.

We built functions in Python to perform a Paired t-test to determine if there was a significant differenct in hourly temperature between New York and Philadelphia. 

Addional graphs were created using Python and Matplotlib to visualize the relationship between crime and temperature. Appropriate correlation coefficients were calculated and displayed alongside the graphs.

Conclusions:
1) As expected we rejected the null hypothesis and concluded that there was a significant difference in hourly temperature between New York and Philadelphia in 2015.
2) There is a positive correlation between the temperature and crime rate for most cities. The highest correlation coefficient values were found in NYC (r=.962), Chicago (r=.889), and Philadelphia (r=.867). LA had a weak, postive correlation coefficient (r=.594) and Vancouver had a relatively insignificant r-value (r=.231).

Although our data supports the conclusion that Crime Rate increases as temperature increases, keep in mind that correlation does not mean causation!






