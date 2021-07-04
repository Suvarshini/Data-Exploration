# Bay Wheels Bike Sharing System
## by Suvarshini


## Dataset

> Bay Wheels (previously known as Ford GoBike) is a regional public bicycle sharing system in California's San Francisco Bay Area. Bay Wheels publicly share their data in the [Bay Wheels' Data System](https://www.lyft.com/bikes/bay-wheels/system-data). For this project, I focus on the year 2019 which has 2,506,983 rows and 15 columns. All 12 files were manually downloaded and concatenated into a dataframe using Jupyter. Basic cleaning were done such as removing incomplete columns, changing datatypes and removing incorrect records. 


## Summary of Findings

> The aim of this project is to understand and learn insights of the consumer's behavior when using the bike sharing system. I am interested to know who uses this system, how long do they ride, when do they ride, and how did the rebranding affected the user's behavior. After analysis, I found out that most rides are during working hours (weekdays and at 8-9am and 5-6pm) and have short duration (less than 15 minutes). Rentals and ride duration are affected by season where there are more rentals and longer ride duration during hotter months. However, the number of rental was affected by the rebranding and marketing strategy by Lyft. For example, the drop in May-June was due to the rebranding, July had higher rentals due to the introduction of ebike but dropped again in August when ebikes were pulled out due to battery issues. Most of the users are subscribers but customers have longer ride duration. Customers might also be transitioning to subscribers during December 2019.


## Key Insights for Presentation

> Lyft introduced dockless ebikes in July 2019 but quickly pulled out due to bateery issues. I was interested to know how these events have affected users' behavior. And sure enough, the number of rentals were indeed affected by it. Since it was dockless, it also caused a high number of station_id and station_name to be missing values which isn't an error and should be maintained in the analysis. 
