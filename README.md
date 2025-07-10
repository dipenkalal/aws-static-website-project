# 🚀 AWS Static Website Deployment Project

This project demonstrates how to deploy a **static website on AWS** using the **AWS Management Console** only — without writing any code or using the CLI. It includes EC2 for hosting, EBS for persistent storage, optional EFS for shared storage, and IAM for secure access management.

---

## 📌 Project Objective

> Host a static website on an EC2 instance using:
- 🖥️ **EC2** for web hosting
- 💾 **EBS** for persistent data storage
- 📂 **EFS** (optional) for scalable storage
- 🔐 **IAM** roles for secure permissions

---

## 🧰 Services Used

| Service | Purpose |
|--------|---------|
| EC2    | Host the Apache web server |
| EBS    | Attach volume for persistent data |
| EFS    | (Optional) For scalable shared storage |
| IAM    | Manage EC2 access securely |

---

## 📸 Screenshots

| Step | Screenshot |
|------|------------|
| EC2 Instance Launch | `/screenshots/ec2-launch.png` |
| EBS Volume Attachment | `/screenshots/attach-ebs.png` |
| IAM Role Creation | `/screenshots/iam-role.png` |
| Static Website Running | `/screenshots/site-success.png` |

---

## 📝 Steps Followed

1. ✅ Created EC2 instance with Amazon Linux 2 and User Data script
2. ✅ Attached an EBS volume to the instance
3. ✅ Created and configured an EFS file system (optional)
4. ✅ Created an IAM Role with necessary policies
5. ✅ Deployed a static website using Apache HTTP Server
6. ✅ Accessed the website via EC2 Public IP
