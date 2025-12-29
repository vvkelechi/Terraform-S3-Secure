# Terraform Secure S3 Bucket Project

## 📌 Overview
This project provisions a **secure AWS S3 bucket** using Terraform.
It follows infrastructure-as-code best practices and is suitable for
production-ready environments.

---

## 🛡️ Security Features
- Public access completely blocked
- Server-side encryption enabled (AES-256)
- Bucket versioning enabled
- Parameterized configuration using variables

---

## 📁 Project Structure
terraform-s3-secure/
├── main.tf
├── variables.tf
├── outputs.tf
├── README.md

---

## ⚙️ Prerequisites
- AWS CLI configured (`aws configure`)
- Terraform installed
- AWS account with S3 permissions

---

## 🚀 Usage

### 1️⃣ Initialize Terraform
```bash
terraform init

2️⃣ Plan Infrastructure
terraform plan -var="bucket_name=unique-bucket-name"

3️⃣ Apply Infrastructure
terraform apply -var="bucket_name=unique-bucket-name"

📤 Outputs

After deployment, Terraform will display:

S3 bucket name

S3 bucket ARN

🧠 Use Cases

Secure storage for application assets

Terraform remote backend storage

Backup and archival solutions

🏷️ Author

Victor Eze

Devops & Cloud Engineer


---

## ✅ STEP 5: Run It (Local Test)

```bash
terraform init
terraform plan -var="bucket_name=klec-secure-bucket-12345"
terraform apply -var="bucket_name=klec-secure-bucket-12345"

