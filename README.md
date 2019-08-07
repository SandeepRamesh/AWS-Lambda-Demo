# AWS-Lambda-Demo
A House Price Prediction Machine Learning model created to predict and deploy on AWS Lambda. 

Steps to Deploy:
  1.  Install Serverless and Configure IAM AWS credentials to your account.
  2.  sls create --template aws-python3 --name house-prediction
  3.  Edit the handler.py and serverless.yml
  4.  sls plugin install -n serverless-python-requirements@4.2.4
  5.  sudo sls deploy
  6.  sls invoke --function predict-price --path event.json
  
  
  Next steps is to deploy on to a webpage. 
