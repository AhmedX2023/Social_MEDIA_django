# Social Network Platform

## 📌 Project Overview
This is a **Django-based** social networking platform that allows users to **register, create profiles, post content, chat in real-time, and interact with other users**. It is built using **Django, Django REST Framework, WebSockets, and PostgreSQL**.

## 🚀 Features
- **User Authentication** (Register, Login, Logout)
- **User Profiles** (Edit Profile, Upload Profile Pictures)
- **Post Creation & Interaction** (Likes, Comments)
- **Real-time Chat** (WebSockets-based)
- **RESTful API** (For mobile and frontend integration)
- **Notifications System**
- **Responsive UI** (Built with HTML, CSS, JS)

## 🛠️ Tech Stack
- **Backend:** Django, Django REST Framework, WebSockets  
- **Frontend:** HTML, CSS, JavaScript  
- **Database:** PostgreSQL  
- **Authentication:** JWT (JSON Web Tokens)  
- **Deployment:** Can be hosted on **Heroku, AWS, or DigitalOcean**  

## 📂 Project Structure

/social_network/ │── manage.py │── requirements.txt │── README.md │── .env │── config/              # Project settings │── users/               # User authentication & profiles │── posts/               # Post creation & interactions │── chat/                # Real-time chat feature │── api/                 # REST API endpoints │── static/              # Static files (CSS, JS, images) │── templates/           # HTML templates │── media/               # User-uploaded files

## ⚡ Installation & Setup
1. **Clone the repository**
   ```sh
   git clone https://github.com/yourusername/social-network.git
   cd social-network

2. Create a virtual environment

python -m venv venv
source venv/bin/activate   # On Windows use: venv\Scripts\activate


3. Install dependencies

pip install -r requirements.txt


4. Set up environment variables
Create a .env file and add your database credentials.


5. Run migrations

python manage.py migrate


6. Start the development server

python manage.py runserver



🖥️ Deployment

To deploy on Heroku, use:

heroku create your-app-name
git push heroku main
heroku run python manage.py migrate


📧 Contact

For any inquiries, contact Ahmed Said Ali at ahmed.2021.ali2022@gmail.com

