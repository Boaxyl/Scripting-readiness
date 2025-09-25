# Scripting-readiness

# AWS EC2 & S3 Automation Script

## 📌 Project Overview

This shell script automates the provisioning of **Amazon EC2 instances** and **S3 buckets**, designed to meet client deployment needs while reinforcing key shell scripting concepts. It serves both as a practical tool and a learning artifact.

---

## 🚀 Features

- Create EC2 instances with custom types
- Provision S3 buckets with dynamic names
- Track created resources using arrays
- Secure sensitive data via environment variables
- Accept command line arguments for flexible deployments
- Implement robust error handling for AWS service exceptions

---

## 🧠 Shell Scripting Concepts Used

| Concept              | Description                                                                 |
|----------------------|-----------------------------------------------------------------------------|
| **Functions**         | Modular tasks for EC2/S3 creation and deployment verification               |
| **Arrays**            | Track and manage created resources                                          |
| **Environment Variables** | Store AWS credentials and region settings securely                        |
| **Command Line Arguments** | Customize behavior with inputs like instance type and bucket name         |
| **Error Handling**    | Gracefully catch and respond to AWS service failures                        |

---

## ⚙️ Prerequisites

- AWS CLI installed and configured
- Valid AWS credentials with permissions for EC2 and S3
- Bash shell environment

---

## 📦 Usage

```bash
./aws_setup.sh <instance_type> <bucket_name>
