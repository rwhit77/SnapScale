# 🖼️ SnapScale – Serverless Image Optimization Pipeline

**SnapScale** is a fully serverless image processing pipeline built on AWS. It automatically resizes and compresses images uploaded to an S3 bucket using an AWS Lambda function triggered by S3 events. The optimized images are stored in a separate output bucket. All infrastructure is deployed using Terraform for full automation and repeatability.

---

## 🧠 What This Project Demonstrates

- Event-driven architecture using S3 and Lambda
- Real-time image optimization using Python (Pillow)
- Automated infrastructure deployment with Terraform
- Secure IAM role scoping and permissions control
- Scalable serverless design — no EC2 or containers required

---

## 🛠️ Tech Stack

- **Storage:** AWS S3
- **Compute:** AWS Lambda (Python runtime)
- **Infrastructure as Code:** Terraform
- **Image Processing:** Pillow (Python image library)
- **IAM:** Scoped roles for S3 and Lambda execution

---

## ⚙️ Architecture Diagram


