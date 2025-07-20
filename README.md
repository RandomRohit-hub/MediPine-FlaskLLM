# MediPine-FlaskLLM













Here’s a **step-by-step instruction block** you can directly add to your `README.md` for your project **MediPine-FlaskLLM** to help others set up the project easily:

---

## 🚀 Setup Instructions for MediPine-FlaskLLM

Follow the steps below to set up the project on your local machine:

### 📦 1. Clone the Repository

```bash
git clone https://github.com/RandomRohit-hub/MediPine-FlaskLLM.git
cd MediPine-FlaskLLM
```

---

### 🐍 2. Create a Conda Environment (Recommended)

> Make sure [Anaconda](https://www.anaconda.com/products/distribution) or Miniconda is installed.

```bash
conda create -n medibotenv python=3.10 -y
conda activate medibotenv
```

---

### 📜 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

---

### 🔑 4. Set Your Environment Variables

Create a `.env` file in the root directory and add your keys:

```env
GROQ_API_KEY=your_groq_api_key
```

---

### ▶️ 5. Run the Flask App

```bash
python app.py
```

Your Flask app should now be running at:
📍 **[http://127.0.0.1:5000](http://127.0.0.1:5000)**

---

### 🧠 LLM Model Used

This app uses **Groq's Mixtral/LLama3** models with **LangChain** for chatbot functionality.

---

### 🛠 Tech Stack

* Python 3.10
* Flask
* LangChain
* Groq API
* Pinecone
* HTML/CSS (for UI)

---

Let me know if you also want a section for **troubleshooting**, **contribution guidelines**, or **deployment (e.g., Render or Railway)**.
