# Surf Up
- SQLAlchemy
- Python Pandas on Jupyter notebook
## Overview of the Analysis
I have a hawaiin data temperature data on sql database. The client wants to know the weather description summary in June and December. So, I used SQLAlchemy on Python to connect to the database and collect the information I need. First, I created engine, inspected the data, extract the useful information in regards to its date, and created pandas DataFrame to display the info.
## Results
### 1. June Temp: 

![](https://user-images.githubusercontent.com/64121596/147046013-272e8d42-c4cb-43d1-89ed-4a1c5c7cf188.png)


### 2. Dec Temps: 

![](https://user-images.githubusercontent.com/64121596/147045966-b6cf818d-1aac-4288-92c7-86af58abd441.png)

### Differences between the 2 statistics tables:
1. In june, there were 1700 records have been written, whereas in december, it was 1517.
2. The highest temperature was 85F and minimum was 64F in June. Whereas, The highest temperature was 83F and minimum was 56F in December. It means that the range in June is 21F, while the range is 27F in December and the temprature could drop to 56F. 
3. The 75 percentile of the temprature in June was 77F, while it was 74F in December. It means that the temperature is higher in the summer.
## Summary
The 2 statistical tables above shows the comparison of the 2 temperatures in 2 different months, specifically in June and December. We could clearly see that the temperature is a little higher in June, but the mean temperature is close to each other. This means that the weather is stable all year long. 
We could add another query for the perception in June and December to illustrate how much rain we have and compare the 2 months. We could have data on the wind speed to determine how cold or warm it could feel during those 2 months. 
