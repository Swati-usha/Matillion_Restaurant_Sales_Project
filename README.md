Matillion_Restaurant_Sales_Project

Welcome to the Restaurant Matillion Project README!

Project Overview:
The Restaurant Matillion Project is aimed at leveraging data analytics to optimize operations and enhance customer experience within a restaurant setting. 
By harnessing the power of Matillion, a cloud-native data integration platform, this project seeks to 
streamline various aspects of restaurant management, including inventory management, sales forecasting, personalized marketing strategies.

In this project, data is fetched from S3 Bucket into Snowflake source database tables.
data is then transferred into matillion for transformation.
In transformation it majorly focuses on iterative and recursive identification of tables and lastly tables are reloaded based
on the flag which will be set by Grid Variables in matillion.
then the cleaned data will be merged from the pipelines and the transformed data will be sent to PowerBi for visualization. 
