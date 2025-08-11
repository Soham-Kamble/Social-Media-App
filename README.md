📸 Social Media App
A Django-based social media application where users can register, log in, share posts, like, and comment.
The project uses TailwindCSS for styling and provides a clean, responsive interface.

🚀 Features
🔐 User Authentication – Register, login, logout, and password reset.

📝 Post Creation – Upload and share images with captions.

❤️ Like System – Like or unlike posts.

💬 Comment System – Add comments and view others' thoughts.

🎨 TailwindCSS Styling – Modern and responsive design.

📱 Mobile-Friendly UI – Works on all screen sizes.

📂 Project Structure
bash
Copy
Edit
socialproject/
├── posts/                # Post-related views, models, templates
├── users/                # User authentication & profile
├── static/               # CSS, images
├── templates/            # HTML templates
└── manage.py             # Django entry point

🛠️ Installation
1.Clone the repository

bash
Copy
Edit
git clone https://github.com/yourusername/social-media-app.git
cd social-media-app
2.Create a virtual environment

bash
Copy
Edit
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
3.Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
4.Run migrations

bash
Copy
Edit
python manage.py migrate
5.Create a superuser (optional)

bash
Copy
Edit
python manage.py createsuperuser
6.Run the server

bash
Copy
Edit
python manage.py runserver
