# SnapScale
SnapScale is a serverless image processing pipeline built on AWS. When an image is uploaded to an S3 bucket, it automatically triggers a Lambda function that resizes and compresses the image, storing the optimized version in a separate output bucket. This architecture is scalable, event-driven, and fully managed using Terraform.
