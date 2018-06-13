# Image-Store
Lambda function to process an image

Use this code as function.dev.json file and update the role ARN

{
  "description": "Node.js lambda function using S3 as a trigger to transform the uploaded image and then upload the new image in S3",
  "role": "arn:aws:iam::xxxxx:role/apex-image-transform_lambda_function",
  "handler": "index.handler",
  "environment": {
  	"TRANSFORM_FUNC" : "negative"
  }
}
