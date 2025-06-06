# CSC3402_Project
# 🌍 TRAVEL.NOW

*Empowering seamless travel bookings with modern web technologies.*

![last-commit](https://img.shields.io/github/last-commit/ixgnoy/TravelNow)
![repo-top-language](https://img.shields.io/github/languages/top/ixgnoy/TravelNow)
![repo-language-count](https://img.shields.io/github/languages/count/ixgnoy/TravelNow)
![Visitors](https://visitor-badge.laobi.icu/badge?page_id=ixgnoy.TravelNow)


---

## ✨ Features

- ✅ User Authentication & Authorization  
- 🛠️ Admin-side CRUD for:  
  - Packages  
  - Bookings  
  - Users  
- ✏️ User-side CRUD for:
  - Booking  
  - Payment  
- 🧩 Package Listings  
- 🕒 Booking Sessions  
- 💳 Payment Integration
- 🤖 AI-Powered Chatbot Features:  
  - Real-time user assistance  
  - Context-aware conversation powered by Gemini API  
  - User-friendly chat interface  
  - Collects user information and provides personalized responses  
- 💬 Real-time User Interaction & Support via Chatbot  
- 🔄 Seamless Integration between Chatbot and Backend Services    

---

## 🧠 Skills & Tech Stack

### 🧑‍💻 Front-End
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-005F0F?style=for-the-badge&logo=thymeleaf&logoColor=white)

### ☕ Back-End
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![Spring Web](https://img.shields.io/badge/Spring_Web-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/JPA-007396?style=for-the-badge&logo=hibernate&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)  
![Gemini API](https://img.shields.io/badge/Gemini_API-4285F4?style=for-the-badge&logo=google&logoColor=white)

### 🗃️ Database
![H2](https://img.shields.io/badge/H2-1F4E79?style=for-the-badge&logo=h2&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)

### 🛠️ Tools & Utilities
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Validation API](https://img.shields.io/badge/Validation_API-000000?style=for-the-badge)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)

---

## 🧩 System Design & Architecture

- 🧬 **Database Design (ERD)**  
- 🏗 **Application Design using MVC Architecture**


- <h3>ERD is as below:</h3>
  <img src="https://github.com/ixgnoy/CSC3402_Project/blob/main/ERD/ERD.png" />
  <hr>

<h3>The Architecture Diagram:</h3>
<img src="Architecture Diagram/diagram (travel.Now).png"/><br>
  
Relationship is as below:

- One-to-Many Relationship between User and Book (one user can make multiple bookings).
- One-to-One Relationship between Book and Payment (one booking can have only one payment).
- One-to-One Relationship between Book and Package (one booking can be within only one package).
<br>
<h3>Latest Feature:</h3>
- Implemented Intelligent Chabot using Gemini API (Flash 2.0 Model) with restricted safety feature to avoid offensive language:<br>
- I chose to use a Microservice Architecture with Node.js to build the chatbot using the Gemini API because it allows for better scalability, modularity, and easier maintenance. By isolating the chatbot functionality into a separate microservice, it becomes independent from the main application, making it easier to update, debug, and scale as needed. Node.js is ideal for this setup due to its non-blocking, event-driven nature, which enables efficient handling of API requests and real-time communication. This approach also keeps the system flexible and allows other parts of the platform to interact with the chatbot via a simple API call.
<br>
  <img src="image_chatbot/chatbot.png"/>
<br>
Demonstration is as below:
1. Login when you're a registered user:<br>
   (https://youtu.be/umv8zJHvv3A "Database Web Dev Demo Video")

2. Register a new account when you're a new user of Travel.Now: <br>
   (https://youtu.be/Gby6tjzD_EU "Database Web Dev Demo Video of Register A New Account")

3. Accessing the H2 Database: <br>
   (https://youtu.be/7N39x59Ddkw "Database Web Dev Demo Video of Accessing H2 Db")

