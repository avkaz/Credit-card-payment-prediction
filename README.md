## ML Classification Project with Azure ML
### Overview
This repository contains two Projects that demonstrate the process of building, training, and deploying a machine learning classification model using Azure ML, MLflow, Scikit-learn, and Pandas. The two projects highlight different approaches to creating an ML pipeline:

##### Project 1: Focuses on model creation and deployment.
##### Project 2: Emphasizes the creation of reusable pipeline components without deployment.
### Projects
#### 1. Model Creation and Deployment (E2E project with deployment)
This notebook walks through the steps required to create and deploy a Gradient Boosting Classifier model.

##### Key Features:
- Data Source: Accesses data from an external URL.
- Model: Uses Gradient Boosting Classifier for the classification task.
- Deployment: Includes the steps to deploy the trained model using Azure ML.
- Limitations: The script is not reusable as it does not create separate pipeline components.
#### 2. Reusable Pipeline Creation (Reusable E2E project with components and pipeline)
This notebook focuses on building a reusable machine learning pipeline.

##### Key Features:
- Data Source: Accesses data from a registered data asset in Azure ML.
- Model: Utilizes Gradient Boosting Classifier for the classification task.
- Pipeline: Emphasizes reusability by creating modular pipeline components.
- No Deployment: Does not include deployment steps.
