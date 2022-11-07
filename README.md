# EY_Capstone_Project_Group2
# Data analysis on City.csv Dataset.
# Team - Group_2

# Team_Members - 
1. Md Ishtiyaque Hussain 
2. Raju Kumar
3. Ravikanti Vaishnavi
4. Sumayya

# PROJECT OBJECTIVE
                                                     
The objective is to collect and process the data so that other data analysts and data scientists can utilize the data for their business use cases.

# TASKS TO BE PERFORMED
                                                     
1.Bronze Layer:- As a  data engineer we would first build the bronze layer where we would collect the data from the different sources
2.Silver Layer:-Then we will build a silver layer where we will clean the data and remove all impurities such as missing values or datetime correction.
3.Gold Layer:- Finally, we will build a gold layer where we will design the distribution of the data sets and save the graphs back into the data lake.

# DATA INGESTION
In data ingestion , we load the data records from one or more sources  by using azure data factory into the bronze container of data lake storage.

# STORING DATA
After the data ingestion we store the data in bronze container and after  cleaning it we will transfer it to silver container 

# DATA PROCESSING 
In this Process we used Azure data bricks and we will perform  operations:

1.Analyzing the Data.
2.Deleting the column which has more null Values.
3.Deleting the Rows which has more than 3 null Values.
4.Replacing the null value with mean value of the same Column.
5.We handled the Time-Series Data.

# VISUALIZATION

We have use Power BI Visualization tool for visual representations, it will help users to develop powerful business insight quickly and effectively.
In this part we have created Six reports to show our Outcomes which are:-
1.AQI_Bucket.pbix
2.Avg_AQI.pbix
3.Avg_AQI_Year.pbix
4.Avg_AQI_month.pbix
5.Avg_CO.pbix
6.Avg_NH3.pbix 

# CONCLUSION

Through this project,
We explored the dataset, handled the missing Values and drawn insights from it by using Visualization tool Power BI.
Through different reports we represented the Air Quality Index(AQI),yearly & monthly which helps user to understand in which year & month pollution is more.
For Specific city we have filter out reports by displaying which city is most polluted.
We also have explore the harmful gases which affecting the AQI by calculating Average CO & NH3 value.


