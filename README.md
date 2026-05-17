# 🎓 RGM College Assistant

An AI-powered smart college assistant chatbot designed to help students with academic and campus-related queries.

---

## 🚀 Features

- 🤖 AI chatbot for answering college queries
- 🎤 Voice input support using Whisper
- 🌐 Multi-language support
- 🧠 Semantic search using FAISS
- 📍 Campus location assistance
- 🔐 Login & Registration system
- 💾 MongoDB database integration
- ⚡ Fast and interactive Flask web application

---

## 🛠️ Technologies Used

- Python
- Flask
- MongoDB
- FAISS
- Sentence Transformers
- Whisper AI
- HTML
- CSS
- JavaScript

---

## 📂 Project Structure

```bash
RGM-College-Assistant/
│
├── app.py
├── build_faiss.py
├── templates/
├── static/
├── rag_data/
├── rag_data_optimized_new/
├── requirements.txt
└── README.md
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/Devriyazai/RGM-College-Assistant.git
```

---

## 2️⃣ Move into Project Folder

```bash
cd RGM-College-Assistant
```

---

## 3️⃣ Create Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Linux / Mac

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## 4️⃣ Install Required Packages

```bash
pip install -r requirements.txt
```

---

## 5️⃣ Install MongoDB

Download and install MongoDB:

https://www.mongodb.com/try/download/community

After installation start MongoDB service.

---

## 6️⃣ Create Environment File

Create a `.env` file in project root folder and add:

```env
GROQ_API_KEY=your_api_key_here
```

---

## 7️⃣ Build FAISS Index

```bash
python build_faiss.py
```

---

## 8️⃣ Run the Application

```bash
python app.py
```

---

## 9️⃣ Open in Browser

```text
http://127.0.0.1:5000
```

---

# 📸 Features Included

- Student query answering
- Department information
- Admissions guidance
- Placement details
- Campus facilities information
- Examination information

---

# 🔐 Security

Sensitive API keys are stored securely using environment variables.

---

# 👨‍💻 Contributors

- Shaik Bepari Suhana Afreen
- Devriyazai

---

# ⭐ Future Improvements

- Better UI/UX
- Deployment to cloud
- Mobile responsive design
- More AI integrations

---

# 📌 Project Status

✅ Completed and functional
