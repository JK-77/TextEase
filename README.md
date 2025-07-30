# 🧠 TextEase — Chrome Extension for Smarter, Easier Web Reading

**TextEase** is a lightweight, AI-powered Chrome extension that improves web accessibility by simplifying, summarizing, and enhancing the readability of any webpage — making browsing easier for everyone.

---

## ✨ Features

- ✅ AI-based text simplification using the Cohere API  
- ✅ Summarizes lengthy web content instantly  
- ✅ Works on any webpage  
- ✅ Fast, lightweight, and privacy-conscious  
- ✅ Use your own API key or connect to our backend server  

---

## 🚀 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/JK-77/TextEase.git
cd TextEase
2. Install Dependencies
Make sure you have Node.js and npm installed. Then run:

npm install
3. (Optional) Use Your Own API Key
If you'd like to use your own Cohere API key:

touch .env
Add the following to your .env file:

COHERE_API_KEY=your_api_key_here
PORT=10000
🧪 Running the Backend Server (If Needed)
If you're using your own API key and want to run the backend server:

npm start
This starts the server at:

http://localhost:10000
🔌 Load the Extension in Chrome
Open Google Chrome

Navigate to: chrome://extensions/

Toggle on Developer Mode (top right)

Click "Load unpacked"

Select the folder containing manifest.json (root of the project)

The TextEase icon should now appear in your Chrome toolbar ✅

🤝 Contributing
Pull requests are welcome!
For major changes, please open an issue first to discuss what you'd like to change.
