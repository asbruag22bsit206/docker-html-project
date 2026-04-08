Docker Containerization for HTML Web Application
A simple Dockerized HTML web application deployed using Nginx.

About the Project
    This project demonstrates how containerization simplifies the deployment of an HTML web application using Docker. It ensures consistent performance across different environments and reduces manual setup.
    
 Technologies Used
- HTML5
- CSS3
- JavaScript
- Docker
- Nginx

 Project Structure
- index.html
- styles.css
- script.js
- Dockerfile
- docker-compose.yml
- 
 How to Run the Project

Step 1: Build Docker Image
docker build -t my-html-app .

Step 2: Run Docker Container
docker run -d -p 8080:80 my-html-app

Step 3: Open in Browser
http://localhost:8080
OR using Docker Compose:
docker-compose up -d

 Output Screenshots
Docker Build 
docker build -t my-html-app .

Docker Run
docker run -d -p 8080:80 my-html-app

Browser Output
![Browser Output](docker-output.png)

Features
- Containerized deployment
- Lightweight and fast
- Easy to scale
- Cross-platform support
- No dependency conflicts

 Future Enhancements
- Kubernetes deployment
- CI/CD pipeline integration
- Database integration (MySQL/MongoDB)
- Improved UI design

👨‍💻 Author

Bidhu P
