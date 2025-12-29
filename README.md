# Lab 09: Cloud Computing - AWS CLI & Codespaces

This repository contains the documentation and task execution for **Lab 09** of the **Cloud Computing** course.

## Author Information

* 
**Name**: Areej Fatima 


* 
**Registration Number**: BSE-2023-010 



---

## Overview

This lab focuses on setting up and managing cloud resources using the **GitHub CLI** and **AWS CLI** within a GitHub Codespace environment. The primary goal is to demonstrate proficiency in infrastructure management through command-line interfaces, including instance lifecycle management and IAM configurations.

## Tools & Technologies

* 
**Environment**: GitHub Codespaces 


* 
**CLIs**: GitHub CLI (gh) v2.83.2 , AWS CLI 


* 
**Cloud Provider**: Amazon Web Services (AWS) 


* 
**Operating System**: Linux (Ubuntu/Amazon Linux 2) 



---

## Tasks Performed

### 1. GitHub CLI & Codespace Setup

* Installed GitHub CLI using `winget`.


* Authenticated with GitHub via browser-based login.


* Provisioned and connected to a GitHub Codespace (2 cores, 8GB RAM, 32GB storage).



### 2. AWS CLI Configuration

* Installed and verified AWS CLI versioning within the Codespace.


* Configured AWS credentials (Access Key ID, Secret Access Key) and set the default region to `us-east-1`.


* Verified identity using `sts get-caller-identity`.



### 3. Network & Security Management

* Created an EC2 Security Group named **"MySecurityGroup"**.


* Added ingress rules to authorize SSH (Port 22) and HTTP (Port 80) traffic.


* Generated an **ED25519** key pair and saved it as `MyED25519Key.pem`.



### 4. EC2 Instance Operations

* Identified appropriate AMI IDs (Amazon Linux 2) and Subnet IDs.


* Launched an EC2 instance and connected via SSH.


* Managed instance states including stopping, starting, and terminating instances via CLI.



### 5. Resource Discovery & Reporting

* Used `describe` commands to audit VPCs, Subnets, Security Groups, and Availability Zones.


* Applied advanced filters and queries to generate tabular reports for instance types, public IPs, and states.



### 6. IAM & Cleanup

* Managed IAM users and groups, including policy attachments.


* Performed a complete cleanup by terminating instances, deleting volumes/snapshots, and removing security groups/key pairs to avoid unnecessary costs.
