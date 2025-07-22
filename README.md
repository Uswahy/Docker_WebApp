🚀 Dockerized Node.js Web App

This is a simple Node.js web application containerized using Docker and orchestrated with Docker Compose. 
It serves a basic "Hello World" message on Browser.

---

📂 Project Structure

node-docker-app/

├── app.js

├── package.json

├── Dockerfile

├── docker-compose.yml

└── .dockerignore

Before running this project, ensure you have:

- ✅ [Docker Desktop](https://www.docker.com/products/docker-desktop) installed and running
- ✅ Node.js installed (optional, only if testing outside Docker)
- ✅ Git (to clone the repository)

📥 Installation Steps

1. Clone the Repository
    
git clone https://github.com/your-username/node-docker-app.git

🚀 Running the App with Docker Compose

2. Bash: 

cd node-dockerApp

docker-compose up --build

3. Access the App in Browser:
   
   http://localhost:3000
