# AWS EKS: Deployment
# Video Tutorial

This repository contains resources and guides based on the video tutorial regarding how to manage deployment availability within **Amazon EKS**.

## 📺 Video Tutorial
Watch the detailed step-by-step guide here:
[![Watch on YouTube](https://img.shields.io/badge/YouTube-Watch-red?style=for-the-badge&logo=youtube)](https://youtu.be/xWqu1Ku7MDQ)

---

## 🛠️ Prerequisites
Before starting the tutorial, ensure you have the following tools installed and configured:

* **AWS CLI:** Configured with appropriate permissions (`AdministratorAccess` or specific EKS/EC2 policies).
* **kubectl:** The Kubernetes command-line tool, version-matched to your cluster.
* **eksctl:** The official CLI for Amazon EKS to create and manage clusters easily.
* **Docker:** To build and push images if you are using a custom application.

---

## 🚀 About the Service: Amazon EKS
**Amazon Elastic Kubernetes Service (Amazon EKS)** is a managed service that makes it easy to run Kubernetes on AWS without needing to install, operate, and maintain your own Kubernetes control plane or nodes.

### Key Benefits:
- **Security & Stability:** Scalable and secure Kubernetes environments by default.
- **Integration:** Native integration with AWS services such as IAM, VPC, and ELB.
- **Managed Control Plane:** AWS manages the availability and scalability of the control plane instances.

---

## 💰 Pricing Model
Amazon EKS uses a flexible billing model to scale with your usage:

| Charge Type | Description | Model |
| :--- | :--- | :--- |
| **EKS Cluster** | Fixed fee per hour for each cluster control plane. | **$0.10 per hour** |
| **Compute (EC2/Fargate)** | Pay for the resources (vCPU/RAM) your nodes use. | **Pay-as-you-go** (per second) |
| **Storage (EBS)** | Pay for the volume of data stored on the node disks. | **Pay per Storage** (per GB/month) |

> **Note:** Costs may vary based on the AWS Region and specific instance types selected.

---

## 📖 Instructions
1. **Clone** this repository to your local machine.
2. **Follow** the detailed instructions in the video [at this link](https://youtu.be/xWqu1Ku7MDQ).
3. **Apply** the `Strategy` configurations (such as `RollingUpdate`) in your deployment YAML file to ensure minimum availability during updates.

---
*Created by [Code Klaudia](https://www.youtube.com/@CodeKlaudia)*
