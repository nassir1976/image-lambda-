# image-lambda-

### author Nassir Abegaz

## overview 
- create s3 Buckets for file storage.
- upload an image to resize.
- Deploying a Node.js Lambda Function that conects to s3.
- Auto Deploying to AWS through GitHub.
  

  ## Feature Tasks

- A user should be able to upload an image at any size, and have both the original size and a thumbnail size
- When an image is uploaded to your S3 bucket, it should trigger a Lambda function which must;
    - Create a 50x50 pixel thumbnail version of that image
    - Save it to another S3 bucket.
    - It should do so with a predictable naming convention, so that your server and/or frontend know where that thumbnail image will be.
  
## set-up 
npm init -y 
npm install dependancies 
eb init / initialize elasticbeanstalk .
zip -r lambda-function.zip (zip a lambda function)