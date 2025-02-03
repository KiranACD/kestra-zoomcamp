## Kestra Files

Run `docker compose up` to set up kestra and postgres. 

Open Kestra UI in the browser at `localhost:8080`.

Save and execute the flow in `gcp_key_value_setup.yaml` to set up the google cloud credential key value pairs.

Save and execute the flow in `gcp_bucket_dataset_setup.yaml` to set up a new bucket and dataset in big query.

Save the flow in `gcp_taxi_data_scheduled.yaml` and execute the flow by selecting the date range in the backfill execution option in the triggers section of the flow file. 

