# 🚀 CC Mini Project

This project demonstrates a complete CI/CD pipeline using GitHub Actions, Docker, and cloud deployment.

---

## ⚙️ CI/CD Pipeline

* **Feature branches** → Build + Test stages
* **Main branch** → Full pipeline (Build + Test + Docker + Deploy)

---

## 🌐 Live Deployment (Render)

👉 https://cc-project-p9gg.onrender.com

---

## 📦 Run with Docker (Recommended)

No need to install Java or Maven.

```bash
docker pull iqras1555/cc-project:latest
docker run -p 8080:8080 iqras1555/cc-project:latest
```

👉 Open in browser:
http://localhost:8080

---

## 💻 Run Locally from Source

```bash
git clone https://github.com/iqras1555/cc_project.git
cd cc_project/cc-app
./mvnw spring-boot:run
```

👉 Open in browser:
http://localhost:8080

---



---

## 🔌 API Endpoints

| Method | Endpoint    | Description          |
| ------ | ----------- | -------------------- |
| GET    | /tasks      | Get all tasks        |
| POST   | /tasks      | Add new task         |
| DELETE | /tasks/{id} | Delete task by index |

---

## 🐳 Docker Hub

👉 https://hub.docker.com/r/iqras1555/cc-project

---

## 👩‍💻 Contributors

* Iqra Shaikh
* Pranali Nikose
* Sanika Pawar

---

## 🧠 Project Highlights

* CI/CD using GitHub Actions
* Dockerized Spring Boot application
* Cloud deployment using Render
* Automated testing (JUnit + Selenium)

---

## 📌 Author

Iqra Shaikh
GitHub: https://github.com/iqras1555
