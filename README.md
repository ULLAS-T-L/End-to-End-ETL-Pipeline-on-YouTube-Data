# End-to-End-ETL-Pipeline-on-YouTube-Data

### Data Engineering YouTube Analysis with AWS

#### Overview:
This repository focuses on securely managing, streamlining, and analyzing structured and semi-structured YouTube video data, with a specific emphasis on video categories and trending metrics.

#### Project Goals:
- **Data Ingestion:** Develop a mechanism for ingesting data from diverse sources.
- **ETL System:** Transform raw data into the appropriate format.
- **Data Lake:** Establish a centralized repository for storing data from multiple sources.
- **Scalability:** Ensure the system scales seamlessly with increasing data size.
- **Cloud Integration (AWS):** Utilize AWS for processing large amounts of data.
- **Reporting Dashboard:** Build a dashboard to extract insights from the data.

#### Services Used:
- **Amazon S3:** Object storage service offering manufacturing scalability, data availability, security, and performance.
- **AWS IAM:** Identity and access management for secure access to AWS services and resources.
- **QuickSight:** Scalable, serverless, embeddable, machine learning-powered BI service for cloud-based business intelligence.
- **AWS Glue:** Serverless data integration service facilitating data discovery, preparation for analytics and application development.
- **AWS Lambda:** Computing service enabling code execution without server management.
- **AWS Athena:** Interactive query service for S3, allowing data querying without the need to load it.

#### Dataset:
The repository includes a Kaggle dataset containing daily statistics (CSV files) of up to 200 trending YouTube videos across multiple months and locations. Each region has its file, including video title, channel title, publication time, tags, views, likes, dislikes, description, and comment count. The associated JSON file contains a region-specific `category_id` field. This dataset serves as a comprehensive source for understanding the dynamics of trending YouTube videos.
