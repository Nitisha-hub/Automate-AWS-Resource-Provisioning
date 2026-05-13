# Automate-AWS-Resource-Provisioning
Developed a cloud automation project that provisions and manages AWS resources programmatically using Python and the boto3 SDK. The project automates the creation and management of services such as Amazon EC2, Amazon S3, and AWS IAM, reducing manual configuration efforts and improving operational efficiency.


## 📌 Project Overview
This project automates the provisioning and management of AWS cloud resources using Python and the boto3 SDK. Instead of manually configuring services through the AWS Management Console, the project uses scripts to create and manage AWS infrastructure efficiently.

The automation includes:
- Launching EC2 instances
- Creating S3 buckets
- Managing IAM users
- Secure AWS authentication setup

This project demonstrates basic cloud automation and Infrastructure as Code (IaC) concepts using AWS and Python.

---

## 🚀 Features
- Automated EC2 instance creation
- Automated S3 bucket provisioning
- IAM user creation and management
- Python-based AWS automation
- Git and GitHub integration
- Easy-to-understand modular scripts

---

## 🧰 Technologies Used
- Python
- boto3
- AWS EC2
- AWS S3
- AWS IAM
- Git
- GitHub

---

## 📂 Project Structure

```text
aws-automation-project/
│
├── ec2_launch.py
├── s3_bucket.py
├── iam_user.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Prerequisites

Before running the project, ensure you have:

- Python installed
- AWS account
- AWS CLI configured
- IAM permissions for EC2, S3, and IAM services

Install AWS CLI:

```bash
pip install awscli
```

Configure AWS credentials:

```bash
aws configure
```

Enter:
- AWS Access Key
- AWS Secret Key
- AWS Region
- Output format

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/aws-automation-project.git
```

Move into the project directory:

```bash
cd aws-automation-project
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Scripts

### Create S3 Bucket

```bash
python s3_bucket.py
```

### Launch EC2 Instance

```bash
python ec2_launch.py
```

### Create IAM User

```bash
python iam_user.py
```

---

## 🔐 AWS Services Used

### AWS IAM
Used for secure identity and access management.

### Amazon EC2
Used to provision virtual server instances.

### Amazon S3
Used for scalable cloud object storage.

---

## 📸 Output Examples
- EC2 instance created successfully
- S3 bucket provisioned
- IAM user generated

---

## 💡 Future Enhancements
- Add AWS Lambda automation
- Integrate CloudWatch monitoring
- Add Terraform support
- Build Flask dashboard
- Implement CI/CD pipeline using GitHub Actions
- Docker integration

---

## 📚 Learning Outcomes
Through this project, you will learn:
- AWS cloud fundamentals
- Python automation scripting
- boto3 SDK usage
- Infrastructure automation concepts
- GitHub project management

---

## 👨‍💻 Author
Nitisha Mali

Final Year B.Tech AIML Student  
R.C. Patel Institute of Technology, Shirpur

---

## 📄 License
This project is created for educational and learning purposes.
