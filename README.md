# Image Classification using AWS SageMaker

Use AWS Sagemaker to train a pretrained model that can perform image classification by using the Sagemaker profiling, debugger, hyperparameter tuning and other good ML engineering practices. This can be done on either the provided dog breed classication data set or one of your choice.

## Project Set Up and Installation
Enter AWS through the gateway in the course and open SageMaker Studio. 
Download the starter files.
Download/Make the dataset available. 

## Dataset
The provided dataset is the dogbreed classification dataset which can be found in the classroom.
The project is designed to be dataset independent so if there is a dataset that is more interesting or relevant to your work, you are welcome to use it to complete the project.

### Access
Upload the data to an S3 bucket through the AWS Gateway so that SageMaker has access to the data. 

## Hyperparameter Tuning
I started with pretained Resnet50 and frozen it layers and added connected layers. The types of parameters and their ranges used for the hyperparameter search are learning rate, epochs and bacth size

Remember that your README should:
- Include a screenshot of completed training jobs
- Logs metrics during the training process
- Tune at least two hyperparameters
- Retrieve the best best hyperparameters from all your training jobs
Screenshots are present in screenshots folder

## Debugging and Profiling
Debugginga nd profiling is done with help of model smdebug which helps us to monitor. we can specify rules, configs to the debugger

### Results
What are the results/insights did you get by profiling/debugging your model?

It helped me understandp and cpu and GPU usages and also helped be to adjust the hyperparametrs for correct fitting of model

## Model Deployment
Give an overview of the deployed model and instructions on how to query the endpoint with a sample input.
load the image that you want to oredict and reshape it as per the model and use the model file to predict

