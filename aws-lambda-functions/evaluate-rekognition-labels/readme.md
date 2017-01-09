# evaluate-rekognition-labels

This directory contains an AWS Lamdba Definition that evaluates whether or not to send an alert email for an uploaded picture.

## Contents

1. evaluate-rekognition-labels.js.

## How to use

### IAM Role

Using the [AWS IAM Console](https://aws.amazon.com/console/) create an IAM Role containing the "AmazonSESFullAccess" and "AWSLambdaBasicExecutionRole" permissions. 

### Upload to AWS

Using the [AWS Lambda Console](https://aws.amazon.com/lambda), create a new Lambda Function called *evaluate-rekognition-labels* and copy this file into the inline code editor.