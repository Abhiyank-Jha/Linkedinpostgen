# 📢 LinkedIn Post Generator

🚀 **Generate engaging LinkedIn posts using Llama and Streamlit!**

## 🔥 Features
- **AI-powered post generation** using Llama models
- **User-friendly UI** built with Streamlit
- **Customizable post length & topics**
- **Real-time API integration** with Groq

## 🛠️ Tech Stack
- **Python**
- **Streamlit** (for UI)
- **Langchain-Groq** (for Llama model)
- **dotenv** (for secure API key handling)

## 📦 Installation

### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/yourusername/linkedin-post-generator.git
cd linkedin-post-generator
```

### **2️⃣ Set Up Virtual Environment (Optional)**
```sh
python -m venv venv  # Create virtual environment
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate  # On Windows
```

### **3️⃣ Install Dependencies**
```sh
pip install -r requirements.txt
```

### **4️⃣ Set Up API Key**
Create a `.env` file in the project root and add:
```ini
GROQ_API_KEY=your_actual_api_key_here
```

Or, manually set it:
```sh
export GROQ_API_KEY=your_actual_api_key_here  # macOS/Linux
set GROQ_API_KEY=your_actual_api_key_here  # Windows
```

### **5️⃣ Run the Application**
```sh
streamlit run app.py
```

## 📜 Usage
1. Open the Streamlit app in your browser.
2. Select **post length**, **language**, and **topic**.
3. Click **Generate Post** to get AI-generated content.
4. Copy & share your post on LinkedIn!

## 🏗️ Project Structure
```
📂 linkedin-post-generator
 ├── 📄 app.py  # Main Streamlit app
 ├── 📄 llm_helper.py  # Llama API integration
 ├── 📄 post_generator.py  # Post generation logic
 ├── 📄 requirements.txt  # Dependencies
 ├── 📄 .env  # API key (not shared)
 └── 📄 README.md  # Project documentation
```

## 💡 Future Enhancements
- 🔄 **Multi-language support**
- 🎨 **Better UI with themes**
- 🏆 **AI-powered post ranking**

## 👏 Contributing
Feel free to submit PRs, suggestions, or bug reports.

## 📜 License
MIT License © 2025 Your Name

---
🔥 Built with ❤️ by [Abhiyank Jha]((https://github.com/Abhiyank-Jha))
