CDC for Taxicab:

Initial Load Data: s3://pheaa-initial-load
CDC data : s3://pheaa-cdc-load
Final Table : s3://pheaa-base-partitioned

Notebook: aws-glue-phess02 
Dev end point: ag-pheaa-2

Glue DB: pheaa-taxicab
Glue Table: pheaa_base_partitioned
Crawler: pheataxi