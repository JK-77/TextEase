# 🧠 TextSavvy — Chrome Extension for Smarter, Easier Web Reading

**TextEase** is a fast, AI-powered Chrome extension that makes web reading simpler and more accessible for everyone.


## ✨ Key Features

- 🧠 AI text simplification (via Cohere API)  
- 📚 Instant content summarization  
- 🌐 Works on any webpage  
- ⚡ Lightweight & privacy-friendly  
- 🔑 Custom API key or connect to backend  
- 🧩 Accessibility modes (Dyslexia, Colorblind)  
- 🎨 Text customization (font, size, spacing)  
- 🛠️ Simplify, translate, and speak text  
- 🔉 Adjustable speech settings (rate, pitch)


## 🚀 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/JK-77/TextEase.git
cd TextEase
```

### 2. Install Dependencies

Make sure you have **Node.js** and **npm** installed. Then run:

```bash
npm install
```

### 3. (Optional) Use Your Own API Key

If you'd like to use your own [Cohere API key](https://dashboard.cohere.ai/api-keys), create a `.env` file:

```bash
touch .env
```

Then add the following to your `.env` file:

```env
COHERE_API_KEY=your_api_key_here
PORT=10000
```

### 🧪 Running the Backend Server (If Needed)

If you're using your own API key and want to run the backend server locally:

```bash
npm start
```

This will start the server at:

```
http://localhost:10000
```


### 🔌 Load the Extension in Chrome

1. Open **Google Chrome**
2. Navigate to: `chrome://extensions/`
3. Enable **Developer Mode** (top right toggle)
4. Click **“Load unpacked”**
5. Select the folder containing `manifest.json` (root of the project)
6. The **TextEase** icon should now appear in your Chrome toolbar ✅


## 🤝 Contributing

Pull requests are welcome!  
For major changes, please open an issue first to discuss what you'd like to change.
