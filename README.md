# Analyzing Maritime Ports and their Vessel Traffic 
### Amazon Web Services, AWS ATHENA, AWS GLUE, SQL


In this project I used AWS to create an S3 bucket. I then created a database and schema by using AWS Glue to crawl JSON data. This data was obtained from Kaggle and consists of 24hours of traffic for each port.


## Querying the data for the port with the largest number of incoming vessels


![alt text](https://github.com/Zi-Stonga/Maritime-Ports-AWS/blob/main/Images/Most_Arrivals.JPG)


From this table we can see that the busiest port for incoming vessels is Singapore, Singapore. This is followed by Shanghai China, and Singapore, Singapore Anch.


## Finding the port with the least number of incoming vessels

![alt text](https://github.com/Zi-Stonga/Maritime-Ports-AWS/blob/main/Images/Least_Arrivals.JPG)

From this table we can see that the least busiest port for incoming vessels is China Fuling. This is followed by Fort Lauderdale USA, then Norfolk USA.



## Finding the port with the most number of vessel departures
![alt text](https://github.com/Zi-Stonga/Maritime-Ports-AWS/blob/main/Images/Most_Departures.JPG)

From this table we can see that the busiest port for vessels departures is Shanghai China, followed by Nantong, China. CJK China is the 3rd busiest port, followed by Naning and Jiangyin both in China. With the top 5 busiest ports all in China, we can deduct that this is due to the fact that china is the one the leading manufacturers of steel, car parts, chemicals, electronics, and robotics.


## Finding the port with the least number of vessel departures

![alt text](https://github.com/Zi-Stonga/Maritime-Ports-AWS/blob/main/Images/Least_Departures.JPG)

From this table we can see that the least busiest port for vessel departures is Fourchon USA, closely followed by Barcelona Spain. And then Muara Berau Anch, Indonesia.

## Finding the port with most expected arrivals
![alt text](https://github.com/Zi-Stonga/Maritime-Ports-AWS/blob/main/Images/Most_expected_arrivals.JPG)

From this table we can see that the port for most expected incoming vessels is Singapore, followed by Shanghai China.


## Finding the port with least number of expected arrivals
![alt text](https://github.com/Zi-Stonga/Maritime-Ports-AWS/blob/main/Images/least_expected_arrivals.JPG)


From this table we can see that the port with the least expected incoming vessels is Constanta, Romania. This is followed by Pingtan China. Third is Norfollk, USA

## Sentiments
With a continuously active maritime industry world wide, analyzing this data for activity was insightful in understanding how busy a port can be in a particular country and the amount of planning needed to ensure port traffic is planned and tracked with continous system adaptation and improvement.





