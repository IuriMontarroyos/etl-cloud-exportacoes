# ETL – Cloud-Ready Data Pipeline

This project demonstrates a simple ETL pipeline in Python with a cloud-oriented architecture.

## Objective
Build an ETL process to extract export data, transform and aggregate information, and store the final report in a structure prepared for cloud storage (AWS S3).

## Technologies
- Python
- Pandas
- CSV
- Cloud Storage concepts (AWS S3)
- Google Colab

## ETL Pipeline
- **Extract:** Load structured export data
- **Transform:** Clean, standardize and aggregate the dataset
- **Load:** Store the final report in a simulated cloud bucket

## Output
A CSV report containing aggregated export data, stored in a directory that represents a cloud storage bucket.

## Notes
The pipeline is designed to be easily extended to a real AWS S3 integration using the AWS SDK (boto3).
