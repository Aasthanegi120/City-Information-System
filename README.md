# 🏙️ City Info System

A web-based information platform that provides categorized and verified data about essential public services like hospitals, schools, colleges, hotels, malls, and theatres within a city. Built using Flask and Bootstrap 5, it supports secure admin management and user-friendly search functionality.

---

## ✨ Features

- 🔍 Search city services by name, address, or classification
- 🧭 User-friendly UI with clean navigation
- 🔐 Secure login system for users and admins
- 🛠️ Admin panel to add, update, or delete services
- 🏥 Categories: Hospitals, Hotels, Schools, Colleges, Malls, Theatres
- 📱 Mobile-responsive design using Bootstrap 5
- 💾 MySQL backend with session management and password hashing

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, Bootstrap 5, JavaScript
- **Backend:** Python (Flask)
- **Database:** MySQL
- **Session Management:** Flask-Session
- **Security:** Werkzeug for password hashing

---

## 📸 Screenshots

> ![image alt](https://github.com/Aasthanegi120/City-Information-System/blob/main/image-1.png?raw=true)
- Home Page  
- Login / Register  
- Admin Dashboard  
- View & Manage Hospitals, Schools, etc.  

---

1. **Clone the repository**
```bash
git clone https://github.com/Aasthanegi120/City-Information-System
cd city-info-system
```

2. **Set up virtual environment (optional)**
```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
```

3. **Install dependencies manually**
```bash
pip install flask flask-mysqldb flask-bcrypt flask-session mysql-connector-python
```


4. **Run the app**
```bash
python app.py
```

---

## 📦 Project Structure

```
.
├── static/              # CSS, JS, assets
├── templates/           # HTML pages
├── app.py               # Main application
├── README.md
└── ...other files
```

---

## 🙌 Author

- Aastha Negi   naastha4@gmail.com

---

## 📄 License

This project is for academic and educational use only.  
© 2024 Shri Vaishnav Vidyapeeth Vishwavidyalaya, Indore

---
