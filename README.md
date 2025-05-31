# 🐳 Docker Get Started Workshop

This project is based on the official [Docker Get Started Workshop](https://docs.docker.com/get-started/workshop/). It walks through how to containerize a simple Node.js application and progressively improve the Docker setup through multiple stages.

## 📚 Workshop Sections

This implementation includes all 8 parts of the Docker workshop:

1. Containerize the application  
2. Update the application  
3. Share the image on Docker Hub  
4. Persist the database using volumes  
5. Bind mounts for live development  
6. Multi-container setup with MySQL  
7. Use Docker Compose  
8. Image building best practices

## 🚀 Running the Application

To run the application locally using Docker:

```bash
docker-compose up --build
```

You can access the application in your browser at:

```
http://localhost:3000
```

## 🛠 Tech Stack

- Node.js
- Express
- SQLite / MySQL
- Docker
- Docker Compose

## 📁 Project Structure

```
docker-workshop-main/
├── src/
├── spec/
├── .dockerignore
├── docker-compose.yml
├── Dockerfile
└── README.md
```

## 📄 License

This project is provided for educational purposes and follows the structure of the official Docker documentation.
