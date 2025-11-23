# Azure Infrastructure Project  
### VM + VNet + NSG + Load Balancer + Storage  
### Built using Microsoft Azure Sandbox (Free)

## 📌 Overview  
This project demonstrates a basic cloud infrastructure setup using Azure.  
It includes virtual machines, networking, security groups, a load balancer, and storage resources.

## 🚀 What I Built  
- 1x Linux Virtual Machine (Ubuntu)
- 1x Virtual Network (VNet)
- Subnets
- Network Security Group (NSG)
- Azure Load Balancer (Layer 4)
- Public IP + NIC
- Azure Storage (Blob + File Share)

## 🧰 Tools Used  
- Microsoft Azure Sandbox  
- Azure Portal  
- Bash / SSH  
- draw.io (architecture diagram)  

## 🏗 Architecture Diagram  
*(Insert image here later — I’ll show you how)*  

Example diagram structure:
Client → Load Balancer → VM
↳ VNet → Subnet → NSG
↳ Storage Account

## 🔧 Step-by-Step Deployment  
1. Create a Resource Group  
2. Deploy Linux VM  
3. Create VNet + Subnet  
4. Create NSG & rules (SSH, HTTP, custom ports)  
5. Attach NSG to subnet/NIC  
6. Deploy Load Balancer  
7. Attach VM backend pool  
8. Create/probe health checks  
9. Create Storage Account  
10. Upload/download files  
11. Test Load Balancer traffic  

## 📸 Screenshots  
*(Add later — I’ll show you how)*  
- VM overview  
- VNet + Subnets  
- NSG rules  
- Load Balancer backend  
- Storage containers  

## 📚 What I Learned  
- Azure compute basics (VMs)  
- Networking (VNets, subnets)  
- Security (NSGs, RBAC basics)  
- Load balancing concepts  
- Storage account configuration  

## 🟢 Status  
Completed ✔️  
