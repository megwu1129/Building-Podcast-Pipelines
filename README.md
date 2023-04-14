# building-podcast-pipelines

## Overview

In this project, I created a data pipeline using Airflow. The pipeline will download podcast episodes and automatically transcribe them using speech recognition. I store the results in a SQLite database that we can easily query.


## Local Setup
To follow this project, please install the following locally:

- Airflow 2.3+
- Python 3.8+
- Python packages: pandas, sqlite3, xmltodict, requests, vosk,pydub
