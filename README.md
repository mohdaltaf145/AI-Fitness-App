# 🧠 AI Fitness Recommendation App

An AI-powered fitness recommendation platform that analyzes user activity and generates personalized workout suggestions using a modern microservices architecture.

---

## 🚀 Tech Stack

- **Backend:** Spring Boot, Spring Cloud  
- **Frontend:** React  
- **Microservices:** Eureka (Service Discovery)  
- **API Gateway:** Spring Cloud Gateway  
- **Messaging:** Apache Kafka  
- **Authentication:** OAuth2 + Keycloak  
- **AI Integration:** Gemini AI  

---

## 📌 Features

- 🔍 Track and analyze user activity data  
- 🧠 AI-driven personalized workout recommendations  
- ⚡ Event-driven architecture using Kafka  
- 🔐 Secure authentication & authorization with Keycloak  
- 🌐 API Gateway for centralized routing  
- 🔄 Scalable microservices architecture  
- 📊 Real-time data processing  

---

## 🏗️ Architecture Overview

- **Eureka Server** → Service discovery  
- **API Gateway** → Entry point for all client requests  
- **User Service** → Manages user data  
- **Activity Service** → Tracks fitness activities  
- **Recommendation Service** → Generates AI-based suggestions  
- **Kafka** → Handles asynchronous communication  
- **Keycloak** → Authentication & authorization  

---

## 📂 Project Structure
fitness-microservices/
│── api-gateway/
│── eureka-server/
│── user-service/
│── activity-service/
│── recommendation-service/
│── frontend-react/
│── docker/
│── README.md


---


---

## ⚙️ Setup & Installation

### 1. Clone the repository

bash
git clone https://github.com/mohdaltaf145/AI-Fitness-App.git
cd AI-Fitness-App

2. Prerequisites

Make sure you have installed:

Java 17+
Node.js
Docker (optional but recommended)
Kafka & Zookeeper

3. Run services in order
Start Eureka Server
Start API Gateway
Start all microservices
Start Kafka & Zookeeper
Start React frontend

4. Access the app
Frontend → http://localhost:3000
API Gateway → http://localhost:8080
Eureka Dashboard → http://localhost:8761
🔐 Authentication
Uses Keycloak for OAuth2-based authentication
Configure the realm, client, and users in Keycloak before running
🤖 AI Recommendation Engine
Integrated with Gemini AI to:
Analyze user activity
Suggest workouts
Provide personalized fitness insights

🧪 Future Improvements
📱 Mobile app integration
📊 Advanced analytics dashboard
☁️ Cloud deployment (AWS/GCP)
🤝 Contributing

Contributions are welcome! Feel free to fork and submit a PR.

📄 License

This project is licensed under the MIT License.

👨‍💻 Author

Altaf Mazhar
Backend Developer | Fitness Enthusiast



