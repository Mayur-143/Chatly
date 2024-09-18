# Chatly

**Messaging Service Prototype**  
**Name:** Mayuresh Chimankar  
**Roll No.:** 22075046  
**University:** IIT (BHU), Varanasi  
**Department:** Computer Science and Engineering (B.Tech)

## Setup and Deployment Instructions

### Local Setup

1. **Clone the Repository:**

   ```bash
   git clone <repository-url>
   cd Chatly
   
2. **Install Dependencies:**
   Make sure you have installed the Python virtual environment. Then, run:
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Windows use: venv\Scripts\activate
   pip install -r requirements.txt

3. **Run Migrations:**
   ```bash
   python manage.py migrate
   python manage.py makemigrations
   
4. Run the Server:
   ```bash
   python manage.py runserver
Access the application by visiting http://127.0.0.1:8000 in your browser.

### Project Overview
Chatly is a messaging service prototype with the following features:

- User registration and authentication
- Text messaging
- Group chat functionality
- Real-time messaging
- File sending
- User profile customization

### Technologies Used
- Backend: Django
- Database: dbsqlite3
- Frontend: React.js, CSS, HTML, JavaScript
- Real-time Updates: Django Channels, WebSockets

### Development
For development purposes, ensure that you have all the necessary dependencies installed and that the server runs locally. Follow the local setup instructions to get started.

### Contributing
Feel free to contribute to the project by submitting issues, pull requests, or suggestions.

