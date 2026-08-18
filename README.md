# AI-Assisted Full-Stack Development Capstone

A modern full-stack web application developed as an AI-assisted capstone project. Built using a robust MERN-style architecture with **React + Vite** on the frontend, **Node.js + Express** on the backend, and **MongoDB** for database storage.

---

## 🚀 Features

- **Frontend Application**: Responsive, high-performance user interface built with React and Vite.
- **Backend API**: Scalable RESTful web services powered by Node.js and Express.
- **Database Integration**: Persistent document storage using MongoDB.
- **AI-Assisted Workflows**: Designed and developed with structured AI pair-programming and modern engineering standards.

---

## 🛠️ Tech Stack

- **Frontend**: React, Vite, HTML5, CSS3, JavaScript (ES6+)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Package Manager**: `npm`
- **Version Control**: Git & GitHub

---

## 📁 Project Structure

```text
ai-dev-capstone/
├── client/          # React + Vite frontend application
├── server/          # Node.js + Express backend service
├── AGENTS.md        # Project guidelines & AI agent instructions
├── README.md        # Project documentation
└── .gitignore       # Git ignore specifications
```

---

## 🏁 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18+ recommended)
- [npm](https://www.npmjs.com/)
- [MongoDB](https://www.mongodb.com/) (Local instance or MongoDB Atlas connection string)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/ai-dev-capstone.git
   cd ai-dev-capstone
   ```

2. **Install Backend Dependencies:**
   ```bash
   cd server
   npm install
   ```

3. **Install Frontend Dependencies:**
   ```bash
   cd ../client
   npm install
   ```

4. **Environment Setup:**
   Create a `.env` file in the `server` directory with your database URI and server port:
   ```env
   PORT=5000
   MONGO_URI=mongodb://localhost:27017/ai-dev-capstone
   ```

### Running the Application

- **Start the Backend Server:**
  ```bash
  cd server
  npm start
  ```

- **Start the Frontend Client:**
  ```bash
  cd client
  npm run dev
  ```

---

## 📜 Development Guidelines & Conventions

- Follow **Conventional Commits 1.0.0** specifications (`feat:`, `fix:`, `docs:`, `chore:`).
- Code style: ES6+ syntax, 2-space indentation, no semicolons.
- For detailed AI guidelines and coding standards, refer to [`AGENTS.md`](./AGENTS.md).

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
