# About
## Python scraper to collect the Fear & Greed Index from CNN money site at 10am and 6pm MON-FRI

# Deployment
## AWS Lambda
 
# Trigger
## CloudWatch cron jobs to fire at 10am and 6pm from Monday throuh Friday

# Data
## the time sereis data is updated and stored in a csv file in AWS s3 bucket 

# Troubleshooting
## installing modules: Used Lambda layer -> zipped needed python modules 
## 403 (forbidden access) from s3 ->  added s3fullAcess policy on IAM for my Lambda role

# cnn_gfi_collector
