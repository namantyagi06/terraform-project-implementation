# Terraform Project Implementation

## 🚀 Project Overview

This repository demonstrates **Infrastructure as Code (IaC)** using **Terraform** to provision and manage AWS resources. The project is designed for learning and hands-on practice with real-world Terraform configurations commonly used in DevOps and Cloud roles.

Resources are defined in separate Terraform files to maintain clarity, scalability, and best practices.

---

## 🛠️ Technologies Used

* **Terraform**
* **AWS (Amazon Web Services)**
* **EC2**
* **S3**
* **DynamoDB**
* **Linux / Bash scripting**

---

## 📂 Project Structure

```
terraform-project-implementation/
│
├── ec2.tf           # EC2 instance configuration
├── s3.tf            # S3 bucket configuration
├── dynamodb.tf      # DynamoDB table configuration
├── variables.tf     # Input variables
├── outputs.tf       # Output values
├── terraform.tf     # Provider and Terraform settings
├── script.sh        # Shell script for automation
├── terra-key.pub    # Public key for EC2 access
├── graph.png        # Terraform architecture graph
└── README.md        # Project documentation
```

---

## ✅ Prerequisites

Make sure you have the following installed and configured:

* Terraform (v1.0+ recommended)
* AWS CLI
* AWS Account
* IAM user with sufficient permissions

Configure AWS CLI:

```bash
aws configure
```

---

## ⚙️ How to Use This Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/namantyagi06/terraform-project-implementation.git
cd terraform-project-implementation
code .
```

---

### 2️⃣ Initialize Terraform

```bash
terraform init
```

---

### 3️⃣ Validate Configuration

```bash
terraform validate
```

---

### 4️⃣ Preview the Infrastructure

```bash
terraform plan
```

---

### 5️⃣ Apply the Configuration

```bash
terraform apply
```

Type `yes` when prompted.

---

### 6️⃣ Destroy Resources (Optional) After completing the project.

```bash
terraform destroy
```

---

## 🔧 Variables

All configurable inputs are defined in `variables.tf`. You can override values using:

* `terraform.tfvars`
* Command line `-var` flag
* Environment variables

---

## 📤 Outputs

Useful outputs such as instance IDs or resource names are defined in `outputs.tf`.

View them using:

```bash
terraform output
```

---

## 📌 Learning Outcomes

* Understand Terraform file structure
* Learn AWS resource provisioning via Terraform
* Practice Infrastructure as Code concepts
* Visualize infrastructure using Terraform graph

---

## 🧠 Best Practices Followed

* Separate resource definitions
* Use variables and outputs
* Keep infrastructure version controlled
* Clear and reusable configurations

---

## 🙌 Author

**Naman Tyagi**
GitHub: [https://github.com/namantyagi06](https://github.com/namantyagi06)

---

⭐ If you find this project helpful, feel free to star the repository!

