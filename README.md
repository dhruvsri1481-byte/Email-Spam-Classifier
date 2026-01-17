Spam Mail Classification

Description  
The Spam Mail Classification project is a web-based application that uses machine learning to classify emails as spam or ham. It features a Flask backend, a frontend created with HTML, CSS, and JavaScript, and a MySQL database for storing user data and email classifications.

---

Features  
Email Classification: Categorizes incoming emails as spam or ham.  
User Registration and Login: Secure account creation and authentication.  
Real-Time Email Classification: Classifies emails in real time.  
User Dashboard: Users can view their email history and classifications.  
Machine Learning Model: Employs a trained model to classify emails.  
Customization: Users can configure spam filter settings.

---

Technologies Used  
Flask (Python Web Framework): For the backend server.  
HTML, CSS, and JavaScript (Frontend): For the user interface.  
MySQL (Database): For storing user data and email classifications.  
Machine Learning Libraries (e.g., Scikit-Learn): Used to build and deploy the email classification model.

---

Getting Started  

To use the Spam Mail Classification app, follow these steps:

Clone this Repository:
```bash
git clone https://github.com/dhruvsri1481-byte/Email-Spam-Classifier.git
cd Email-Spam-Classifier

Install Required Python Packages:
pip install Flask
pip install nltk
pip install mysql-connector-python

Create a MySQL Database and Table:
CREATE DATABASE smc;
USE smc;
CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    full_name VARCHAR(255) NOT NULL,
    username VARCHAR(255) UNIQUE NOT NULL,
    email VARCHAR(255) UNIQUE NOT NULL,
    phone VARCHAR(15) NOT NULL,
    password VARCHAR(255) NOT NULL
);

Run the Flask App:
python app.py

Goto browser to open this website in Localhost:
http://127.0.0.1:5000/


