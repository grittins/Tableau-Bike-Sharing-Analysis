# NYC-Citi-Bike-Sharing-Analysis
Visualizations for investors of a bike-sharing program in Des Moines. The visualizations are created by analyzing Citi Bike-Sharing in NYC. 

## Resources
- Data Source: 201908-citibike-tripdata-minutes.csv
- Software: Python, Jupyter Notebook, Tableau

[Tableau Public Profile](https://public.tableau.com/app/profile/rezwan.ferdous)

## Overview of the analysis: 

For this bike-sharing analysis, Pandas is used to change the "tripduration" column from an integer to a datetime datatype and renamed to "tripduration minutes". Also, the 'Gender' column denoted by '0', '1' and '2' is changed from number form to string 'Unknown', 'Male' and 'Female' respectively. Then, using the converted datatype, visualizations are created to:

- Show the length of time that bikes are checked out for all riders and genders
- Show the number of bike trips for all riders and genders for each hour of each day of the week
- Show the number of bike trips for each type of user and gender for each day of the week.

Finally, the new visualizations are used via Tableau story and dashboards for final presentation and analysis to pitch to investors.


## Results: 

- Checkout Times for Users
<img width="1038" alt="Screen Shot 2022-08-13 at 11 20 23 PM" src="https://user-images.githubusercontent.com/104872971/184521005-e07b5740-fe6b-4e5d-8e40-7486d25e1d2f.png">
Here's the display of the checkout times for users. With above 146,000 bikers checking out at 5 minutes. The graph shows an exponential drop where most bikers checking out before the 60 minutes mark. 


- Checkout Times by Gender
<img width="1037" alt="Screen Shot 2022-08-13 at 11 21 16 PM" src="https://user-images.githubusercontent.com/104872971/184521017-d85b5854-fd9c-41b4-a492-2d29703db5f6.png">
Here's a breakdown of the checkout times by gender. With all genders checking out before 30 minutes marks most bikers checking before the 60 minutes mark. 


- Trips by Weekday by Hour
<img width="1038" alt="Screen Shot 2022-08-13 at 11 21 56 PM" src="https://user-images.githubusercontent.com/104872971/184521041-b32487c4-0092-42df-846d-87cf74db606c.png">


- Trips by Gender (Weekday per Hour)
<img width="1036" alt="Screen Shot 2022-08-13 at 11 23 00 PM" src="https://user-images.githubusercontent.com/104872971/184521078-70d1be3b-151b-4802-9c11-ebccc5c4b658.png">


- User Trips by Gender by Weekday
<img width="1035" alt="Screen Shot 2022-08-13 at 11 23 26 PM" src="https://user-images.githubusercontent.com/104872971/184521091-f2a02730-7cbe-409f-90d4-ef7a7cd9aab2.png">


## Summary:
All in all, this bike-sharing analysis provides a lot of insight for a successful business as there are plenty of bikers using the service for their commute with a very high-percentage using the services to commute to and from their workplaces. 

Here are some additional visualizations in the form of Tableau story and dashboards: 

- [Working Hours Analysis](https://public.tableau.com/views/CitiBikeAnalysisStory/WorkingHoursAnalysis?:language=en-US&:display_count=n&:origin=viz_share_link): 
<img width="1013" alt="Screen Shot 2022-08-13 at 11 29 36 PM" src="https://user-images.githubusercontent.com/104872971/184521229-be04b8d6-edb2-4ad1-a157-151e00cddd6a.png">


- [Trips by Gender Analysis](https://public.tableau.com/shared/GW27DDXJN?:display_count=n&:origin=viz_share_link): 

<img width="1009" alt="Screen Shot 2022-08-13 at 11 30 53 PM" src="https://user-images.githubusercontent.com/104872971/184521247-ade812c0-cc26-44ef-97b1-bbecaf789d4f.png">

- [Trips by User Types Analysis](https://public.tableau.com/shared/FKF4ZJH4R?:display_count=n&:origin=viz_share_link):  

<img width="1006" alt="Screen Shot 2022-08-13 at 11 31 42 PM" src="https://user-images.githubusercontent.com/104872971/184521265-549e6d4f-22c3-4be3-a455-9e0ee1369b19.png">


