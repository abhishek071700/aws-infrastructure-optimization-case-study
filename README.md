# AWS Cost Optimization & Infrastructure Audit – Case Study (Client A | NDA Masked)

[![AWS](https://img.shields.io/badge/AWS-Infrastructure%20Audit-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://aws.amazon.com/)
[![Savings](https://img.shields.io/badge/Estimated%20Savings-$144%20to%20$165%2Fmonth-success?style=for-the-badge)](#total-estimated-savings)
[![NDA](https://img.shields.io/badge/NDA-Sanitized%20Report-blue?style=for-the-badge)](#nda--confidentiality)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

> Portfolio case study documenting a real-world AWS environment review and optimization assessment.  
> Client identity and infrastructure identifiers are anonymized due to NDA.

---

## 📌 Project Overview
**Date:** January 2025  
**Prepared By:** Abhishek Pandey  
**Role:** Cloud Pre-Sales Engineer (AWS)  
**Client:** Client A (Masked)  
**Region:** ap-south-1 (Mumbai)

---

## 🎯 Objective
- Audit current AWS infrastructure
- Analyze utilization via CloudWatch (~4 weeks)
- Identify cost inefficiencies and rightsize compute
- Recommend improvements without impacting reliability or security

---

## ⚠️ NDA & Confidentiality
- Client name and organization details removed
- Instance IDs, bucket names, IPs masked
- Workload names generalized (Production / Staging)

---

## 🏗️ Environment Summary (Masked)
**Key Services Observed:** EC2, S3, VPC, ELB/ALB, CloudWatch, IAM, Route53, WAF, Lambda, DynamoDB, CloudFront, SNS/SQS

---

## 💰 Key Recommendations
### 1) EC2 Rightsizing
Estimated monthly savings: **~$77.24**

### 2) Intel → AMD x86 Modernization (if compatible)
Estimated monthly savings: **~$47.59**

### 3) Reserved Instances (No Upfront)
- 1-Year RI: **~$27.95/month**
- 3-Year RI: **~$53.36/month**

### 4) Waste Cleanup (EIPs / snapshots)
Estimated monthly savings: **~$10.95**

---

## 📊 Total Estimated Savings
**Estimated range:** **~$141.55 to $165.42 / month**  
**Annual impact:** **~$1,700 to $2,000 / year**

---

## 🔒 Security Recommendations (Summary)
- Enable MFA (especially privileged users)
- Rotate and audit access keys
- Least privilege IAM policies
- Encrypt EBS using AWS KMS
- Reduce public exposure (private subnets)
- Enable Trusted Advisor + VPC Flow Logs

---

## 📂 Repository Structure
```text
aws-infrastructure-optimization-case-study/
├── README.md
└── artifacts/
    ├── ec2-rightsizing-analysis.md
    ├── reserved-instance-analysis.md
    └── security-recommendations.md
```


---

## 👤 Author
**Abhishek Pandey**  
LinkedIn: https://linkedin.com/in/abhishek-pandey-045241316  
GitHub: https://github.com/abhishek071700
