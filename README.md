# Welcome to the Elasticsearch Linear Regression Model Project

This project uses MLflow and DAGSflow to monitor a Linear Regression model trained on Elasticsearch data. The project is hosted on GitHub at https://github.com/harshvasisht/mlflow_dagshub.

## Features

* The model is trained on a dataset of Elasticsearch documents.
* The model is monitored locally using MLflow.
* The model is monitored remotely using DAGSflow.

## Benefits

* The MLflow tracking system provides a centralized view of all experiments and models.
* The DAGSflow monitoring system provides real-time alerts and notifications.
* The project is hosted on GitHub, which makes it easy to collaborate and share with others.

## Getting started

To get started with this project, you can follow these steps:

1. Clone the repository.
2. Install the dependencies.

    ```bash
    bash setup.sh
    ```

3. Activate the environment.

    ```bash
        conda activate venv
    ```

4. Run the 'app.py' script to train the model. With the alpha & l1_ratio.

    ```bash
        python app.py 0.3 0.7
    ```

    ```bash
        Elasticnet model (alpha=0.300000, l1_ratio=0.700000):
        RMSE: 0.774713648356711
        MAE: 0.607967853255621 
        R2: 0.14961391810397706
    ```

5. To view MLflow dashboard.

    ```bash
        mlflow ui
    ```

[![project repo](https://github.com/HarshVasisht/MLflow_Dagshub/blob/main/img/ElasticSearch_LR.png?raw=true)](https://github.com/HarshVasisht/MLflow_Dagshub/blob/main/img/ElasticSearch_LR.png?raw=true)

## Resources

* [MLflow documentation](https://mlflow.org/docs/latest/)
* [DAGSflow documentation](https://dagsflow.readthedocs.io/en/latest/)
* [GitHub repository](https://github.com/harshvasisht/mlflow_dagshub)

## Community

The MLflow and DAGSflow communities are vibrant communities of machine learning practitioners and developers. The communities provide support, resources, and collaboration opportunities.

* [MLflow community forum](https://discuss.mlflow.org/)
* [MLflow community Slack channel](https://mlflow.slack.com/)
* [DAGSflow community forum](https://dagsflow.discourse.group/)
* [DAGSflow community Slack channel](https://dagsflow.slack.com/)

I hope you enjoy this project!
