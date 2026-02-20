# HeartDiseaseAnalysis

❤️ Heart Disease Analysis Web Application

Live Demo Link:https://drive.google.com/file/d/1Jmy9wEahy6izfsgh3LcHUCJCit4lQzZy/view?usp=drive_link

📌 Abstract

Heart disease is one of the leading causes of health complications worldwide. Early detection and risk assessment play a vital role in prevention and timely treatment.

The Heart Disease Analysis Web Application is a Flask-based web system developed to analyze basic cardiovascular health parameters and estimate a user's heart disease risk level. The application includes user authentication, a heart-themed user interface, and a rule-based risk evaluation mechanism.

This project is developed for academic and learning purposes and demonstrates full-stack web development using Python and Flask.

📖 Introduction

The increasing prevalence of heart-related illnesses has created a need for simple and accessible health assessment tools. This web application allows users to input essential health parameters and instantly receive an estimated risk level.

The system uses predefined medical thresholds to calculate a risk score and categorize users into:

<Low Risk

=Medium Risk

>High Risk

The application includes login and sign-up functionality to provide controlled access to the analysis module.

🎯 Objectives

Design a simple and user-friendly heart disease analysis system

Implement user login and registration functionality

Collect basic heart health parameters from users

Calculate heart disease risk using rule-based logic

Display results in a clear and visually appealing format

📌 Scope of the Project

This project is suitable for:

Academic demonstrations

Mini project submissions

Learning Flask web development

⚠️ It does not replace professional medical diagnosis and is not intended for real-world clinical use.

🏗️ System Architecture

The application follows the Model–View–Controller (MVC) architecture pattern:

Model → Risk calculation logic

View → HTML templates

Controller → Flask routes in app.py

The system follows a client–server architecture where:

Frontend → Built using HTML5 and CSS3

Backend → Developed using Python Flask

Static assets → Managed using Flask’s static folder

💻 Technologies Used

Python 3

Flask

HTML5

CSS3

Static Image Assets

📁 Project Structure
HeartDiseaseAnalysis/
│
├── app.py
├── templates/
│   ├── login.html
│   ├── signup.html
│   ├── index.html
│   └── result.html
│
├── static/
│   └── heart.jpg
│
├── requirements.txt
└── README.md

🔐 Functional Description
1️⃣ User Authentication

Users can register using email and password

Registered users can log in

User data is stored temporarily in memory

2️⃣ Heart Disease Analysis

Users enter the following parameters:

Age

Blood Pressure

Cholesterol

Heart Rate

Oldpeak value

The system evaluates each parameter against predefined thresholds and calculates a cumulative risk score.

3️⃣ Result Generation

Based on the total score, the system classifies the user into:

Low Risk

Medium Risk

High Risk

The result is displayed clearly on the result page.

📊 Risk Calculation Logic
Parameter	Condition	Score
Age	> 50	+10
Blood Pressure	> 130	+10
Cholesterol	> 200	+10
Heart Rate	< 140	+5
Oldpeak	> 2	+10
🏷️ Risk Classification

Score ≤ 20 → Low Risk

Score 21–40 → Medium Risk

Score > 40 → High Risk

🎨 User Interface Design

Heart-themed static background image

Semi-transparent content boxes

Clean and simple layout

Medical-themed color scheme

⚙️ Installation and Execution
Step 1: Install Python

Download and install Python (version 3.7 or above).

Step 2: Install Required Packages
pip install flask


Or using requirements file:

pip install -r requirements.txt

Step 3: Run the Application
python app.py

Step 4: Open in Browser
http://127.0.0.1:5000/

🧪 Sample Test Case

Input:

Age: 55

Blood Pressure: 140

Cholesterol: 230

Heart Rate: 120

Oldpeak: 2.5

Output:

Risk Score: 45

Risk Level: High

⚠️ Limitations

No database integration

Passwords stored in plain text

Uses rule-based logic instead of machine learning

Not suitable for real medical diagnosis

🚀 Future Enhancements

Database integration (MySQL / SQLite)

Secure password hashing

Machine learning-based prediction

Improved UI using Bootstrap

Graphical data visualization

🎓 Applications

Academic mini project

Flask learning project

Health analytics demonstration

College project submission

🏁 Conclusion

The Heart Disease Analysis Web Application demonstrates a practical implementation of web development concepts using Python Flask. It integrates user authentication, risk assessment logic, and frontend design into a complete working system.

This project provides a strong foundation for future enhancements such as machine learning integration, database connectivity, and secure authentication mechanisms.

⚠️ Disclaimer

This application is developed strictly for educational purposes. It does not provide medical advice and should not be used as a substitute for professional healthcare diagnosis.

👩‍💻 Author

Developed as part of an academic project by Shaik Saad Ahamed.

❤️ “Your heart matters – take care of it.”
