# Lidar Glue Streamer

A simple tool to stream raw lidar point data to a data lake.
Utilizing Amazon S3 and AWS Glue.

## Why?

Lidar point clouds are huge, and since we want real-time streaming and storing of the data, a traditional database with a schema is a poor fit. 
