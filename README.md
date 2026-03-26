# 🎨 CodePixel Arena

**CodePixel Arena** is a collaborative web platform where users interact through programming challenges to claim and control pixels on a shared digital canvas.

The project combines competitive programming, real-time interaction, and gamification into a single system. Users create coding challenges, submit solutions, and gain ownership of pixels by successfully solving problems. The platform tracks user performance, manages challenge validation, and updates the shared canvas in real time.

---

## 🚀 Features

* **Interactive Pixel Canvas**
  A shared grid where each pixel is linked to a programming challenge and owned by users.

* **Coding Challenges & Submissions**
  Users can create problems and submit solutions through an in-browser editor.

* **Automated Evaluation**
  Solutions are validated against test cases to determine correctness.

* **Real-Time Updates**
  Pixel ownership and canvas changes are synchronized instantly across users.

* **User Progress Tracking**
  Track solved challenges, submission history, and performance metrics.

* **Leaderboard System**
  Rank users based on activity, accuracy, and achievements.

---

## 🏗️ Tech Stack

**Frontend**

* React.js
* TypeScript
* Canvas libraries (e.g., Fabric.js)
* Monaco Editor

**Backend**

* C# ASP.NET Core
* SignalR (real-time communication)

**Database**

* SQL-based relational database (users, challenges, submissions, pixels)

**DevOps & Tools**

* Docker (for code execution sandbox)
* GitHub Actions (CI/CD)
* Cloud deployment (e.g., Azure)

---

## 🧠 Core Concept

Each pixel on the canvas is associated with a coding challenge.

* A user must solve the challenge to gain control of the pixel
* Submissions are automatically evaluated using predefined test cases
* Ownership can change based on successful solutions
* All actions are stored and managed through the database system

---

## 📊 Project Structure (High-Level)

* **Frontend**: UI, canvas rendering, code editor
* **Backend**: APIs, real-time updates, submission handling
* **Database**: Data storage, relationships, and query logic
* **Execution Engine**: Secure evaluation of user code

---

## 🎯 Goals

* Build a full-stack, real-time collaborative system
* Apply database design and optimization techniques
* Integrate algorithmic problem-solving into an interactive platform
* Demonstrate scalable and modular system architecture

---

## ⚙️ Status

🚧 Initial version in development

---

## 📌 Future Improvements

* Advanced challenge categories (graphs, trees, algorithms)
* Team-based collaboration
* Enhanced analytics and visualization
* Improved sandboxing and security
