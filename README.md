# project4: Serverless Data Engineering Pipeline
![Figure](https://github.com/nogibjj/project4/blob/main/Screen%20Shot%202023-04-05%20at%208.57.17%20PM.png)

1. Things included are:

* `An AWS Lambda function`

*  `An Amazon Simple Storage Service (Amazon S3) bucket`

*  `An AWS Step Functions state machine`

*   `Related AWS Identity and Access Management (IAM) roles`

2. Use SageMaker and AWS Step Functions to train a machine learning model and batch transform a test dataset

* `Data Preparation: The first step is to prepare the data that will be used to train the model. This could involve cleaning, transforming, and splitting the data into training, validation, and test sets.`

* `Data Storage: The data needs to be stored in a data source that the AWS infrastructure can access. AWS offers a variety of data storage options such as Amazon S3 (Simple Storage Service) and Amazon RDS (Relational Database Service).`

* `Model Selection: Choose a machine learning algorithm that is best suited. AWS offers a variety of algorithms such as Linear Learner, XGBoost, and DeepAR.`

* `Model Training: Use AWS SageMaker to train the selected machine learning model. SageMaker is a fully-managed service that provides a scalable, secure, and cost-effective way to build, train, and deploy machine learning models.`

*  `Model Evaluation: Once the model is trained, it needs to be evaluated to ensure that it is accurate and effective.`

3. The "train.csv" file is used for training the model, the "test.csv" file is used for evaluating the final performance of the model, and the "test-out" dataset is used during the development process to tune the hyperparameters of the model.

4. Metrics
![Figure](https://github.com/nogibjj/project4/blob/main/Screen%20Shot%202023-04-12%20at%2012.40.41%20PM.png)

![Figure](https://github.com/nogibjj/project4/blob/main/Screen%20Shot%202023-04-12%20at%2012.40.50%20PM.png)