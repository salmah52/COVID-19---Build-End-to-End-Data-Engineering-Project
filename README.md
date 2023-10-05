# COVID-19

## ---Build-End-to-End-Data-Engineering-Project

## Data Engineering Project: Building a COVID-19 Analytics Platform

Welcome to my data engineering project, where I build a comprehensive COVID-19 analytics platform. In this project, I'll walk you through the entire process, from data acquisition to data analysis and visualization.

## Architecture Diagram

![Architecture Diagram](https://github.com/salmah52/COVID-19---Build-End-to-End-Data-Engineering-Project/assets/44398948/29ff6b04-e742-4ee2-9c18-18429305cb65)

## Relational Data Model

To organize and manage our data, I have designed a relational data model. This model defines the structure of our database, including tables, primary keys, and relationships. More details about the data model can be found in [this document](link-to-data-model.md).

### Connecting Athena for Data Querying

Amazon Athena is a powerful tool for querying data stored in Amazon S3. I set up Athena, define databases and tables, and execute SQL queries to extract valuable insights from my data.

## Implementing an ETL Job in Python

Extract, Transform, Load (ETL) is a crucial step in data engineering. I extract data from our source, perform transformations, and prepare it for loading into our analytics platform.

## Saving Results to Amazon S3

Once I have processed and transformed my data, I move it to our S3 bucket. Amazon S3 provides scalable and durable storage, making it an ideal choice for data storage.

## Building Tables on Amazon Redshift

Amazon Redshift is our data warehousing solution. I create the necessary tables on Redshift to store our cleaned and transformed data. These tables are designed to support efficient querying and reporting.

## Copying Data to Amazon Redshift

Finally, I copy data from S3 into Amazon Redshift tables. This step is critical for making our data accessible for analytics and reporting.

## Conclusion

Our COVID-19 analytics platform is now ready for action! We've covered every step of the data engineering process, from designing a relational data model to querying data using Athena, implementing ETL in Python, storing results in S3, building tables on Redshift, and loading data into Redshift. With this platform, you can analyze, visualize, and gain insights from COVID-19 data effectively.

Thank you for joining me on this data engineering journey!

Happy Engineering!
