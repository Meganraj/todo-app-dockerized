
# Node.js To-Do List Application

This is a simple **To-Do List Application** built with **Node.js** and Dockerized for easy deployment.

## 🚀 Features
- Add, delete, and update tasks.
- REST API for managing tasks.
- Docker support for containerized deployment.

## 🛠️ Tech Stack
- **Backend:** Node.js, Express.js
- **Containerization:** Docker

---

## 🛆 Installation & Setup

### 1⃣ Clone the Repository
```sh
git clone https://github.com/N4si/learn_docker.git
cd learn_docker
```

### 2⃣ Install Dependencies
```sh
npm install
```

### 3⃣ Run Locally
```sh
npm start
```
By default, the app runs on **port 3000**.

---

## 🐳 Running with Docker

### 1⃣ Build the Docker Image
```sh
docker build -t my_to_do_app .
```

### 2⃣ Run the Container
```sh
docker run -p 3000:3000 my_to_do_app
```

### 3⃣ Stop the Running Container
To stop the running container, first find its ID:
```sh
docker ps
```
Then stop it:
```sh
docker stop <CONTAINER_ID>
```

---

## 👤 Pushing to Docker Hub
### 1⃣ Log in to Docker Hub
```sh
docker login
```

### 2⃣ Tag the Image
```sh
docker tag my_to_do_app megan/my_to_do_app
```

### 3⃣ Push the Image
```sh
docker push your_docker_hub_user_name/my_to_do_app
```
---
## 💡 Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.
---


