# Operationalizing-Machine-Learning-on-SageMaker
Operationalizing Machine Learning on SageMaker - AWS project 4

## Project Set Up and Installation
For this project, you should perform all of the Sagemaker steps using Sagemaker itself, not Sagemaker Studio
## 1.	Write about the Sagemaker instance you created, including a justification of why you chose the instance type you did.
•	 I have chosen the “ml.t2.medium” instance type for Notebook instance because for completing the execution of this particular project’s jupyter notebooks we do not need a very computationally powerful CPU and high RAM. But We will need to keep this notebook instance in “in Service” status for a long time while we are working on the project So, avoid high costs we should select a notebook that is low in per hour cost and also offers reasonably good CPU and RAM.

 - ![instance](https://github.com/6abi/Operationalizing-Machine-Learning-on-SageMaker/blob/main/prints/instance.PNG)
 
## Dataset
The provided dataset is the dogbreed classification dataset which can be found in the classroom.
The dataset was upload into S3 bucket

- ![bucket](https://github.com/6abi/Operationalizing-Machine-Learning-on-SageMaker/blob/main/prints/bucket_create.PNG)
- ![dataset](https://github.com/6abi/Operationalizing-Machine-Learning-on-SageMaker/blob/main/prints/dataset.PNG)

## Hyperparameter Tuning

### Results


## Model Deployment

**TODO** Remember to provide a screenshot of the deployed active endpoint in Sagemaker.
- ![endpoint](https://github.com/6abi/Image-Classification-using-AWS-SageMaker---computer-vision-nlp/blob/main/prints/endpoint.PNG)
