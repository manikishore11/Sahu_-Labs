Student Academic Analysis System
Data Analysis • Flask Dashboard • Student Performance Insights • Android

A complete academic analytics project for exploring student performance data through Python, Flask, responsive web pages, and an Android WebView application.

Designed and Developed by Sahu Tech

Overview
The Student Academic Analysis System is a data analysis project designed to study student academic performance using a structured dataset.

The system processes student records, prepares cleaned data, generates academic insights, and presents the results through a responsive Flask web application. An Android WebView application is also included for mobile access.

Core Capabilities
Student dataset loading
Data cleaning and preprocessing
Academic performance analysis
Student-wise record viewing
Processed dataset generation
Responsive dashboard
Analysis page
Searchable student records
Individual student details
Android WebView application
System Architecture
Student Dataset
      ↓
Python Data Analysis
      ↓
Processed Student Dataset
      ↓
Flask Backend
      ↓
Responsive Web Dashboard
      ↓
Android WebView Application
Technology Stack
Data Analysis
Python
Pandas
Backend
Flask
Frontend
HTML5
CSS3
JavaScript
Android
Kotlin
Android Studio
Android WebView
Development Tools
Visual Studio Code
Android Studio
Git
GitHub
Dataset
The project uses student academic data stored in:

student.csv
After analysis and preprocessing, the processed data is stored in:

processed_students.csv
The processed dataset is used by the Flask application to display academic information and student records.

Data Analysis
The analysis.py file handles the core student-data processing workflow.

Typical operations include:

Loading the student dataset
Inspecting the available records
Cleaning the data
Processing academic fields
Preparing student performance information
Generating useful analysis
Saving the final processed dataset
The output is saved as:

processed_students.csv
Web Application
The Flask application is implemented in:

app.py
It provides multiple pages for exploring student academic information.

Dashboard
The dashboard provides a high-level overview of the student dataset and academic performance.

Students
The students page displays student records in an organized format.

Student Details
The student-details page provides information about an individual student.

Analysis
The analysis page presents academic insights generated from the processed student data.

Frontend Structure
The interface is built using reusable HTML templates and a shared stylesheet.

Templates
templates/
├── analysis.html
├── dashboard.html
├── students.html
└── students_details.html
Styling
static/
└── style.css
The interface is designed to remain usable across desktop and mobile screen sizes.

Android Application
The project includes an Android application inside:

Android App/
The Android application is developed using:

Kotlin
Android Studio
WebView
The application loads the Flask web interface inside a native Android application.

Local Testing
When using the Flask development server locally, the Android device and computer should normally be connected to the same network.

The Android app can then connect to the computer using its local network IP address.

Example:

http://192.168.x.x:5000
Important APK Note
The Android application currently depends on the Flask backend being reachable.

Installing the APK alone does not make the complete system standalone.

For public deployment, the Flask backend can be hosted online and the Android WebView URL can be updated to the deployed HTTPS address.

Project Structure
Student-Academic-Analysis-System/
│
├── analysis.py
├── app.py
├── student.csv
├── processed_students.csv
├── requirements.txt
├── README.md
├── .gitignore
│
├── static/
│   └── style.css
│
├── templates/
│   ├── analysis.html
│   ├── dashboard.html
│   ├── students.html
│   └── students_details.html
│
└── Android App/
    ├── app/
    ├── gradle/
    ├── build.gradle.kts
    ├── gradle.properties
    ├── gradlew
    ├── gradlew.bat
    └── settings.gradle.kts
Installation
1. Clone the Repository
git clone https://github.com/TECHIEVK007/Student-Academic-Analysis-System.git
cd Student-Academic-Analysis-System
2. Install Python Dependencies
pip install -r requirements.txt
3. Run the Data Analysis
python analysis.py
This prepares or updates:

processed_students.csv
4. Start the Flask Application
python app.py
The web application will normally be available at:

http://127.0.0.1:5000
For access from another device on the same local network:

http://YOUR_LOCAL_IP:5000
Android Setup
Open the Android App/ folder in Android Studio.
Allow Gradle to synchronize.
Open the Android source code.
Confirm that the WebView URL points to the running Flask server.
Build and run the application on an Android device.
Example WebView address:

webView.loadUrl("http://192.168.x.x:5000")
Requirements
Software
Python 3.x
Visual Studio Code or another Python IDE
Android Studio
Git
Python Libraries
The exact package list should be maintained in:

requirements.txt
For the current Flask/Pandas workflow, the main dependencies are expected to include:

Flask
pandas
Add any other libraries used by analysis.py or app.py to requirements.txt.

Main Features
Student academic data analysis
Data preprocessing
Processed CSV generation
Academic performance overview
Student record browsing
Individual student details
Responsive Flask dashboard
Analysis page
Mobile-friendly interface
Android WebView application
Academic Purpose
This project was developed as an academic data-analysis system.

The project demonstrates the complete workflow:

Student Data
     ↓
Data Cleaning
     ↓
Data Processing
     ↓
Academic Analysis
     ↓
Flask Application
     ↓
Android Application
The system is intended for educational, academic, and demonstration purposes.

Future Enhancements
Possible future improvements include:

Advanced academic performance analytics
Subject-wise trend analysis
Student ranking reports
Attendance integration
Predictive performance models
Interactive charts
PDF report generation
Student authentication
Faculty/admin dashboard
Database integration
Public cloud deployment
Secure HTTPS hosting
Standalone mobile backend integration
Repository
GitHub:
https://github.com/mani kishore/Student-Academic-Analysis-System

Developer
Sahu Labs
Designed and Developed by Sahu Labs

Focused on practical solutions in:

Artificial Intelligence
Machine Learning
Data Analytics
Software Development
Web Applications
Mobile Applications
Disclaimer
This project is intended for educational and academic purposes only.

The analysis generated by this project should be interpreted as part of an academic demonstration and should not be treated as an official institutional academic evaluation system unless independently validated for that use.

License
This project is currently intended for educational and academic use.

Student Academic Analysis System

Python • Pandas • Flask • Android

Designed and Developed by Sahu Labs
