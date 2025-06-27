# Gemini-Chatbot
Gemini Chatbot is an AI-powered conversational assistant built by integrating Gemini with a custom frontend using HTML, CSS, and JavaScript, and a backend using Flask and Python. This project demonstrates how to connect Gemini's powerful language capabilities with a user-friendly web interface to create an interactive chatbot experience.
🗂️ Project Structure
bash
Copy
Edit
Gemini-Chatbot/
│
├── integrations/
│   └── Chatbot.html        # Frontend UI for the chatbot
│
├── chatbot.py              # Gemini API integration logic
├── app.py                  # Flask app to serve the chatbot
├── .env                    # Stores API key and environment variables
└── README.md               # Project documentation
⚙️ Tech Stack
Frontend: HTML, CSS, JavaScript

Backend: Python, Flask

AI Integration: Gemini API (via chatbot.py)

Environment Config: .env for storing secret keys

🚀 Getting Started
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/Gemini-Chatbot.git
cd Gemini-Chatbot
2. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Set Up .env File
Create a .env file in the root directory and add your Gemini API key:

ini
Copy
Edit
GEMINI_API_KEY=your_api_key_here
4. Run the Flask App
bash
Copy
Edit
python app.py
Visit http://localhost:5000 in your browser to interact with the chatbot.

📄 License
This project is open-source and available under the MIT License.


