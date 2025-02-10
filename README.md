# Social Network Platform

## ًں“Œ Project Overview
This is a **Django-based** social networking platform that allows users to **register, create profiles, post content, chat in real-time, and interact with other users**. It is built using **Django, Django REST Framework, WebSockets, and PostgreSQL**.

## ًںڑ€ Features
- **User Authentication** (Register, Login, Logout)
- **User Profiles** (Edit Profile, Upload Profile Pictures)
- **Post Creation & Interaction** (Likes, Comments)
- **Real-time Chat** (WebSockets-based)
- **RESTful API** (For mobile and frontend integration)
- **Notifications System**
- **Responsive UI** (Built with HTML, CSS, JS)

## ًں› ï¸ڈ Tech Stack
- **Backend:** Django, Django REST Framework, WebSockets  
- **Frontend:** HTML, CSS, JavaScript  
- **Database:** PostgreSQL  
- **Authentication:** JWT (JSON Web Tokens)  
- **Deployment:** Can be hosted on **Heroku, AWS, or DigitalOcean**  

## ًں“‚ Project Structure
```
/social_network/
â”‚â”€â”€ manage.py
â”‚â”€â”€ requirements.txt
â”‚â”€â”€ README.md
â”‚â”€â”€ .env
â”‚â”€â”€ config/              # Project settings
â”‚â”€â”€ users/               # User authentication & profiles
â”‚â”€â”€ posts/               # Post creation & interactions
â”‚â”€â”€ chat/                # Real-time chat feature
â”‚â”€â”€ api/                 # REST API endpoints
â”‚â”€â”€ static/              # Static files (CSS, JS, images)
â”‚â”€â”€ templates/           # HTML templates
â”‚â”€â”€ media/               # User-uploaded files
```

## âڑ، Installation & Setup
1. **Clone the repository**
   ```sh
   git clone https://github.com/yourusername/social-network.git
   cd social-network
   ```
2. **Create a virtual environment**
   ```sh
   python -m venv venv
   source venv/bin/activate   # On Windows use: venv\Scripts\activate
   ```
3. **Install dependencies**
   ```sh
   pip install -r requirements.txt
   ```
4. **Set up environment variables**  
   Create a `.env` file and add your database credentials.
5. **Run migrations**
   ```sh
   python manage.py migrate
   ```
6. **Start the development server**
   ```sh
   python manage.py runserver
   ```

## ًں–¥ï¸ڈ Deployment
- To deploy on **Heroku**, use:
  ```sh
  heroku create your-app-name
  git push heroku main
  heroku run python manage.py migrate
  ```

## ًں“§ Contact
For any inquiries, contact **Ahmed Said Ali** at **ahmed.2021.ali2022@gmail.com**.
