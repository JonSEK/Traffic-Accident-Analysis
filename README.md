# Traffic Accident Analysis
![image](https://github.com/JonSEK/Traffic-Accident-Analysis/assets/103926746/e559fd1c-e6cd-4afb-bfc8-fbd0cc73e253)
Using Microsoft Excel, 12,601 rows of raw traffic accident data was analyzed and visualized to reveal significant trends and patterns, providing a comprehensive understanding of the information. The resulting charts and graphs serve as valuable tools for informed decision-making and targeted interventions to improve road safety.

## How it's made

### Sample of raw data
![image](https://github.com/JonSEK/Traffic-Accident-Analysis/assets/103926746/b1d1223b-57a4-4538-8376-dcb3786a3136)

### Total Accident
![image](https://github.com/JonSEK/Traffic-Accident-Analysis/assets/103926746/b32f2cca-2087-4720-adc3-97c102ee8e7a)

#### Data Preparation
1. The frame of the table was created with the years as the heading of the columns and the months as the heading of the rows. 
2. `SUMPRODUCT` function was used to get the total number of accidents in the given year and month. 
3. `SUM` function was then used to get the total number of accidents in the year at the end of the table.

### Time and Crash Type
![image](https://github.com/JonSEK/Traffic-Accident-Analysis/assets/103926746/23279a4e-51b0-4512-8539-d599b0117ac7)

#### Data Preparation
1. The frame of the table was created with the crash type as column heading and time as row heading. 
2. The time of the day was divided into 8 groups, each group lasting 3 hours.
3. `COUNTIFS` function was used to get the number of accidents that happened in each of the time groups and the different crash types.

### Gender and Type of Road User
![image](https://github.com/JonSEK/Traffic-Accident-Analysis/assets/103926746/fb65d980-a77f-4a94-bd1a-1cc99c129f93)

#### Data Preparation
1. 2 tables were required to get the outer and inner doughnut chart. 
2. `COUNTIF` function was used to get the data for the 1st table which contains the total number of male and female involved in the accident. 
3. `SUMPRODUCT` function was used to get the data for the 2nd table which contains the breakdown of the road user from the male and female that were involved in the accident.

### Heavy Vehicle Involvement
![image](https://github.com/JonSEK/Traffic-Accident-Analysis/assets/103926746/0ec05469-fe7b-4a8f-afdc-39ee1ba523fb)

#### Data Preparation
1. Headings for the columns are the type of heavy vehicles that were involved in the accidents, headings for the rows are the years. 
2. `COUNTIFS` function was used to extract the data into the table.

### Age Group
![image](https://github.com/JonSEK/Traffic-Accident-Analysis/assets/103926746/5b313ca9-d095-409e-b2ff-286161e64954)

#### Data Preparation
1. All the age of the users that were involved in the accidents were divided into age group with 5 years a group starting from 0 to 100. 
2. Headings for the rows are the age group and heading for the column is number of accidents. 
3. `COUNTIFS` function was used to extract the data into the table.
