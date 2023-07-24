# Project: SQL-Snowflake
## Airbnb Data Analysis Using SQL-Snowflake
### Description of the Dataset:
Airbnb, Inc. is an American San Francisco-based company operating an online marketplace for short- and long-term homestays and experiences. The company acts as a broker and charges a commission from each booking.
You will be working with their European Booking Dataset. This is a merged dataset of 9 famous cities in Europe:
Amsterdam, Athens, Barcelona, Berlin, Budapest, Lisbon, Paris, Rome, and Vienna.
The original Dataset was messy and lacked describing appropriate information. But, this one was first cleaned. 

#### Variables Names and Descriptions are:
* City: Name of the City
* Price: Price of Airbnb
* Day: If it is a weekday or weekend
* Room Type: Type or Airbnb - Entire Apt, Private Room, Shared Room
* Share Room: If the Room in Airbnb is shared by anyone
* Private Room: If the Stay has a Private room available
* Person Capacity: The Person Capacity of Airbnb
* Superhost: If the Airbnb host is Superhost or not
* Multiple Rooms: If the Airbnb has multiple rooms (2-4) rooms
* Business: If the Business has more than 4 offers
* Cleaningness Rating: Cleanness Ratings of the Places
* Guest Satisfaction: Guest Satisfaction Score they left
* Bedrooms: Number of Bedrooms in the facility
* City Center (km): Distance to the center of the City from the staying place
* Metro Distance (km): Distance to the Metro Service from the staying place
* Attraction Index: Attraction Index of the Place
* Normalised Attraction Index: Normalised value of the Attraction Index
* Restraurant Index: Restaurant Index of the Place
* Normalised Restraurant Index: Normalised value of the Restaurant Index

#### Task:

1. Perform exploratory data analysis using Snowflake SQL and tell a story you'd like to tell with this dataset.
2. Create a Database in Snowflake named "TOURISM"
3. Create a Schema under that Database named "EUROPE"
4. Create a Table under that Database and Schema named "AIRBNB" [Be careful with the Field Names and Field Types]
5. Create an Appropriate File Format to Bulk insert the CSV file (Airbnb Europe Dataset.csv)
6. Insert the dataset using the created file format [K]
7. If you see any error, then work on that. You must try until you see no error.
8. Proof Check: The number of Records should be 41,714
9. Perform Descriptive Analysis and Frequency Distribution [Build Charts as well in your result if you find the output important enough]
10. Check if there is any outlier in the "PRICE" Field; If so, then report the observations and then remove the outliers
11. Apart from the descriptive analysis, try to Explore which Fields/Variables have a Causal Relationship with "Guest Satisfaction".
12. Build a Simple Dashboard using Snowflake [Keep one or two filters on top; whatever field you find most important ones to look at]
13. Write a Short Report based on your findings [Report should be written in Microsoft Word File and the Analyses, Charts should be included in the report; Add a Screenshot of your dashboard as well]

## Findings:
![Screenshot (30)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/7adab94b-f7a8-4168-9598-d15c940d19f3)

![Screenshot (29)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/f2c96361-6318-4aca-81f4-a9adcf93b05e)

![Screenshot (34)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/d24a85fc-3dd0-4ef4-86bf-297ea414c7e2)

![Screenshot (33)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/e29fe6d7-14ce-4638-a90d-133de3e80a1d)

![Screenshot (32)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/b3fe9394-6173-42d0-bb99-76bd8cf8d5c3)
![Screenshot (35)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/5c414aed-d1b9-47f2-af48-6ede3cb0b7c2)
![Screenshot (36)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/290baf4e-fa50-455b-96e5-6b678dae1ad8)
![Screenshot (37)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/2888c7af-1209-4b56-b5b1-818881811e72)
![Screenshot (38)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/1d6c7ccb-1baf-4ef2-9574-b6a4a34763b9)
![Screenshot (39)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/fd51c014-cebb-4d89-92f9-17534ef8fdaa)




