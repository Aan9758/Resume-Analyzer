
---

# 📄 Resume Analyzer – AI Powered Job Match

> 🚀 An AI-powered Resume Analyzer that extracts insights from resumes and matches them against job descriptions to evaluate candidate fit.
> Built with **Flask + Gemini AI + HTML/CSS frontend**.

---

## ✨ Features

✅ Upload **Resumes (PDF)** and extract structured information
✅ Paste **Job Descriptions** to compare candidate skills vs role requirements
✅ AI-powered **Resume Scoring & Suggestions** using **Gemini API**
✅ Simple, clean **Frontend (HTML + CSS)**
✅ Secure – hides API keys with `.env` file

---

## 🖼️ Demo Preview

🔹 Upload Resume →
🔹 Paste Job Description →
🔹 Get **AI-powered analysis & match percentage**


## 🛠️ Tech Stack

* **Backend:** Python, Flask
* **Frontend:** HTML, CSS
* **AI Model:** Google Gemini API
* **Other:** dotenv for environment variables

---

## 🚀 Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-Aan9758/resume-analyzer.git
cd resume-analyzer
```

### 2️⃣ Create Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Setup API Key

* Create a file named `.env` in the root directory
* Add your Gemini API key:

```
GEMINI_API_KEY=your_api_key_here
```

### 5️⃣ Run the App

```bash
python main.py
```

Your app will be live at: **[http://127.0.0.1:5000/](http://127.0.0.1:5000/)** 🎉

---

## 📂 Project Structure

```
Resume_Analyzer/
│── main.py             # Flask backend
│── analyse_pdf.py      # Resume parsing + Gemini analysis
│── templates/
│   └── index.html      # Frontend HTML
│── static/
│   └── style.css       # Frontend styling
│── .env                # API key (ignored in GitHub)
│── .gitignore
│── README.md
│── requirements.txt
```

---

## ⚡ How It Works

1. Upload resume (PDF) → Extract text
2. Paste Job Description → Send to Gemini AI
3. AI compares **skills, experience, and keywords**
4. Output: **Match Score + Suggestions to Improve Resume**

---

## 🌟 Future Enhancements

* 📊 Dashboard with candidate ranking
* 📍 NLP-based keyword extraction for ATS optimization
* 🌐 Deploy on **Streamlit / Hugging Face / Render**

---

## 🤝 Contributing

Pull requests are welcome!
If you’d like to suggest improvements, please open an **issue**.

---

## 👨‍💻 Author

Made with ❤️ by **[Your Name](https://github.com/your-Aan9758)**
⭐ If you like this project, don’t forget to **star the repo**!

---


