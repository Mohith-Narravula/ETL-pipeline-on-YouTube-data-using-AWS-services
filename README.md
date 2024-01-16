# ETL-pipeline-on-YouTube-data-using-AWS-services

### 📋 Architecture Diagram:
![Architecture](https://github.com/Mohith-Narravula/ETL-pipeline-on-YouTube-data-using-AWS-services/assets/117317024/caf66c9f-ab05-4e99-96c7-142c22a6c351) 
(provided by the mentor of this project --> Carlos Contreras)

### 🔍 Project Overview:
This project is about Analysing YouTube Dataset (on Trending YouTube Video) by AWS services like Athena, S3, Glue and Lambda. Technical languages used are SQL, Python3. Aim is to securely manage, streamline, and perform analysis on the structured and semi-structured YouTube videos data based on the video categories and the trending metrics. Cloud-based safe Data Lake solutions aid in the development of rich analytics on data while classifying it into several storage phases, such as raw, cleansed, and analytical.

### 💾 Dataset for this project
Pulled data from Kaggle throught Kaggle API throught AWS CLI and the name of the data set is [Trending YouTube Video Statistics](kaggle.com/datasnaek/youtube-new![image](https://github.com/Mohith-Narravula/ETL-pipeline-on-YouTube-data-using-AWS-services/assets/117317024/c54e9532-75ff-40dc-8887-2316885baded)
) 

### 👩‍💻 What I learnt from this Project:
•	Building a data lake from scratch in Amazon S3, by joining semi-structured and structured data.
•	Data lake design in layers, partitioned for cost-performance: In this case three S3 buckets are created which are, Raw (landing layer), Cleansed and analysis (reporting for BI users WORM model / Write Once Read Many).
•	Creating IAM Roles, Policies and Lambda functions.
•	How to combine two different dataset format and joins those tables together: In this case, JSON and CSV to Parquet.
•	AWS Data Catalogue. 
•	Setting up Glue Jobs for ETL.
•	Using Glue Crawler and Glue Studio.
•	Performing Data Transformations and Joins.

### 🎯 Key Achievements:
•	Built a ETL pipeline in AWS.
•	Got introduced to Staging and Data Lake
•	End-To-End ETL pipe line can handle real-time (streaming) data.
•	Learnt naming conventions in AWS for each service in an effective way. 
•	Learnt to connect AWS from AWS CLI.

### 🙏 Acknowledgments:
A big thanks to my mentor for this project, [Carlos Contreras]( https://www.linkedin.com/in/carloscontreras/), for simplifying each concept as simply as possible and to the Project Pro team for providing amazing Big Data projects. 
