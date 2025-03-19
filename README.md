# cyberranges
project to create virtual cyber range with a single click. 

This project will have kafka cluster, which will be getting streams metrics from ELK stacks and will be managed by kubernetes.
For Infra provisioning, we will use Terraform.
For Configuration management it will be Ansible and Python is perffered programming language on this. 

Intention is to create provision such a system in multi environment (dev, staging, prod), and multiple platforms (proxmox, aws) spread across multiple zones.

GIT Branching Strategy
======================
main → Stable production code.
develop → Latest development changes (integration branch).
feature/* → New features (branched from develop).
release/* → Prepares for release (branched from develop).
hotfix/* → Emergency fixes (branched from main).

![image](https://github.com/user-attachments/assets/ed0be2e2-c2e8-4cc1-a6a7-cc934e8b5c15)

creating branches 
