<div align="center">

# SkillXchange

### Learn something new. Share what you know.

An online learning-exchange platform where learners and instructors can discover courses, share skills, and connect.

<p>
  <a href="https://krishthakur248.github.io/SkillXChange/SkillXchange">✨ Open the Live Demo</a>
</p>

<p>
  <img src="https://img.shields.io/badge/Frontend-HTML%20%7C%20CSS%20%7C%20JavaScript-159952?style=for-the-badge" alt="Frontend: HTML, CSS, and JavaScript">
  <img src="https://img.shields.io/badge/Backend-Node.js%20%7C%20Express-43853d?style=for-the-badge" alt="Backend: Node.js and Express">
  <img src="https://img.shields.io/badge/Database-MongoDB-47A248?style=for-the-badge" alt="Database: MongoDB">
</p>

</div>

---

## 🌱 About

**SkillXchange** brings people together to teach and learn. Browse skill-based courses, publish courses of your own, and connect with other learners through course chat.

The project includes a multi-page web interface and an Express API backed by MongoDB. The live demo is hosted on GitHub Pages.

## ✨ Features

- **Explore courses** across areas such as engineering, medicine, commerce, and arts.
- **Teach a skill** by creating and managing courses.
- **Join courses** and keep track of your enrollments.
- **Chat with course members** using real-time WebSocket messaging.
- **Create an account and sign in** to access account-based features.
- **Meet online** through the Jitsi Meet integration in `index.html`.
- **Learn how it works** and browse the project’s informational pages.

## 🚀 Live Demo

Visit **[SkillXchange Live Demo](https://krishthakur248.github.io/SkillXChange/SkillXchange)** to explore the site.

> The deployed frontend is hosted on GitHub Pages. Features that need the API or database depend on the backend being available.

## 🧰 Built With

| Part | Technologies |
| --- | --- |
| Frontend | HTML, CSS, JavaScript |
| Backend | Node.js, Express |
| Database | MongoDB with Mongoose |
| Authentication | JSON Web Tokens (JWT), bcryptjs |
| Live course chat | WebSockets (`ws`) |
| Video meetings | Jitsi Meet External API |
| Static hosting | GitHub Pages |

## 📁 Project Pages

| File | Purpose |
| --- | --- |
| `SkillXchange.html` | SkillXchange introduction and landing page |
| `bypass.html` | Course discovery and signed-in home |
| `view-courses.html` | Browse and enroll in courses |
| `TeachingPeer.html` | Create and manage teaching courses |
| `YourCourses.html` | View courses you teach |
| `YourWnrollment.html` | View your enrolled courses |
| `chat.html` | Course member chat |
| `howitwork.html` | Platform guide |
| `server.js` | Express API and WebSocket server |

## 💻 Run Locally

### Frontend

1. Clone this repository:

   ```bash
   git clone https://github.com/krishthakur248/SkillXChange.git
   cd SkillXChange
   ```

2. Open `SkillXchange.html` in a browser, or serve the project folder with a local static web server such as the VS Code **Live Server** extension.

### Backend

The backend requires Node.js, npm, and a MongoDB database.

1. Install the dependencies:

   ```bash
   npm install
   ```

2. Before starting the server, configure a valid MongoDB connection URI and a secure JWT secret for your environment. Do not commit credentials or production secrets.

3. Start the API:

   ```bash
   npm start
   ```

The server listens on port `5000` by default and uses the `PORT` environment variable when one is set.

> **Configuration note:** The database connection and JWT secret in `server.js` need to be configured for your own environment before running or deploying the backend. The frontend’s API requests also need to point to the backend you intend to use.

## 🤝 Contributing

Suggestions and improvements are welcome. Fork the repository, create a branch for your change, and open a pull request with a clear summary.

## 📄 License

No license is currently specified in this repository. Please contact the project owner before reusing or redistributing the project.

---

<div align="center">

Made with 💚 for curious learners and generous teachers.

</div>
