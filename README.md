# AWS VPC Setup — Step-by-step

# Secure Internet Access for Private EC2 via Layered AWS Network Architecture

## Project Overview
This project demonstrates how to establish **secure internet access for a non-public EC2 instance** without exposing it directly to the internet.  
The design uses a **multi-tier VPC architecture** with public and private subnets, NAT gateway for outbound access, and secure routing layers.  

## Repository Structure
├── steps/ # Contains step-by-step explanation of setup


├── images/ # Contains architecture diagrams and output screenshots


└── README.md

## Documentation
- All the detailed step-by-step implementation is documented inside the **`steps/` folder**.  
- Screenshots and diagrams related to VPC, EC2, and private machine outputs are available in the **`images/` folder**.  

## Key Components
- **VPC** with segregated public & private subnets  
- **NAT Gateway** for secure outbound traffic  
- **Route Tables** for controlled communication  
- **EC2 Instance (Private)** accessible securely without public exposure  

## Outputs
Example images of architecture and outputs are available in the `images/` folder, such as:  
- VPC setup  
- EC2 instance configuration  
- Output from private machine  

## ✅ Conclusion
This project highlights how to design a **secure, layered AWS network** ensuring private resources can access the internet safely without being publicly exposed.  

---
📌 Author: *LAKSHANA V*  
📌 Tech: **AWS, Networking, EC2, VPC, NAT Gateway**
