# Terraform - DevOps
This repository is your one stop solution for Terraform for DevOps Engineers

# Terraform Commands - Complete Guide

## **1. Setup & Initialization**
### **Install Terraform**

``sh
# Linux & macOS
curl -fsSL https://apt.releases.hashicorp.com/gpg | sudo apt-key add -
sudo apt-add-repository "deb [arch=amd64] https://apt.releases.hashicorp.com $(lsb_release -cs) main"
sudo apt-get update && sudo apt-get install terraform

# Verify Installation
terraform -v
```