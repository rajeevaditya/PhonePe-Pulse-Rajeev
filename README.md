# PhonePe Pulse Data Visualization 2018-2022
This project is a data visualization tool for PhonePe's pulse data from 2018 to 2022. It allows users to explore and analyze various metrics related to PhonePe's business performance.


## Installation and cloning
Clone the repository to your local machine using git clone https://github.com/PhonePe/pulse.git
Install the required Python packages by running pip install -r requirements.txt

I have created a dashboard to visualize Phonepe pulse Github repository data(https://github.com/PhonePe/pulse) using Streamlit and Plotly in Python

Link for web app is : https://phonepe-pulse-rajeev-ljnqpngrz5tscscqsa2dj2.streamlit.app/

THE MAIN COMPONENTS OF DASHBOARD ARE

HOME PAGE
![image](https://github.com/rajeevaditya/PhonePe-Pulse-Rajeev/assets/126942001/36478985-19bc-4982-b132-a3aa43d00479)


1 GEO-VISUALIZATION & TOP STATES DATA

![image](https://github.com/rajeevaditya/PhonePe-Pulse-Rajeev/assets/126942001/a711feef-7f82-4239-93e5-9dfc34dc2741)

![image](https://github.com/rajeevaditya/PhonePe-Pulse-Rajeev/assets/126942001/e3307d64-42d7-4491-ba7f-60af2d546b27)


2 TRANSACTIONS ANALYSIS

![image](https://github.com/rajeevaditya/PhonePe-Pulse-Rajeev/assets/126942001/5afd339c-da6a-4ed8-94ab-a97e435f0690)


3 USERS ANALYSIS

![image](https://github.com/rajeevaditya/PhonePe-Pulse-Rajeev/assets/126942001/df42b59a-3d5a-4c46-bf5b-32f8bb2d15ef)


1 Geo-Visualization: The India map shows the Total Transactions of PhonePe in both state wide and District wide.It comes with zoom option and on hover displays the content related to that particular state or district.The main functions I have used to create this map are (User can give year and quarter input to show how the data changed over time)

1 Plotlys scatter_geo for plotting districts along with the conent    

2 Plotlys coropleth for drawing the states in India map    
2 Transactions Analysis: The Transactions data mainly contains the total Transactions count and total amount in each state and district, I have used different graphs available in plotly to represent this data

1 State-wise study
The above bar graph shows the increasing order of PhonePe Transactions according to the states of India, 
Here we can observe the top states with the highest Transaction by looking at graph

2 District-wise study
User can observe how transactions are happening in districts of a selected state.We can observe the 
leading distric in a state

3 Year-wise study   
We can observe the states with total transactions in particular mode in the selected year

4 Overall Analysis
To show how the transactions drastically increased with time
3 User Data Analysis: The Users data mainly contains the Registered Users count and App openings via different mobile brands in each state and district,I have used different graphs available in plotly to represent this data

1 State-wise study
User can observe how the App Openings are growing and how Registered users are growing in a state

2 District-wise study
User can observe how App Openings are happening in districts of a selected state

3 Year-wise study   
User can observe the top leading brands in a particular state in given year

4 Overall Analysis
We can see that the Registered Users and App openings are increasing year by year
4 Top States Data:

1 States with top Registered users
2 States with top Total Amount Transacted
3 States with highest Trabsactions count
4 States with top app openings

