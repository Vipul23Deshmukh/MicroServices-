# Microservices Project

## 📌 Overview
This project demonstrates a microservices-based architecture where different services handle specific business functionalities independently. Each service is containerized and communicates via REST APIs.

## 🏗️ Architecture
- **Service 1 (User Service):** Handles user registration, authentication, and profile management.
- **Service 2 (Booking Service):** Manages reservations and booking workflows.
- **Service 3 (Payment Service):** Processes payments and transaction records.
- **API Gateway:** Routes requests to the appropriate microservice.
- **Database:** Each service has its own database for loose coupling.

## 🚀 Tech Stack
- **Backend:** .NET 8 / Node.js (depending on service)
- **Frontend:** React
- **Database:** MySQL
- **Cloud Deployment:** Azure
- **Containerization:** Docker

## ⚙️ Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/microservices-project.git
