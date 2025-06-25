# ☁️ Containerized Java Web Application

## 🧩 Project Overview

This project demonstrates the containerization of a **multi-tier Java web application** using **Docker** and **Vagrant**. It includes separate containers for the **App**, **Database**, and **Web** tiers. The setup is fully automated and runs inside a local virtual environment powered by Vagrant.

---

## 🛠️ Tools & Technologies Used

- Docker
- Docker Compose
- Vagrant
- Java
- Apache HTTP Server
- MySQL
- Shell Scripting

---

## 📂 Project Structure

containerized-java-webapp/
├── app/ # Java app Dockerfile and source
├── db/ # MySQL Dockerfile and schema
├── web/ # Apache web server Dockerfile
├── docker-compose.yml # Orchestration file
├── Vagrantfile # Virtual machine provisioning
├── screenshots/ # Demo images
└── README.md