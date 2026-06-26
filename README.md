# Taskflow

Taskflow is a scalable task management application built with Django, featuring a heavily customized authentication architecture engineered for precise data flow control.

## 🚀 Architecture & Features

- **Custom Authentication Engine:** Bypasses standard Django magic in favor of a raw database backend, providing absolute manual control over cryptographic hashing and user session management.
- **Extended User Schema:** Utilizes a custom `UserProfile` architecture to safely store extended data (like contact numbers) alongside standard authentication credentials.
- **Secure Cryptography:** Implements secure `pbkdf2_sha256` single-pass password hashing.
- **App Modularity:** Clean separation of concerns between `authApp` (handling all security and user sessions) and `taskApp` (handling core business logic).
- **Frontend Integration:** Clean, responsive UI built with Bootstrap 5.

## 🛠️ Tech Stack

- **Backend:** Python, Django
- **Database:** SQLite (Development)
- **Frontend:** HTML5, Bootstrap 5 

## ⚙️ Installation & Setup (Linux/Workstation)

Follow these steps to get the development environment running on your workstation.

**1. Clone the repository**
```bash
git clone [https://github.com/yourusername/taskflow.git](https://github.com/yourusername/taskflow.git)
cd taskflow
