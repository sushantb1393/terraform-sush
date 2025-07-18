# terraform-sush

# 🚀 Terraform EC2 Project

This repository contains a basic Terraform project to launch an EC2 instance on AWS.

---

## 🛠️ Steps to Get Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/atulkamble/terraform-ec2-new.git
cd terraform-ec2-new

mkdir project
cd project

 Create a Key Pair in AWS Console
Go to the AWS EC2 Dashboard → Key Pairs.
Create a new key pair named key.pem.
Download and move it to your project directory.

sudo yum install git tree -y

nano main.tf
nano variables.tf
nano output.tf

git add .
git commit -m "Initial commit with Terraform EC2 code"
git push origin main


terraform init         # Initialize Terraform project
terraform validate     # Validate syntax
terraform fmt          # Format code
terraform plan         # Preview changes
terraform apply        # Apply changes

terraform apply

terraform-ec2-new/
└── project/
    ├── main.tf
    ├── variables.tf
    ├── output.tf
    └── key.pem

chmod 400 key.pem

echo "key.pem" >> .gitignore



