# Analyzing 10Gb of Yelp Reviews Data

Analyzed a subset of Yelp's business, reviews and user data. This dataset comes to us from [Kaggle](https://www.kaggle.com/yelp-dataset/yelp-dataset) although we have taken steps to pull this data into a s3 bucket: `s3://sta9760-yelpdataset/yelp-light/*business.json`

## Technology Used

Create a Cluster on AWS EMR

Provision the hardware
Configure Jupyter Notebook connected to the cluster
Run Spark Cluster Tasks via Jupyter Notebook
Read dataset through S3 buckets

## Cluster and Notebook Configs

![notebook](assets/notebook.png)
![cluster](assets/cluster.png)
