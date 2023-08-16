# YoutubeDataHarvestingAndWarehousing
DS_YouTube Data Harvesting and Warehousing using SQL, MongoDB and Streamlit

Introduction

Harvesting and warehousing YouTube data can provide valuable insights into user behavior, content trends, and engagement patterns. This repository aims to provide a starting point for collecting YouTube data and setting up a data warehousing system to manage and analyze the collected data.
Prerequisites

Before you begin, ensure you have the following prerequisites:

    Python (>= 3.6)
    Google API Key
    Google Cloud Platform Account (for advanced usage)
    YouTube Data API v3 Access

Data Harvesting

The data_harvesting directory contains scripts for harvesting YouTube data. You can use these scripts to collect data such as video information, comments, and user details. Modify the scripts according to your specific use case and data requirements.

    video_metadata_harvester.py: Collects metadata for a list of YouTube videos.
    comments_harvester.py: Collects comments for a given YouTube video.
    user_details_harvester.py: Collects details for a list of YouTube users.

Data Warehousing

The data_warehousing directory contains resources and guidelines for setting up a data warehousing system to store and manage the harvested YouTube data.

    Choose a Database: Depending on the scale of your project, consider using a relational database (e.g., MySQL, PostgreSQL) or a NoSQL database (e.g., MongoDB, Cassandra).

    Schema Design: Design a schema that suits your data model. Consider tables/collections for videos, comments, users, etc.

    ETL Process: Create an ETL (Extract, Transform, Load) process to transfer harvested data from the harvesting scripts to the database.

Usage

    Clone this repository to your local machine.

    bash

    git clone https://github.com/your-username/YouTube-Data-Harvesting-Warehousing.git

    Follow the instructions in the data_harvesting directory to use the data harvesting scripts.

    Set up your chosen database and follow the guidelines in the data_warehousing directory to design your schema and implement the ETL process.

    Execute the ETL process to transfer harvested data to your database.

Contributing

Contributions to this repository are welcome! If you have improvements or additional scripts for data harvesting or warehousing, feel free to open a pull request.
License

This project is licensed under the MIT License.
