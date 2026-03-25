# CA1 - Cloud Infrastructure & Virtualisation (Docker Project)
**Student Name:** Fady Abdelrahman Mohamed  
**Student ID:** 20053593  
**Lecturer:** Paul Laird  
**Academic Year:** 2025/2026

## Project Overview
This repository contains the practical implementation for the CA1 assignment. The goal of this project was to demonstrate proficiency in containerization using Docker and deploying a multi-container application on Google Cloud Platform (GCP).

## Technologies Used
* **Docker:** For containerizing the application.
* **Docker Compose:** To manage multi-container setups (App + Database).
* **Google Cloud (GCP):** Hosted on a Compute Engine VM instance.
* **Python/Node.js:** Core application environment.
* **MySQL:** Persistent database storage.

## Key Features Implemented
1. **Dockerfile Configuration:** Created a custom Dockerfile with optimized layers.
2. **Data Persistence:** Implemented Docker Volumes to ensure data (Todos) is saved even after containers restart.
3. **Docker Networking:** Configured a private bridge network for secure communication between the app and the database.
4. **Automation with Compose:** Defined the entire infrastructure in a `docker-compose.yml` file for one-command deployment.
5. **Cloud Deployment:** Successfully deployed and tested the application on a public IP address using GCP.

## How to Run the Project
To run this project on your local machine or a VM, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/FadyAbdelrahman/CA1-Docker-Cloud-Infrastructure.git](https://github.com/FadyAbdelrahman/CA1-Docker-Cloud-Infrastructure.git)
   cd CA1-Docker-Cloud-Infrastructure
