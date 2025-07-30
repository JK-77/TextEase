# 🧠 TextEase — Chrome Extension for Smarter, Easier Web Reading

**TextEase** is a lightweight, AI-powered Chrome extension that improves web accessibility by simplifying, customizing, and enhancing the readability of any webpage — making browsing more inclusive and enjoyable for everyone.


## ✨ Features

- 🧠 **AI-based Text Simplification** using the Cohere API  
- 📚 **Content Summarization** for quick understanding  
- 🌐 **Works on Any Webpage** seamlessly  
- 🧩 **Accessibility Modes**  
  - 🟣 Dyslexia Mode  
  - 🟡 Colorblind Mode  
- 🔤 **Text Customization**  
  - Choose from fonts like *Arial*, *Verdana*, etc.  
  - Set **font size** and **letter spacing** with sliders  
  - Toggle **bold** mode  
  - One-click **reset to defaults**  
- 🛠️ **Text Tools**  
  - ✅ Simplify Text  
  - 🔊 Speak Text (Text-to-Speech)  
  - 🌍 Translate to any language  
- 🔉 **Speech Settings**  
  - Adjust **rate** and **pitch** of voice  
- 🔐 **Privacy-Conscious** and **Fast**  
- 🔑 Use your own API key or connect to our backend  


## 🚀 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/JK-77/TextEase.git
cd TextEase

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
