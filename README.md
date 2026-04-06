# aws-ec2--webserver
Deploying a web server on AWS EC2 using Linux and Apache with secure configuration
# AWS EC2 Web Server Deployment

## Overview
This project demonstrates how to deploy a web server on AWS EC2 using a Linux instance. Apache web server is installed and configured to host a basic website.

##  Services & Tools Used
- AWS EC2
- Linux (Amazon Linux)
- Apache (httpd)
- SSH
- Security Groups

##  Steps Performed
1. Launched an EC2 instance on AWS
2. Connected to the instance using SSH
3. Installed Apache web server (httpd)
4. Started and enabled Apache service
5. Configured Security Groups to allow HTTP (port 80) and SSH (port 22)
6. Hosted a sample web page

##  Output
- Successfully hosted a website on EC2 instance
- Accessed using public IP in browser

## 📸 Screenshots
These screenshots demonstrate the complete deployment process and successful hosting of the web server on AWS EC2.

- EC2 instance running
- <img width="1913" height="905" alt="image" src="https://github.com/user-attachments/assets/6a60d9cf-c45e-41a0-b557-9df81b168670" />

- SSH connected
- <img width="1230" height="650" alt="image" src="https://github.com/user-attachments/assets/61a5ab7c-b7b4-4f9b-937d-a09bb307a1ac" />

- Apache service status
- <img width="1431" height="837" alt="image" src="https://github.com/user-attachments/assets/0dbfd1ea-6ea6-4fe8-9662-2e59d4723f41" />

- Web page output in browser
- <img width="712" height="375" alt="image" src="https://github.com/user-attachments/assets/bb9bb1da-8928-443d-866d-5d1a9b5d22ad" />
- stop & terminate instance after completion to avoid unnecessary billing.
- <img width="1561" height="367" alt="image" src="https://github.com/user-attachments/assets/b2fe68a0-8859-4e5e-8d23-efc266c644ec" />



## 🎯 Key Learning
- Hands-on experience with EC2
- Linux server setup and management
- Web server configuration
- Basic networking and security concepts
