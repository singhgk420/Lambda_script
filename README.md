# Lambda_script
1) lambda-sqs-script:-
  In this project, I will be creating an S3 bucket, Queue, and Lambda function. Whenever an object is uploaded in the S3 bucket,
  an S3 event will trigger the queue and the lambda function will run which will check if the object name contains the word "sensitive"
  If so it will send an email notification to the team saying some sensitive file is added in the bucket.
