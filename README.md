
# K-means Based Customer Segmentation in AWS

## Project Overview
This project aims to develop a customer segmentation model using the K-means clustering algorithm on AWS SageMaker. By identifying distinct customer segments, the project enhances targeted marketing strategies and improves customer relationship management.

## Key Features
- **Model Development and Deployment:** Utilized AWS SageMaker to train and deploy a K-means clustering model, achieving high accuracy in customer segmentation.
- **Automation and Scalability:** Implemented AWS Lambda functions to automate data preprocessing, storage, and prediction processes, ensuring efficient, secure, and scalable data handling.
- **Monitoring and Evaluation:** Used AWS CloudWatch to monitor model performance and presented actionable insights to non-technical stakeholders.

## Technologies Used
- **AWS SageMaker:** For model training and deployment.
- **AWS S3:** For data storage and preprocessing.
- **AWS Lambda:** For automation of prediction processes.
- **AWS CloudWatch:** For monitoring and evaluation of model performance.
- **Python:** For data preprocessing using pandas and numpy.
- **Machine Learning:** K-means clustering algorithm.

## Project Workflow
1. **Data Preparation:**
   - Loaded and preprocessed customer data using pandas.
   - Normalized data to improve quality and consistency.

2. **Model Training:**
   - Configured and trained a K-means model on AWS SageMaker.
   - Set optimal hyperparameters to achieve high accuracy.

3. **Model Deployment:**
   - Deployed the trained model to a SageMaker endpoint for real-time predictions.

4. **Automation:**
   - Created AWS Lambda functions to automate the prediction process.

5. **Monitoring:**
   - Used AWS CloudWatch to monitor the performance of the deployed model.

## Results
- Successfully identified five distinct customer segments.
- Enabled real-time predictions and integrations with other applications.
- Provided actionable insights to stakeholders, enhancing targeted marketing efforts.

## How to Use
1. Clone this repository.
2. Prepare your customer data and upload it to an S3 bucket.
3. Follow the steps in the `notebooks` directory to preprocess the data and train the K-means model.
4. Deploy the model using SageMaker and set up AWS Lambda for automation.
5. Monitor the model's performance using CloudWatch.

## Conclusion
This project demonstrates the effective use of AWS services to develop, deploy, and manage a customer segmentation model. The automation and monitoring capabilities ensure the model is scalable and reliable, providing valuable insights for targeted marketing strategies.


