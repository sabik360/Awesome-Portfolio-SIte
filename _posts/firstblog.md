---
date: '2023-04-15T11:50:54.000Z'
title: Exploring the World of Data Engineering - From Simple Pipelines to Big Data
tagline: Understanding the Purpose and Evolution of Data Engineering
preview: >-
  Data engineering is all about the process of taking data 
  from its source and making it available for analysis. 
  It may seem simple and not worth discussing, but there's 
  a lot more to it than meets the eye.
image: >-
  https://wallpaperaccess.com/full/417693.png
---

# Introduction

Data engineering is all about the process of taking data from its source and making it available for analysis. It may seem simple and not worth discussing, but there's a lot more to it than meets the eye. Let's take a closer look at how data engineering works.



![An old rock in the desert](https://content.altexsoft.com/media/2019/06/word-image-47.png)



## The Journey Begins: Automating Data Collection and Reporting


Imagine a team that has an application, which is working fine as traffic and sales continue to grow. They are tracking results using tools like Google Analytics, CRM, and an application database. There's also an analytics guy who's a pro at Excel spreadsheets. Currently, their analytics data pipeline involves manually moving data into an Excel spreadsheet from multiple sources, which becomes tedious and time-consuming.

However, as the team grows and the amount of data increases, along with the need for more sources and data fields, this manual process becomes inefficient. The analytics guy feels overwhelmed, and the team realizes the need for automation. They decide to automate the data pipeline with the help of a data engineer.



## Data Engineering: Building the ETL Pipeline


The data engineering process starts with automation through an Extract, Transform, Load (ETL) pipeline. The goal is to automatically pull data from various sources, such as APIs, and transform it by removing errors, changing formats, mapping records, and validating the data. Finally, the transformed data is loaded into a database, like MySQL. This process needs to be repeated regularly, which is where the data engineer comes in, building scripts to automate the pipeline.

With the ETL pipeline in place, the team can now use Business Intelligence (BI) tools to analyze the data. These tools offer user-friendly dashboards with visualizations like pie charts, bar graphs, and maps. The team now has convenient access to insights, and the culture of using data begins to flourish. Marketing can track the entire sales funnel, the product team can explore customer behavior, and management can monitor key performance indicators (KPIs).



## The Data Warehouse: Unlocking New Possibilities


However, as the company continues to grow, issues start arising. Reports take longer to generate, some SQL queries go missing, and the current pipeline doesn't seem scalable. This happens because the existing pipeline relies on a standard transactional database like MySQL, which is not optimized for analytical tasks.
At this point, the company realizes the need for a data warehouse. A data warehouse is a repository that consolidates data from various sources into a single central location. Unlike a transactional database, a data warehouse is specifically optimized for running complex analytics queries.

To set up a data warehouse, the team needs to organize the data and structure it in a meaningful way. This involves designing schemas and tables that represent the relationships between different data types. The data engineer works closely with the team to arrive at the best warehouse design through iterations and interviews.
With the data warehouse implemented, the data pipeline becomes more robust and efficient. The data is generated at the sources, automatically pulled by the ETL scripts, transformed and validated, and then loaded into the warehouse. The team can now access this data through BI tools and gain insights for decision-making.



## Data Scientists and Data Engineers: An Interdisciplinary Partnership


While the data warehouse serves the reporting and analytics needs of the team, data scientists require more advanced tools and systems. Data scientists aim to find hidden insights in data and create predictive models. They need access to both the structured data in the warehouse and the raw, unstructured data for exploration and machine learning models.

To cater to the needs of data scientists, data engineers work on setting up a data lake. A data lake is another type of storage that holds raw, unprocessed data without imposing a predefined schema. The ETL process changes to Extract, Load into the lake, and then Transform, as data scientists define how to process the data to make it useful for their analysis and models.



## Enter the Data Lake: Unleashing the Power of Unstructured Data


Working on big data requires a slightly different approach. Big data typically refers to data with high volume, variety, veracity, and velocity. Dealing with big data often requires a dedicated team of data engineers or even a big data engineering team. They work with technologies like Kafka, which enables data streaming through publish and subscribe messaging, and Hadoop, a scalable framework for distributed storage.

In an advanced pipeline for big data, thousands of records are streamed simultaneously using pub-sub systems like Kafka. The data is then processed using ETL or ELT frameworks like Spark. It can be loaded into data lakes, warehouses, or flow through custom pipelines. All these data repositories are deployed on clusters of servers running distributed storage tools like Hadoop.



## Navigating Big Data: Pub-Sub, Distributed Storage, and Computing


As organizations encounter truly massive volumes of data, they face new challenges related to speed, scalability, and storage. Data streaming techniques like publish-subscribe (pub-sub) using technologies such as Kafka, allow for real-time asynchronous data consumption. Distributed storage frameworks like Hadoop, designed for handling petabytes of data across clusters of servers, provide the scalability and redundancy required. Spark, a popular data processing framework, enables efficient processing within this ecosystem.

To cater to the needs of data scientists, data engineers work on setting up a data lake. A data lake is another type of storage that holds raw, unprocessed data without imposing a predefined schema. The ETL process changes to Extract, Load into the lake, and then Transform, as data scientists define how to process the data to make it useful for their analysis and models.



# Conclusion


In conclusion, the sole purpose of data engineering is to extract data from its source, transform and process it, and make it available for analysis. The process involves various stages, from automation using ETL pipelines to the implementation of data warehouses and data lakes. For big data, additional technologies like data streaming and distributed storage are used. Data engineers play a crucial role in building and maintaining these pipelines and systems to ensure the company can unlock the power of its data.




