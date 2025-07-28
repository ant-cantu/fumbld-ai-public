# <a href="https://fumbldai.com">Fumbld AI</a> (Source Available Upon Request)

<p align="center">
<img src="https://github.com/ant-cantu/fumbld-ai/blob/main/source/static/img/fumbld-small-logo.png?raw=true" width="75%">
</p>

## About Fumbld AI

Fumbld AI is a Flask web application that helps fantasy football managers make informed start/sit decisions. It connects to your Yahoo Fantasy leagues, analyzes your roster with current statistics, and uses OpenAI to provide weekly recommendations.

***

### 💻 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&logoWidth=20)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white&logoWidth=20)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black&logoWidth=20)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white&logoWidth=20)

### 🧩 Frameworks

![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white&logoWidth=20)

### 🔌 APIs

![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white&logoWidth=20)
![Yahoo! Sports](https://img.shields.io/badge/Yahoo!%20Sports-6001D2?style=for-the-badge&logo=yahoo&logoColor=white&logoWidth=20)
![Sleeper](https://img.shields.io/badge/Sleeper%20-%20%23233354?style=for-the-badge&logoWidth=20)


### 📚 Libraries & Extensions

![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-CA1F2C?style=for-the-badge&logo=sqlalchemy&logoColor=white&logoWidth=20)
![WTForms](https://img.shields.io/badge/WTForms-000000?style=for-the-badge&logo=formspree&logoColor=white&logoWidth=20)
![Flask-Login](https://img.shields.io/badge/Flask--Login-000000?style=for-the-badge&logo=flask&logoColor=white&logoWidth=20)
![Werkzeug](https://img.shields.io/badge/Werkzeug-FF6F00?style=for-the-badge)

***

## Features
- User registration and authentication using **Flask-Login**
  - Integrated PostgreSQL as a means to safe user profiles
  - Passwords are never stored as plain text instead they are encrypted and decrypted upon use
 
- Protected routes - making sure use is authorized to access the feature
  - Major API endpoints are protected via Flask-Login, users are required to be logged in before an endpoint can be used
  
- Yahoo Fantasy Sports integration with OAuth2
   - Users are able to authorize their Yahoo! Sports account to automatically bring league data into Fumbld AI
     
- Sleeper integration via Sleeper API, using a Sleeper username
   - Sleeper API does not require authentication as it is a read-only API. Users are able to import league data by simply entering their username
     
- Fumbld AI insights powered by **Gemini**
   - Roster data is extracted from Yahoo! Sports or Sleeper and processed through the Gemini API using prompt engineering to generate start/sit recommendations
   - Recommendation is shown to the user in a user-friendly formatted table along with the reason as to why Gemini made those recommendations
     
- Dashboard to view your currently set roster and the NFL schedule for the week
  - Main dashboard module will allow you to select which service (Yahoo! or Sleeper) and the league you want to view/process AI functions with
    
- Google reCAPTCHA for form protection
  - Google reCAPTCHA form used for protecting registration and login abuse
    
- Flask-limiter for rate limiting
   - Protects the login form from brute force attacks
   - Protects our external API endpoints from being abused
   - Protects our internal API endpoints from being abused

## Source Code:
> To protect the source code, it is available upon request to prospective employers only.

## Preview

### Desktop Preview
<img width="1536" height="1024" alt="desktop-fumbld-ai" src="https://github.com/user-attachments/assets/6b1a4bd5-89fc-4297-be5f-836691855368" />

### Mobile Preview
<img width="1536" height="1024" alt="mobile-fumbld-ai" src="https://github.com/user-attachments/assets/4cee8488-ed91-4de3-817d-69c15f7a83e7" />

### Home Page
![image](https://github.com/user-attachments/assets/e3a126f3-9d89-4da2-95b5-ed2179e4b9ae)

### Login Page
![image](https://github.com/user-attachments/assets/9e282bae-6146-4fff-8f7f-c0778382ae8c)

### Registration Page
![image](https://github.com/user-attachments/assets/fb784bfa-e0ad-4c4a-99fc-9e975e2d197d)

### Dashboard - Main
![image](https://github.com/user-attachments/assets/40581aaf-c6cc-4583-a692-413b6e70fd3f)

### Dashboard - Fumbld AI
![image](https://github.com/user-attachments/assets/3c046e16-4996-4c1c-bf29-8fff21569b11)

### Dashboard - Settings (Work In Progress)
![image](https://github.com/user-attachments/assets/7454ecff-2be9-46fb-9d0a-8c75fc13206f)


