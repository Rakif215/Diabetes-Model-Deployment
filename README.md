# Diabetes Prediction Model Deployment

This repository contains all the necessary files and code to deploy a diabetes prediction model on Azure. The steps include building the model, deploying it to Azure, and predicting using the deployed endpoint.

## Repository Structure

- **1. Diabetes model to be deployed.ipynb**: Jupyter notebook containing the code to train the diabetes prediction model.
- **2. deploy ML model on Azure.ipynb**: Jupyter notebook that walks through deploying the trained model to Azure Machine Learning services.
- **3. Predict from Azure Endpoint.ipynb**: Jupyter notebook demonstrating how to predict using the Azure endpoint.
- **config.json**: Configuration file for Azure settings such as subscription ID, resource group, and workspace details.
- **diabetes_model.pkl**: Pickle file containing the trained diabetes prediction model.
- **requirements.txt**: Contains the necessary dependencies to run the notebooks and deploy the model.
- **score.py**: Scoring script used by Azure to predict from the deployed model.

## Setup Instructions

### Prerequisites

1. Install Python 3.x.
2. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Diabetes-Model-Deployment.git
   cd Diabetes-Model-Deployment
