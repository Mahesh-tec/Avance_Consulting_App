# 🔗 URL Shortener Web Application

A full-stack URL Shortener built with **Spring Boot** and **React.js** that shortens long URLs, validates them, and supports expiration logic.

---

## 🚀 Features

- 🔗 Converts long URLs like `https://www.google.com` into short ones like `http://localhost:8080/d245e3`
- ✅ **URL structure validation**
- 🔁 **Handles duplicate URLs** — returns the same short URL if already generated
- ⏱️ **URL expiry logic** — each short URL is valid for **5 minutes**
- 🕔 **Expired URLs** show an error message after expiry
- ❓ **Invalid/non-existing short codes** show a user-friendly message and redirect to home
- ⚛️ Built with **React (frontend)** + **Spring Boot (backend)**


---

## 🖥️ How to Run the Application Locally

## Frontend (React.js)

Navigate to the frontend folder

Install dependencies:

bash
Copy
Edit
npm install
Start the development server:

bash
Copy
Edit
npm start
This starts the app on http://localhost:3000

###  Backend - Spring Boot (Port: `8080`)

1. Navigate to `backend/`
2. Run the app using your IDE or terminal:

```bash
./mvnw spring-boot:run
