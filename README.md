Websockets & Socket.IO - Full Stack Realtime App
    This project demonstrates a full-stack real-time communication application built with Node.js, Express, React, and Socket.IO. It includes authentication, post feeds, image      uploads, and a robust architecture suitable for scalable production systems.

🔗 Repository
    GitHub: https://github.com/ajayvishwakarma457/websockets_and_socket.io

📁 Project Structure
      websockets_and_socket.io/
                              ├── backend/
                              │   ├── controllers/          # Auth & Feed logic
                              │   ├── images/               # Uploaded files
                              │   ├── middleware/           # is-auth for JWT validation
                              │   ├── models/               # Mongoose models (User, Post)
                              │   ├── routes/               # Express routing
                              │   ├── socket.js             # Core socket.io setup
                              │   ├── app.js                # Express app setup
                              │   ├── package.json
                              │   └── .gitignore
                              │
                              ├── frontend/
                              │   ├── public/               # HTML, favicon, manifest
                              │   ├── src/
                              │   │   ├── components/       # Modular UI components
                              │   │   ├── pages/            # Auth & Feed views
                              │   │   ├── util/             # Helpers, validators
                              │   │   ├── App.js            # Main app logic
                              │   │   ├── index.js
                              │   │   └── styles
                              │   ├── package.json
                              │   └── .gitignore
                              │
                              ├── docker-compose.yml        # Optional: orchestrate full stack
                              └── README.md


🚀 Features
  💬 Real-time communication using Socket.IO
  🔐 Secure authentication using JWT
  🖼️ Image upload with preview
  🧠 Modular MVC-based backend structure
  🧩 Modern React frontend using reusable components
  📦 Docker setup for full-stack orchestration (optional)


🛠️ Technologies Used
  Backend
    Node.js
    Express.js
    MongoDB + Mongoose
    Socket.IO
    JSON Web Tokens
    Multer (for file uploads)

  Frontend
    React.js (functional components)
    React Router
    Axios
    Socket.IO-client

🧪 How to Run
  Backend
    cd backend
      npm install
      npm start
        Make sure MongoDB is running locally or provide a MongoDB Atlas URI in a .env file.

  Frontend
    cd frontend
    npm install
    npm start
      Frontend runs on http://localhost:3000, backend typically on http://localhost:8080.

## 📬 Contact
  **Author:** Ajay M Vishwakarma  
  **Email:** ajayvishwakarma457@gmail.com

📄 License
  This repository is licensed under the MIT License.
  See the LICENSE file for details.


