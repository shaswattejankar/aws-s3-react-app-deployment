# aws-s3-react-app-deployment

This code uses boto3 implementation to perform React App Deployment on S3. It does the following things:

1. Create s3 Bucket

2. Clone the repo from provided repo url

3. Upload the code to s3 bucket with appropriate extensions and correct folder structure!

4. Enables Static Site Generation for the bucket

5. Attach Policy for GetObject action

6. Makes all the objects Public using ACL


+ Make sure the public acess is allowed for the bucket and ACLs are enabled while creation

+ provide your own bucket name and github url in place of <code>YOUR_BUCKET_NAME</code> & <code>YOUR_GITHUB_REPO_URL</code>

The temporary deployment link is [here](http://0518-react-bucket.s3-website.us-east-2.amazonaws.com/)
