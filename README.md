# X-Ray
In this module we will build an end to end solution like Prime Video X-Ray to recognize mainstream and custom celebrities. We use RecognizeCelebrities and SearchFacesByImage APIs to recognize mainstream and custom celebrities.

## Pre-requisites
This module requires completion of previous modules:
 - [Celebrity Recognition](https://github.com/darwaishx/celebrity-recognition/tree/master/1-celebrity-recognition)
 - [Recognize Custom Celebrities](https://github.com/darwaishx/celebrity-recognition/tree/master/2-recognize-custom-celebrities)

## Deploy Solution
In this step we will deploy the solution using CloudFormation template. This CloudFormation template will perform following actions:

1. Create and deploy REST APIs using AWS API Gateway. It will provide public endpoints to accept request from Client.
2. Create Lambda function to interface with AWS Rekognition to recognize mainstream and custom celebrities.
3. Create a S3 bucket, copy required files to host HTML based client to test this solution.

Click on **Launch Stack** button below to launch CloudFormation template in US East AWS region.

Region| Launch
------|-----
US East (N. Virginia) | [![Create IAM Role for SageMaker us-east-1](http://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/images/cloudformation-launch-stack-button.png)](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/create/review?stackName=X-Ray&templateURL=https://s3.amazonaws.com/husbasit-dl-artifacts/AnalyzeImage.yaml)


## Other Steps

## Analyze Images

## Other?

## Completion
You have successfully installed and configured Media Analysis Solution. You then learned how to use managed Machine Learning Application Services to extract metadata from your media files. You also learned how to extend Media Analysis Solution and detect and filter inappropriate content.

## Clean up
Step to clean up resources.
