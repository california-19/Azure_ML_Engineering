# Azure_ML_Engineering
Code to start using MLFlow, automated machine learning, hyperparamter tuning, and batch inference on Azure machine learning studio.

In the files below, you will find the code to start using various features of Azure machine learning. To keep things simple, I used the Titanic dataset that I got from the internet. I used Microsoft's Azure Machine Learning documentation, https://learn.microsoft.com/en-us/azure/machine-learning/, as a reference to all of my code. I tried to add explanations as much as I can, but they still require basic knowledge of machine learning and cloud computing. Enjoy using them as you wish!  

**data_assets.ipynb**: Create a data asset that you will use later in machine learning jobs   
**model_automl.ipynb**: Training multipe machine learning models (preconfigured models with options) and comparing the results  
**model_batch_endpoint.ipynb**: Create a batch endpoint for inferencing  
**model_customEnv.ipynb**: Create a custom environment for your machine learning models  
**model_mlflow-autologging.ipynb**: Automatically log metrics, parameters and other files (artifacts)   
**model_mlflow-hyperparameter_tuning.ipynb**: Hyperparameter tuning on Azure  
**model_mlflow.ipynb**: Track ML training using MLFlow  
**ROC-Curve.png**: An ROC curve which was an output of one of the files above  
**titanic_env.yml**: The custom environment I created  
