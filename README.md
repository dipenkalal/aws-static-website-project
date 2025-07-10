
# AWS Static Website Project (Module 1)

This project demonstrates how to deploy a **static website** using AWS services like EC2, EBS, IAM, and optionally EFS — all via the AWS Management Console.

---

## 📌 Objectives

- Deploy a basic static HTML page using an Apache HTTP server on an EC2 instance.
- Persist website data using an attached **EBS volume**.
- Use **IAM roles** to securely manage permissions.
- (Optional) Explore mounting an **EFS file system**.
- Learn AWS hands-on using **zero CLI**.

---

## 📁 Project Structure

```
aws-static-website-project/
│
├── docs/               # PDF Documentation of full deployment steps
├── IAM/                # Screenshots related to IAM user/role setup
├── screenshots/        # EC2, EBS, SSH, and Website preview screenshots
├── scripts/            # User data scripts or setup templates
├── videoclips/         # Optional screen recordings or demo walkthroughs
└── README.md           # This file
```

---

## 🧪 Setup Summary

### ✅ EC2 Instance
- Launched from Console (Amazon Linux 2)
- Apache installed via **User Data**
- Public IPv4 address used to access site

### 💽 EBS Volume
- Created and attached to EC2
- Formatted and mounted from within EC2 via SSH

### 🔐 IAM Role
- Custom IAM role (`Project1A`) created
- EC2 instance updated to assume the role securely

---

## 📸 Highlights

All screenshots are captured and categorized by stage in:
- `screenshots/`: EC2 + EBS + IAM User + Role Setup
- `docs/`: Final PDF report for submission or reference

---

## 📄 Documentation

Download the full setup guide:  
[📥 Project1A_Complete_AWS_Documentation.pdf](./docs/Project1A_Complete_AWS_Documentation.pdf)

---

## 🚀 Live Test

After launching your EC2 instance:
```bash
http://<your-public-ip>
```
You should see:
```
Hello! Welcome to My Static Website!
```

---

## 🛠 Tech Stack

- **Amazon EC2**
- **Amazon EBS**
- **IAM (Roles + Users)**
- **User Data (Bash script)**
- **AWS Console UI**

---

## 👨‍💻 Author

Dipen Patel – *AWS Cloud Engineering – Module 1 Hands-on Project*

---

## 📬 Feedback or Issues?

Create an [Issue](https://github.com/your-repo/issues) or contact me directly via GitHub.

---
