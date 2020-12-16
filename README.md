# E2E ML with BigQueryML

End to end Machine Learning pipelines using Bigquery ML. The main idea is to show how you can make AI at cloud just using BigqueryML.

We will use differents datasets like NYC taxi or AbadIA datasets to show to do it.

## Data Sources

Not decided yet, but perhaps it could be a great idea to use the same dataset with all project.  

## Expected Cloud AI tools

Try to do everything just with BigQuery ML even the production inference:

BigQuery -> Data Ingest  (load csv files)
BigQuery SQL (Data Cleaning) -> clean and write result to the final table 
BigQuery ML (Model Training) -> Train a model (decision tree or mlp, or ensemble model) 
BigQuery ML (Model Serving) -> Just insert data and get the inferences
BigQuery ML (Model Export) -> Just export the model for third part use.
