Simple Notes App with Jenkins CI/CD
This is a full-stack Notes App built using React and Django, containerized with Docker, and deployed using Jenkins CI/CD. As part of a student project, the app runs on port 8000 and demonstrates core DevOps practices including Dockerization, automated builds, and deployment via Docker Hub.

⚙️ Tech Stack
Frontend: React

Backend: Django

CI/CD: Jenkins

Containerization: Docker

Image Hosting: Docker Hub

Web Server (Optional): Nginx

Deployment Port: 8000

📦 Requirements
Python 3.9

Node.js

Docker & Docker Hub account

Jenkins (installed or via Docker)

GitHub repository for source code

(Optional) Nginx for reverse proxy

🚀 Setup & Deployment
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/LondheShubham153/django-notes-app.git
cd django-notes-app
2. Docker Build
bash
Copy
Edit
docker build -t notes-app .
3. Docker Run
bash
Copy
Edit
docker run -d -p 8000:8000 notes-app:latest
App runs at:
http://localhost:8000
