# aws-s3-react-app-deployment

This code uses boto3 implementation to perform React App Deployment on S3. It does the following things:

1. Create s3 Bucket

2. Clone the repo from provided repo url

3. Upload the code to s3 bucket with appropriate extensions and correct folder structure!

4. Enables Static Site Generation for the bucket

5. Attach Policy for GetObject action

6. Makes all the objects Public using ACL


+ Make sure the public acess is allowed for the bucket and ACLs are enabled while creation

+ provide your own github url 
