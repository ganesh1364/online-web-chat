# Real-Time Web Chat Application

A lightweight, responsive web chat product built with a focus on clean code and efficient real-time communication. This project demonstrates a full-stack approach using **Python (Flask)** for backend logic and **JavaScript** for dynamic frontend interactions.

## 🚀 Features

- **Real-Time Interaction:** Instant message updates for a seamless user experience.
- **Responsive UI:** Fully mobile-responsive design built with HTML5 and CSS3 (Tailwind-ready).
- **Session-Based:** Secure temporary chat rooms that manage user sessions efficiently.
- **Clean Architecture:** Modular code structure separating business logic (Python) from presentation (HTML/CSS).

## 🛠 Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **Backend:** Python, Flask
- **Environment:** Virtualenv, Pip

## 📁 Project Structure


online-web-chat/
├── app.py              # Main Flask application & routing
├── static/             # Frontend assets
│   ├── css/            # Custom styling
│   └── js/             # Frontend logic & DOM manipulation
├── templates/          # HTML templates
│   └── index.html      # Main chat interface
└── requirements.txt    # Project dependencies
⚙️ Installation & Setup
Follow these steps to run the project locally:
Clone the repository:
code
Bash
git clone https://github.com/ganesh1364/online-web-chat.git
cd online-web-chat
Create a virtual environment (Recommended):
code
Bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:
code
Bash
pip install -r requirements.txt
Run the application:
code
Bash
python app.py
The app will be available at http://127.0.0.1:5000/.
