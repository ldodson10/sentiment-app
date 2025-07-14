💬 Sentiment Analysis Web Tool
A simple yet powerful Flask-based web tool that analyzes user input text to determine sentiment — positive, negative, or neutral — using natural language processing.

🧠 Technologies Used
Python 3

Flask — Web framework

TextBlob — Sentiment analysis

Flask-SQLAlchemy — Database ORM

SQLite — Lightweight database for storing entries

HTML/CSS — Frontend templates

Render — Cloud deployment

🚀 How to Run Locally
Clone the repository:

bash
Copy
Edit
git clone https://github.com/ldodson10/sentiment-app.git
cd sentiment-app
Create and activate a virtual environment (recommended):

bash
Copy
Edit
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
Install the required packages:

bash
Copy
Edit
pip install -r requirements.txt
Run the application:

bash
Copy
Edit
python app.py
Visit http://localhost:5000 in your browser to use the app.

🌐 Deployment with Render
This project is deployed using Render, a cloud hosting platform that enables developers to launch web applications with ease.

⚙️ Why Render?
Render simplifies the process of hosting and running backend applications like this Flask-based sentiment analysis tool. It automatically pulls the latest code from GitHub and deploys it, eliminating the need to manually manage infrastructure.

🔁 Workflow Overview
GitHub is used to store, version, and manage the project code.

Render connects to the GitHub repository, builds the application, and hosts it live.

🔗 Live Demo:
https://sentiment-app-6yT7.onrender.com

📂 Project Structure
csharp
Copy
Edit
sentiment-app/
├── app.py               # Main application logic
├── requirements.txt     # Python dependencies
├── render.yaml          # Render deployment configuration
├── templates/
│   ├── index.html       # Input form page
│   └── result.html      # Output results page
├── static/              # Static assets (if any)
└── README.md            # Project documentation
✅ Features
Accepts user-submitted text

Analyzes and returns sentiment using TextBlob

Stores past entries in a local SQLite database

Simple UI for submitting and viewing results

📌 License
This project is licensed under the MIT License.