🤖 Spring AI Chatbot — Backend

A REST API built using Spring Boot that connects with an AI model to generate chatbot responses for the frontend application.

🚀 Live API

Base URL:

https://spring-ai-chatbot-backend.onrender.com

✨ Features

REST API for chatbot interaction

AI response generation

CORS enabled for frontend communication

Lightweight API design

Cloud deployment on Render

🛠️ Tech Stack

Java

Spring Boot

Maven

REST Controller

AI API Integration

📂 Project Structure
src/main/java/
 ├── controller/
 ├── service/
 ├── config/
 └── SpringAiChatbotApplication.java

pom.xml
⚙️ Setup Instructions
1️⃣ Clone Repository
git clone https://github.com/asmanisha/spring-ai-chatbot-backend.git
cd spring-ai-chatbot-backend
2️⃣ Build Project
mvn clean install
3️⃣ Run Application
mvn spring-boot:run

Server runs at:

http://localhost:8080
🔌 API Endpoint
Ask AI
GET /ask-ai?prompt=<message>

Example:

http://localhost:8080/ask-ai?prompt=Hello

Response:

{
  "response": "Hello! How can I help you?"
}
🌐 CORS Configuration

Backend allows requests from frontend domain:

https://spring-ai-chatbot-frontend.onrender.com

❗ Common Issues
ERR_CONNECTION_RESET

Render backend goes to sleep after inactivity.

Solution:
Open backend URL manually to wake server.

🔮 Future Improvements

Conversation memory

Authentication system

Streaming responses

Rate limiting

Logging & monitoring

👩‍💻 Author

Manisha
B.Tech IT — Final Year

Output of chatbot
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/bc494cc7-8b76-4638-adff-f407dfb2c9f8" />
