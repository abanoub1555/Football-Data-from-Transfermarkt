# TransferMarket Data Modeling
## Project Overview:
In this project, you need to model the provided dataset into a star schema and implement your model on HDFS in CSV, Avro and Parquet formats. After that, you will compare between the three formats in terms of size, write speed and read speed. You should also try multiple compression levels and alogrithms with the Avro and Parquet formats.

## Resources:
[TransferMarket Dataset on Kaggle](https://www.kaggle.com/datasets/davidcariboo/player-scores)

## Requirements:
- Design the Star Schema.
- Load data modeled as the schema you designed into HDFS as CSV files, Avro files and Parquet files.
- Compare between the sizes, write speed and read speed.
- Repeat the process with different compression algorthims

## Key Deliverables
- Schema Design
- A Document that details the comparison between different trails.

## Steps for the implementation:
1- build docker compose file (docker-compose build -d)
2- run the containers (docker start namenode datanode1 datanode2 datanode3)
3- then run the main code (the application)

