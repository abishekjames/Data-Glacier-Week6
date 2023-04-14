# Data-Glacier-Week6

Following steps are done in File_ingestion.ipynb

2+ GB csv file downloaded from https://www.kaggle.com/datasets/ekibee/car-sales-information?select=region41.csv

* File read using different methods of file reading eg: Dask, Modin, Ray, Pandas

* Computational efficiency reported for the above methods

* Basic validation on data columns like removing special character , white spaces from the col name etc. performed

* A YAML file created with the column names of the csv file

* Number of columns and column name of ingested file validated with YAML

* File written in pipe separated text file (|) in gz format.

* A summary of the file created
