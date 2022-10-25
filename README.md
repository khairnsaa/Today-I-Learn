# Today-I-Learn

Today i learn in LearningX - Sparta Coding Club Bootcamp

## Routing in AWS S3 Bucket

When you configure an Amazon S3 bucket for website hosting, you must give the bucket the same name as the record that you want to use to route traffic to the bucket. For example, if you want to route traffic for spartacodingclub.com/ to an S3 bucket that is configured for website hosting, the name of the bucket must be spartacodingclub.com/. 
If you want to route traffic to an S3 bucket that is configured for website hosting but the name of the bucket doesn't appear in the Alias Target list in the Amazon Route 53 console, or if you're trying to create an alias record programmatically and you're getting an InvalidInput error from the Route 53 API, one of the AWS SDKs, the AWS CLI, or AWS Tools for Windows PowerShell, check the following:
• The name of the bucket exactly matches the name of the record
• The S3 bucket is correctly configured for website hosting.
