# cloud-security-governance-case-study

Cloud Security case study analyzing AWS security vulnerabilities in a healthcare environment using Defense-in-Depth, IAM,
encryption, Zero Trust, and compliance best practices

Cloud Security Case Study: Securing EHR on AWS
---

📌 Overview
---
A cloud security case study analyzing vulnerabilities in a healthcare organization's AWS environment and proposing a secure architecture using 
Defense in Depth,Zero Trust, and AWS security best practices.

📌Problem
---
A government hospital migrated over 200,000 Electronic Health Records (EHRs) to AWS without implementing adequate security controls, exposing sensitive patient data to unauthorized access and compliance risks.


📌Key Risks
---

- Public S3 buckets
- Missing IAM & RBAC
- No encryption
- Lack of monitoring
- No backup or disaster recovery
- HIPAA & DPDP compliance risks

📌 Proposed Solution
---

- Encrypt data using **AWS KMS**
- Implement **IAM, RBAC & MFA**
- Secure network with **VPC & AWS WAF**
- Monitor using **CloudTrail, GuardDuty & CloudWatch**
- Enable automated backups
- Adopt **Zero Trust** and **Defense in Depth**

## AWS Services

- AWS IAM
- AWS KMS
- Amazon S3
- Amazon VPC
- AWS WAF
- CloudTrail
- GuardDuty
- CloudWatch
- AWS Backup

📌 Key Takeaways
---

- Cloud security is a **shared responsibility**.
- Misconfigurations are a major cause of cloud breaches.
- Encryption, IAM, monitoring, and backups are essential.
- Security should be integrated from the start.

## Full Report

The complete case study is available in **`Cloud_Security_Case_Study.pdf`**.

---

Author
---
K K Pranidhi
