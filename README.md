# 📸 Social Media App

A simple **social media platform** built with **Django**, where users can register, log in, post photos, like posts, and comment on others' content.  
Designed with a clean, responsive UI using Tailwind CSS.

---

## ✨ Features
- 👤 **User Authentication** (Register, Login, Logout, Password Reset)
- 🖼 **Post Creation** (Upload and share photos)
- ❤️ **Like System** (Toggle likes on posts)
- 💬 **Comment System** (Comment on any post)
- 📱 **Responsive UI** (Tailwind CSS for modern styling)

---

## 🚀 Installation

```bash
# 1️⃣ Clone the repository
git clone https://github.com/Soham-Kamble/Social-Media-App
cd social-media-app

# 2️⃣ Create a virtual environment
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# 3️⃣ Install dependencies
pip install -r requirements.txt

# 4️⃣ Apply database migrations
python manage.py migrate

# 5️⃣ (Optional) Create a superuser
python manage.py createsuperuser

# 6️⃣ Start the development server
python manage.py runserver
```

---

## 📂 Project Structure
```
social-media-app/
│
├── posts/              # App for posts, likes, comments
├── users/              # App for authentication & profiles
├── socialproject/      # Main project settings
├── templates/          # HTML templates
├── static/             # CSS, images, JavaScript
└── manage.py
```

---

## ⚙️ Tech Stack
- **Backend**: Django
- **Frontend**: Tailwind CSS
- **Database**: SQLite (default, can be changed)
- **Auth**: Django's built-in authentication system

---

## 📸 Screenshots
C:\Users\HP\OneDrive\Desktop\SOHAM\Django\Social Media App\env\Scripts\socialproject\images\homepage.png

---

## 🛡 License
This project is licensed under the **MIT License**.
