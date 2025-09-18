
# beforehend-end-finaltargil

This repository demonstrates the use of **Terraform** and **Ansible** to define, provision, and configure infrastructure.

---

## Project Structure

- **terraform/** — Terraform code to create infrastructure resources  
- **ansible/** — Ansible playbooks and roles for configuration  
- **.gitignore** — Excludes unnecessary or large files such as `.terraform/`  
- **LICENSE** — GPL-3.0 license  

---

## Requirements

Before using this repository, install:

- [Terraform](https://developer.hashicorp.com/terraform/downloads)  
- [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)  
- A cloud provider account (such as AWS) with valid credentials  



## How to Use

### 1. Clone the Repository
```bash
git clone https://github.com/Mordonlan/beforehend-end--finaltargil.git
cd beforehend-end--finaltargil


cd terraform
terraform init
terraform plan
terraform apply

terraform init — downloads required providers and sets up the project

terraform plan — shows what will be created or changed

terraform apply — provisions the resources


# Clone repository
git clone https://github.com/Mordonlan/beforehend-end--finaltargil.git
cd beforehend-end--finaltargil

# Run Terraform
cd terraform
terraform init
terraform plan
terraform apply

# Run Ansible
cd ../ansible
ansible-playbook -i inventory site.yml
--------------------------------------------
