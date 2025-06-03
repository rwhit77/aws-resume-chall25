# aws-resume-chall25
🌟 Cloud Resume Challenge – My AWS-Powered Personal Portfolio
# 🌐 Cloud Resume Challenge – AWS-Powered Portfolio Site

This project is a fully serverless, cloud-native implementation of my personal resume website — built on AWS and deployed entirely with Infrastructure as Code using Terraform.

It demonstrates practical AWS skills across networking, compute, storage, APIs, and automation. The site is fast, secure, and auto-deploys via GitHub Actions whenever I push changes to the codebase.

---

## 🔧 Technologies & Services Used

- **Frontend:** HTML5, CSS3 (customized from an HTML5 UP template)
- **Hosting:** Amazon S3 (Static Website Hosting)
- **CDN & HTTPS:** Amazon CloudFront + AWS Certificate Manager
- **Domain (Optional):** Amazon Route 53
- **Backend API:** AWS Lambda (Python) + Amazon API Gateway
- **Database:** Amazon DynamoDB (Visitor Counter)
- **Infrastructure as Code:** Terraform
- **CI/CD:** GitHub Actions

---

## 📐 Architecture

```text
[ HTML Resume Site ]
        ↓
    [ S3 Bucket ]
        ↓
[ CloudFront Distribution ]
        ↓
[ API Gateway → Lambda → DynamoDB ]
