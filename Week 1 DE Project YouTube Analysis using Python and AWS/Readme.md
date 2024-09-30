# YouTube-Analysis-Project using Python and AWS

### Overview:

This project aims to securely manage, streamline, and perform analysis on the structured and semi-structured YouTube videos data based on the video categories and the trending metrics.

### Project Goals:

1. Data Ingestion — Build a mechanism to ingest data from different sources
2. ETL System — We are getting data in raw format, transforming this data into the proper format
3. Data lake — We will be getting data from multiple sources so we need centralized repo to store them
4. Scalability — As the size of our data increases, we need to make sure our system scales with it
5. Cloud — We can’t process vast amounts of data on our local computer so we need to use the cloud, in this case, we will use AWS
6. Reporting — Build a dashboard to get answers to the question we asked earlier
   
### Services we will be using:

1. Amazon S3: Amazon S3 is an object storage service that provides manufacturing scalability, data availability, security, and performance.
2. AWS IAM: This is nothing but identity and access management which enables us to manage access to AWS services and resources securely.
3. QuickSight: Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud.
4. AWS Glue: A serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development.
5. AWS Lambda: Lambda is a computing service that allows programmers to run code without creating or managing servers.
6. AWS Athena: Athena is an interactive query service for S3 in which there is no need to load data it stays in S3.

### Dataset Used:

This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

https://www.kaggle.com/datasets/datasnaek/youtube-new

### Architecture Diagram:

![image](https://github.com/vikrant1111/Data-Engineering---YouTube-Analysis-Project/assets/38528301/4b77216b-853a-4b02-9060-f772cee858cb)

### Visualization using Tableau:

![image](https://github.com/user-attachments/assets/16d5aa5a-c92b-4274-a25d-4b914fcdb8b6)
![image](https://github.com/user-attachments/assets/c150a912-ea71-4ed6-87aa-1c85429367b6)

### Analysis:
- People & Blogs is the most popular video category across the Canada, United States and Great Britain, followed by Music.
- Entertainment, Music and Science & Technology are the most commented Video Categories.
- Great Britain has highest percentage of dislikes and lower percentage of overall Engagement when compared with Canada and United States.
- The most disliked categories are News&Politics and NonProfits & Activism.   The most liked categories: Travel & Events and Music.
- Music tends to have the highest views in Great Britain followed by Entertainment.
- Music tends to have the highest outliers (as high as ~72m Views). Entertainment came 2nd (highest outlier at ~24m).
- Wil Aime, Weest and exurb1a channels have the highest Engagement rates across the 3 countries.
- Only few video categoris like Music, Entertainment , People & Blogs were able to cross the average view count in United States and Great Britain.
