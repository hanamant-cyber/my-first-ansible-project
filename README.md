🍔 Food Delivery Website Deployment using Ansible & AWS EC2
📖 Project Overview

This project demonstrates how to automate the deployment of a static web application using Ansible on an AWS EC2 instance.
The website is a responsive Food Delivery Portfolio built using HTML, CSS, and JavaScript, and deployed automatically via Ansible playbooks.

🧠 Objective

To automate the full deployment process — from installing the web server to copying application files — with zero manual setup.

🧩 Architecture Diagram
           +---------------------------+
           |     Control Node (WSL)    |
           |  • Ansible installed      |
           |  • Contains Playbook      |
           +------------+--------------+
                        |
                        | SSH (Port 22)
                        v
           +---------------------------+
           |     AWS EC2 Instance      |
           |  • Ubuntu 24.04 LTS       |
           |  • Apache2 Web Server     |
           |  • Deployed Food Website  |
           +---------------------------+

⚙️ Tech Stack
Component	Description
Ansible	Configuration management and deployment tool
AWS EC2 (Ubuntu)	Cloud hosting environment
Apache2	Web server used to host the HTML files
HTML, CSS, JS	Frontend static website
Git & GitHub	Version control and portfolio hosting.......
