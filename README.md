# sanfran-bikeshare

This repository holds a Python notebook developed on Google Datalab, pulling data from BigQuery and creating TensorFlow models from the data.

The models aim to predict if a San Francisco bikeshare station will have availability. Initially this is achieved with one model for all stations, built using the estimator API. Additionally it uses a LSTM RNN to predict availability at a specific station in 15 minutes time.
