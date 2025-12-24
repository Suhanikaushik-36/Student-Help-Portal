# 🎓 Student Help Desk Portal

A web-based **Student Help Desk Portal** designed to simplify communication between students and the administration. This platform allows students to raise queries, track their status, and get timely responses, while admins can efficiently manage and resolve issues.

---

## 🚀 Features

### 👩‍🎓 Student Side

* Register & Login securely
* Raise queries / complaints
* Track query status (Pending / Resolved)
* View responses from admin

### 🧑‍💼 Admin Side

* Admin authentication
* View all student queries
* Respond to and resolve issues
* Manage query status

---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** Python (Flask)
* **Database:** SQLite / MySQL (as configured)
* **APIs & Integrations:** External APIs using **API Keys** (secured via environment variables)
* **Version Control:** Git & GitHub

---

## 📁 Project Structure

```
student-help-desk-portal/
│── static/
│   ├── css/
│   ├── js/
│   └── images/
│── templates/
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   └── admin.html
│── app.py
│── database.db
│── README.md
```

---

## ⚙️ Installation & Setup

1. **Clone the repository**

```bash
git clone https://github.com/suhanikaushik-36/student-help-desk-portal.git
```

2. **Navigate to project folder**

```bash
cd student-help-desk-portal
```

3. **Install dependencies**

```bash
pip install flask
```

4. **Configure API Keys**

This project uses external APIs that require an **API Key**.

* Create a `.env` file in the root directory
* Add your API key as shown below:

```env
API_KEY=your_api_key_here
```

⚠️ **Important:** Never push your actual API keys to GitHub. Make sure `.env` is added to `.gitignore`.

5. **Run the application**

```bash
python app.py
```

6. Open browser and go to:

```
http://127.0.0.1:5000/
```

---

## 🎯 Use Case

This project can be used in:

* Colleges & Universities
* Schools
* Training Institutes

To improve student–administration communication and issue resolution.

---

## 📌 Future Enhancements

* Email notifications
* Role-based authentication
* File upload support
* Improved UI/UX
* Deployment on cloud

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## ✨ Author

**Suhani Kaushik**
B.Tech CSE | Full Stack & AI Enthusiast

---

⭐ If you like this project, don’t forget to star the repository!

