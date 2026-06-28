# AWS Infrastructure Automation - Secure S3 Bucket

## 📌 Project Overview
This repository contains an Infrastructure as Code (IaC) template developed with AWS CloudFormation. It automates the deployment of a highly secure and cost-optimized Amazon S3 bucket designed to store critical corporate documents.

## 🛡️ Implemented Features
* **Automated Deployment:** Multi-resource provisioning using AWS CloudFormation templates.
* **Data Protection:** Active **S3 Versioning** enabled to safeguard files against accidental deletion or modifications.
* **Security Hardening:** Implicit **Public Access Block** configuration to isolate data from non-authorized internet traffic.
* **Cost Optimization:** Custom **S3 Lifecycle Policy** to automatically transition objects to Amazon S3 Glacier after 30 days of retention, reducing storage costs.

## 🛠️ Tech Stack
* **Cloud Provider:** Amazon Web Services (AWS)
* **Infrastructure as Code (IaC):** AWS CloudFormation (YAML)
* **Storage Services:** Amazon S3 & Amazon S3 Glacier
* 
