# 🚀 VProfile Project - Multi-Tier Application Deployment

Welcome to the **VProfile** project! This repository contains everything you need to deploy a **multi-tier web application** using different methods:

![image alt](https://github.com/rajatrajat0210/VProfile-Setup/blob/main/vprofile1.jpg?raw=true)
![image alt](https://github.com/rajatrajat0210/VProfile-Setup/blob/main/vprofile2.jpg?raw=true)
![image alt](https://github.com/rajatrajat0210/VProfile-Setup/blob/main/vprofile3.jpg?raw=true)
![image alt](https://github.com/rajatrajat0210/VProfile-Setup/blob/main/dockerimg.jpg?raw=true)



✅ **Manual VM Provisioning** 🖥️ - Step-by-step setup using Vagrant 
✅ **Automated VM Provisioning** ⚙️ - Provisioning via Vagrant & Ansible  
✅ **Docker-based Deployment** 🐳 - Fully containerized setup using Docker  

---

## 📌 **Project Overview**
VProfile is a **multi-tier web application** that consists of multiple services running on different virtual machines (VMs) or containers:

- **Frontend Web Service** → Nginx  
- **Application Server** → Tomcat  
- **Database Server** → MySQL  
- **Cache System** → Memcached  
- **Message Queue Service** → RabbitMQ  
- **Search & Indexing** → Elasticsearch  

💡 **You can deploy this using VMs or Docker, based on your preference!**

---

# 🛠️ **1️⃣ Manual VM Provisioning**
In this method, each service is set up on a separate **Virtual Machine** (VM) manually.

### **🛠️ Prerequisites**
- **Oracle VM VirtualBox** 🏗️
- **Vagrant** 🏡
- **Git Bash / Command Line** 💻

### **🚀 Steps to Set Up VMs Manually**
```bash
# Install vagrant hostmanager plugin (if not installed)
vagrant plugin install vagrant-hostmanager

# Clone the repository
git clone -b local https://github.com/hkhcoder/vprofile-project.git
cd vprofile-project

# Navigate to manual provisioning folder
cd vagrant/Manual_provisioning

# Bring up the VMs
vagrant up
```

### **🚀 Steps to Set Up VMs Automatic**
```bash
Copy
Edit
# Clone the repository
git clone -b local https://github.com/hkhcoder/vprofile-project.git
cd vprofile-project

# Navigate to automated provisioning folder
cd vagrant/Automated_provisioning

# Run Vagrant with Ansible
vagrant up
```

### **🚀 Steps to Set Up VProfile using all Microservices using Docker**
```bash
Copy
Edit
# Clone the repository
git clone -b docker https://github.com/hkhcoder/vprofile-project.git
cd vprofile-project/docker

# Run the entire stack using Docker Compose
docker-compose up -d
```



