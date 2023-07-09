#Description of the Dataset:
Airbnb, Inc. is an American San Francisco-based company operating an online marketplace for short- and long-term homestays and experiences. The company acts as a broker and charges a commission from each booking.
You will be working with their European Booking Dataset. This is a merged dataset of 9 famous cities in Europe:
Amsterdam, Athens, Barcelona, Berlin, Budapest, Lisbon, Paris, Rome, and Vienna.
The original Dataset was messy and lacked describing appropriate information. But, this one was first cleaned. 

#Variables Names and Descriptions are:
City: Name of the City/
Price: Price of Airbnb/
Day: If it is a weekday or weekend/
Room Type: Type or Airbnb - Entire Apt, Private Room, Shared Room/
Share Room: If the Room in Airbnb is shared by anyone/
Private Room: If the Stay has a Private room available/
Person Capacity: The Person Capacity of Airbnb/
Superhost: If the Airbnb host is Superhost or not/
Multiple Rooms: If the Airbnb has multiple rooms (2-4) rooms/
Business: If the Business has more than 4 offers/
Cleaningness Rating: Cleanness Ratings of the Places/
Guest Satisfaction: Guest Satisfaction Score they left/
Bedrooms: Number of Bedrooms in the facility/
City Center (km): Distance to the center of the City from the staying place/
Metro Distance (km): Distance to the Metro Service from the staying place/
Attraction Index: Attraction Index of the Place/
Normalised Attraction Index: Normalised value of the Attraction Index/
Restraurant Index: Restaurant Index of the Place/
Normalised Restraurant Index: Normalised value of the Restaurant Index/

#Task:

Perform exploratory data analysis using Snowflake SQL and tell a story you'd like to tell with this dataset.
Create a Database in Snowflake named "TOURISM"
Create a Schema under that Database named "EUROPE"
Create a Table under that Database and Schema named "AIRBNB" [Be careful with the Field Names and Field Types]
Create an Appropriate File Format to Bulk insert the CSV file (Airbnb Europe Dataset.csv)
Insert the dataset using the created file format [K]
If you see any error, then work on that. You must try until you see no error.
Proof Check: The number of Records should be 41,714
Perform Descriptive Analysis and Frequency Distribution [Build Charts as well in your result if you find the output important enough]
Check if there is any outlier in the "PRICE" Field; If so, then report the observations and then remove the outliers
Apart from the descriptive analysis, try to Explore which Fields/Variables have a Causal Relationship with "Guest Satisfaction".

Build a Simple Dashboard using Snowflake [Keep one or two filters on top; whatever field you find most important ones to look at]
Write a Short Report based on your findings [Report should be written in Microsoft Word File and the Analyses, Charts should be included in the report; Add a Screenshot of your dashboard as well]

######################### Findings #########################
![Screenshot (30)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/7adab94b-f7a8-4168-9598-d15c940d19f3)

![Screenshot (29)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/f2c96361-6318-4aca-81f4-a9adcf93b05e)

![Number Of Outliers In Price Field](https://github.com/PervejHosen/SQL-Projects/assets/117522848/3a6559a5-b2e6-4e2a-aedc-b96c1c0599a6)



![Frequency Distribution of Guest Satisfaction (1)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/d5f3ad19-1e63-42af-9df4-fea2523ee92e)

![Frequency Distribution of Person Capacity](https://github.com/PervejHosen/SQL-Projects/assets/117522848/3b506a37-8080-477a-ba66-d94013393ae3)

![Scatter Plot of Price Variables](https://github.com/PervejHosen/SQL-Projects/assets/117522848/420a4c70-9f71-4573-b695-e775e975939d)

![Frequency Distribution of Cleanliness Rationg](https://github.com/PervejHosen/SQL-Projects/assets/117522848/86acbe4f-9a64-4632-907d-a38190379dc3)

![Frequency Distribution of Bedrooms](https://github.com/PervejHosen/SQL-Projects/assets/117522848/c6842efe-a19d-431b-a195-9fb6f2fd55f9)

![Frequency Distribution of City Center](https://github.com/PervejHosen/SQL-Projects/assets/117522848/a8283acb-a9af-4d88-984c-f17d29e6d3b6)

![Frequency Distribution of Metro Distance (1)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/1b4c53cb-93bf-452b-a9f1-19cbd2f4565f)


![Total Observation By City](https://github.com/PervejHosen/SQL-Projects/assets/117522848/cb7ab295-c973-4cdd-a907-ad5147655670)

![City Wise Min, Max and Avg Of Price (1)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/6f53b0a9-5883-4ab5-8c40-e321dd371ded)

![Screenshot (22)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/734b3147-1d7d-4e35-bd7e-4627338ddd8d)



