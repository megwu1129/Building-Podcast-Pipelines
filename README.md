# building-podcast-pipelines

## Overview

In this project, I built a data pipeline using Airflow. The pipeline will download podcast episodes and automatically transcribe them using speech recognition. I stored the results in a SQLite database that we can easily query.


## Project Steps

- Download the podcast metadata xml and parse
- Create a SQLite database to hold podcast metadata
- Download the podcast audio files using requests
- Transcribe the audio files using vosk

## Installation
To follow this project, please install the following locally:

- Airflow 2.3+
- Python 3.8+
- Python packages: pandas, sqlite3, xmltodict, requests, vosk,pydub

## Data
The podcast metadata page is [here](https://www.marketplace.org/feed/podcast/marketplace/).
