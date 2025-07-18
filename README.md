# 📚 EdTech Assignment Tracker

An intuitive FastAPI-powered backend for managing users and assignments in an EdTech platform. Built as part of the internship task for Eskillite Tech Serv.

---

## 🚀 Features

- 🔐 **User Authentication** – Register and login functionality
- 📋 **Assignment Management** – Create and retrieve assignments
- ⚡ **FastAPI** – Modern, fast web framework
- 🛡️ **Session Middleware** – Secure session handling

---

## 🛠️ Technologies Used

- 🐍 Python 3.10+
- ⚡ FastAPI
- 🧵 Starlette Sessions
- 🔄 Routers for modular code structure

---

## 📁 Project Structure

```bash
.
├── main.py               # Entry point of the application
├── routers/
│   ├── user.py           # Handles user-related routes
│   └── assignment.py     # Handles assignment-related routes
├── README.md             # You're reading it 👀
🔧 Setup Instructions
🔽 Clone the repo:

bash
Copy
Edit
git clone https://github.com/your-username/edtech-assignment-tracker.git
cd edtech-assignment-tracker
📦 Create and activate a virtual environment:

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
📥 Install dependencies:

bash
Copy
Edit
pip install fastapi uvicorn
▶️ Run the server:

bash
Copy
Edit
uvicorn main:app --reload
🌐 Visit: http://127.0.0.1:8000/docs to explore Swagger UI

👩‍💻 Author
Varshana A J
💼 Aspiring Web Developer | FastAPI Enthusiast
📧 varshanaaj@gmail.com
