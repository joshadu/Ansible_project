
# Ansible in production project

![image](https://github.com/joshadu/Ansible_project/assets/45633182/8bb5c4fa-fdc6-4672-b9d3-4c237159ec1b)

In this project, we created a production environment that consists of four Ubuntu virtual machines set up using Terraform.  One virtual machine is connected to the Internet and private subnet which acts as a jumphost and HTTP load balancer. Other virtual machines are only connected to the private subnet and act as web servers. Ansible is used for configuration management of the virtual machines to set the nginx HTTP load balancer and Terraform is used for the cloud environment management.

# Tools explored

- Terraform: Infrastructure as Code for VM deployment on CSC cPouta
- Ansible: nginx HTTP load balancer configuration and webserver setup
- Python: Ansible virtual environment setup
- Git: Version control

