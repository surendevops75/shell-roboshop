# Shell Roboshop Automation 🚀

## 📌 Repository Description

This repository contains shell scripts to automate the provisioning, configuration, and deployment of the Roboshop microservices application.

It demonstrates real-world DevOps automation using Linux shell scripting for application services, databases, web servers, messaging systems, and supporting components.

---

## 📌 Project Overview

Roboshop is a microservices-based e-commerce application commonly used for DevOps practice.



This repository automates the setup of:

- Frontend Web Server
- Backend Microservices
- Databases
- Cache Layer
- Message Queue
- Service Management

---

## 🛠 Technologies Used

- Linux Shell Scripting
- Bash
- Systemd
- Nginx
- MongoDB
- MySQL
- Redis
- RabbitMQ

---

## 📂 Repository Structure

```bash
shell-roboshop/
│── roboshop.sh
│
│── frontend.sh
│── nginx.conf
│
│── cart.sh
│── cart.service
│
│── catalogue.sh
│── catalogue-set.sh
│── catalogue.service
│
│── user.sh
│── user.service
│
│── payment.sh
│── payment.service
│
│── shipping.sh
│── shipping.service
│
│── mongodb.sh
│── mongo.repo
│
│── mysql.sh
│
│── redis.sh
│
│── rabbitmq.sh
│── rabbitmq.repo
```
---

## ⚙️ Services Automated
# Frontend
- Nginx installation
- Reverse proxy configuration
- Static content deployment

# Application Services
- Cart
- Catalogue
- User
- Payment
- Shipping

# Databases
- MongoDB
- MySQL

# Middleware
- Redis
- RabbitMQ

---

## 🚀 How to Run

Give execute permission:

```bash
chmod +x *.sh
```

Run main script:

```bash
./roboshop.sh
```

Run individual service setup:


```bash
./frontend.sh
./mongodb.sh
./cart.sh
```

---

## 🎯 Key Features
- End-to-end Roboshop setup automation
- Repeatable server provisioning
- Multi-service deployment
- Linux administration practice
- Production-style service management

---

## 📈 Use Cases
- DevOps Interview Preparation
- Shell Scripting Practice
- Linux Server Automation
- Multi-tier Application Deployment
- Real-world Infrastructure Setup

---

## 👨‍💻 Author

Surendra

DevOps Engineer

---

⭐ If you like this project, give it a star.