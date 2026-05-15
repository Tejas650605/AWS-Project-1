# ☁ AWS IAM Policy — Region Restricted EC2 Access

## 📌 Project Overview

This project demonstrates how to create an AWS IAM policy that grants full Amazon EC2 access only in the Paris region (`eu-west-3`) and explicitly denies EC2 access in all other AWS regions.

The project focuses on AWS IAM security, region-based access control, and cloud security best practices.

---

## 🚀 Features

- Full EC2 access only in Paris region (`eu-west-3`)
- Explicit deny access in all other AWS regions
- IAM custom policy implementation
- Region-based security control
- AWS cloud security best practices

---

## 🛠 AWS Services Used

- AWS IAM
- Amazon EC2
- AWS Management Console

---

## 📖 Implementation Steps

### Step 1 — Open IAM Dashboard
- Login to AWS Management Console
- Search for IAM service
- Open IAM Dashboard

---

### Step 2 — Create IAM Policy
- Navigate to Policies
- Click Create Policy
- Open JSON Editor

---

### Step 3 — Add Custom Policy
- Paste the region restricted EC2 policy JSON
- Review policy configuration

---

### Step 4 — Create Policy
- Enter policy name
- Save the policy

---

### Step 5 — Attach Policy to IAM User
- Open IAM Users
- Select target IAM user
- Add permissions
- Attach created policy

---

## 🔐 Security Concepts Used

- IAM Custom Policies
- Region-Based Access Control
- Explicit Deny Rules
- Least Privilege Principle
- Cloud Security Best Practices

---

## 🎯 Expected Result

✅ EC2 access allowed only in Paris region (`eu-west-3`)  
❌ EC2 access denied in all other AWS regions

---


---

## 👨‍💻 Developer

Tejas Kherade
