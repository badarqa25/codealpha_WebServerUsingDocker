#  Docker Web Server Project

This project demonstrates how to build and run a simple static website using **Nginx inside a Docker container**. It’s a great starting point for learning Docker, container lifecycle management, and web server deployment best practices.

---

##  Features

- ✅ Containerized Nginx web server using Docker
- ✅ Custom HTML page served from container
- ✅ Dockerfile for custom image creation
- ✅ Clean and lightweight deployment
- ✅ Easy to extend or scale

---

## 📁 Project Structure

my-docker-web/
│

├── Dockerfile # Defines the custom Nginx image

├── index.html # Simple static webpage

└── README.md # Project documentation

2. **Build the Docker Image**

docker build -t custom-nginx .

3. **Run the Container**

docker run -d -p 8080:80 --name myweb custom-nginx

4. **View the Web Page**
Open your browser and go to:

http://localhost:8080

You should see: "Hello from Docker Web Server!"
