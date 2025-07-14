🧠 Sentiment Analysis Web Tool
🛠️ Technologies Used
TextBlob — Sentiment analysis

Flask-SQLAlchemy — Database ORM

SQLite — Lightweight database for storing entries

HTML/CSS — Frontend templates

Render — Cloud deployment

🚀 How to Run Locally
1. Clone the repository
git clone https://github.com/ldodson10/sentiment-app.git
cd sentiment-app
2. Create and activate a virtual environment (recommended):
python -m venv venv
venv\Scripts\activate        # On Windows
3. Install the required packages:
pip install -r requirements.txt
4. Run the application:
python app.py
Visit http://localhost:5000 in your browser.

☁️ Deployment with Render
This project is deployed using Render, a cloud hosting platform that enables developers to launch web applications with ease.

⚡ Why Render?
Render simplifies the process of hosting and running backend applications like this Flask-based sentiment analysis tool. It automatically pulls the latest code from GitHub and deploys it, eliminating the need to manually manage infrastructure.

🔧 Workflow Overview
GitHub is used to store, version, and manage the project code.
Render connects to the GitHub repository, builds the application, and hosts it live.

🔗 Live Demo: https://sentiment-app-6y17.onrender.com

🗂️ Project Structure
📁 sentiment-app/
├── app.py              # Main application logic
├── requirements.txt    # Python dependencies
├── render.yaml         # Render deployment configuration
├── templates/          
│   ├── index.html      # Input form page
│   └── result.html     # Output results page
├── static/             # Static assets (if any)
└── README.md           # Project documentation