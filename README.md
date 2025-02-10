# DevOps-Demo

![DevOps Demo Screenshot](https://raw.githubusercontent.com/devopslibrary/devops-demo/master/screenshots/overview.png "Overview")

---

## Automation of DevOps Demo App Deployment with Ansible  

### Description  
This project automates the deployment of the [DevOps Demo App](https://github.com/devopsdemoapps/devops-demo.git) on a Debian 11 server using Ansible.  

### Key Features:  
- Installation of all required packages (Nginx, MySQL, and others).  
- Cloning the application repository and extracting files into the created directory.  
- Configuring the `config.ini` file using Ansible templates.  
- Creating a MySQL password, setting up the database, and importing the `devops-demo.sql` file.  
- Removing default Nginx configurations and deploying custom configurations with activation through `sites-available` and `sites-enabled`.  

### Usage  
1. Clone this repository and adjust the variables in the following files:  
   - `config.ini`  
   - Ansible variables   
2. Run the Ansible playbook to automate the deployment process.  

### Requirements  
- Debian 11  
- Ansible
- PHP 7.4  

This project simplifies application deployment and provides flexibility for configuration customization.  

---
