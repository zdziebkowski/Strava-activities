# Strava Activities PowerBI Project

![image](https://github.com/zdziebkowski/Strava-activities/assets/126050762/a7d2a000-d90b-4c3b-8ada-212f3205878a)

# Strava Activities PowerBI Project Background Description:

As a passionate cycling enthusiast, I have embarked on a personal project to analyze and gain insights from my sports activities recorded through the Strava app. For this analysis, I obtained the dataset by downloading my personal Strava profile, which includes activities recorded from the years 2021 to 2023. The dataset comprises both a CSV file containing activity records and GPX files containing GPS data.

To ensure the project's success, I outlined the key information that I aimed to extract and visualize through a comprehensive dashboard.

The initial stage of data preprocessing involved loading all the files into Power Query Editor. Subsequently, I performed data cleaning, which involved the following steps:

1.	Removing unnecessary columns to focus on relevant data.
2.	Standardizing numerical formatting by replacing dots with commas, converting floats from the US format to the EU format.
3.	Unifying skiing activities as 'Ski' by consolidating data from 'Nordic Ski' and 'Alpine Ski' categories.
4.	Inserting additional columns with date and time information, such as month, day, and year, to facilitate temporal analysis.
5.	Adding a conditional column to categorize activities based on the commute to work or other classifications.
6.	Calculating speed from meters per second to kilometers per hour for better readability.
7.	Adjusting data types to ensure accuracy and consistency.

In order to create a heatmap of activities, I imported XML files into Power Query from a designated folder. To optimize the heatmap's loading speed, I conducted further data cleaning by reducing the GPX file size. For this purpose, every 150 rows, starting from the second row, were deleted, sacrificing some path accuracy but ensuring smoother performance while working with the report.
Once the data cleaning and transformation were completed, I loaded the prepared dataset into the data model. The visualization phase then commenced, wherein I designed the dashboard to showcase valuable insights from the data.

Key Performance Indicators (KPIs) were defined, including:
1.	Total number of activities recorded.
2.	Total distance covered in kilometers.
3.	Total time spent in minutes.

![image](https://github.com/zdziebkowski/Strava-activities/assets/126050762/86f1d07c-3d60-4fb7-8eb7-078ebbf3713c)
 
The dashboard features various charts that display:
1.	Total and average distance traveled by the day of the week.
2.	Average distance and time spent by month.

![image](https://github.com/zdziebkowski/Strava-activities/assets/126050762/45d57c4c-958f-44bd-a8da-e68e16964c9b)

![image](https://github.com/zdziebkowski/Strava-activities/assets/126050762/4b713c8e-fb46-4b49-b06e-4592ae24fd4b)
 
Additionally, the dashboard illustrates the percentage share of total time and distance by type of activity (e.g., cycling, skiing) and further classifies the distance into work-related or recreational rides.

![image](https://github.com/zdziebkowski/Strava-activities/assets/126050762/5f830529-9be4-436c-8303-5e7e5bd3bd3a)
 
One interesting feature incorporated into the dashboard is the representation of average speed along with the corresponding minimum and maximum speeds achieved during activities.

![image](https://github.com/zdziebkowski/Strava-activities/assets/126050762/f056214b-7bd5-4d7a-9406-a94c86818181)
 
However, the central highlight of the dashboard lies in the interactive map, where user can explore and review the most common routes and locations of their activities. This feature enables easy retracing of all accomplished journeys, providing valuable insights and a unique way to analyze activity patterns.

![image](https://github.com/zdziebkowski/Strava-activities/assets/126050762/b252ebb4-bded-49f2-8ca0-c8c386a53b69)

Overall, the Strava Activities PowerBI project serves as a powerful tool for examining and visualizing personal sports activities, empowering me to make data-driven decisions, track progress, and gain a deeper understanding of my cycling experiences.
