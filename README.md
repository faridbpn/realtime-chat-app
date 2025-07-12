# 💬 Real-Time Chat App

This is a real-time chat application built using **Node.js**, **Socket.IO**, and **PostgreSQL**. The project is fully containerized using **Docker** and deployed through **GitLab CI/CD pipelines**.

---

## 🚀 Features

- ✅ Real-time messaging using Socket.IO  
- ✅ Simple and clean frontend using plain HTML & JS  
- ✅ Express.js backend server  
- ✅ Containerized with Docker & Docker Compose  
- ✅ CI/CD integration via GitLab pipelines  
- ✅ Ready for deployment to any cloud server  

---

## 🛠 Tech Stack

| Layer       | Technology           |
|-------------|----------------------|
| Frontend    | HTML, JavaScript     |
| Backend     | Node.js, Express.js  |
| Real-time   | Socket.IO            |
| Database    | PostgreSQL (ready for future integration) |
| DevOps      | Docker, Docker Compose |
| CI/CD       | GitLab Pipelines     |

---

## 📂 Project Structure

```
realtime-chat/
├── Dockerfile
├── docker-compose.yml
├── server.js
├── package.json
├── .gitlab-ci.yml
└── public/
    └── index.html
```

---

## ⚙️ Setup & Run (Development)

1. Clone this repo:
   ```bash
   git clone https://github.com/faridbpn/realtime-chat.git
   cd realtime-chat
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the server:
   ```bash
   node server.js
   ```

4. Open browser at [http://localhost:3000](http://localhost:3000)

---

## 🐳 Run with Docker

```bash
docker-compose up --build
```

---

## 🔁 CI/CD with GitLab

Every push to the GitLab repository will automatically:
- 🔨 Build the Docker image
- 🚀 Deploy the app using `docker-compose`

Configured in `.gitlab-ci.yml`

---

## 🧪 To Do / Next Steps

- [ ] Add chat rooms & usernames  
- [ ] Integrate PostgreSQL for chat persistence  
- [ ] Improve UI/UX  
- [ ] Add authentication system  
- [ ] Deploy to public cloud (Render/Fly.io/VPS)

---

## 📄 License

MIT License © 2025 [Farid BPN](https://github.com/faridbpn)
