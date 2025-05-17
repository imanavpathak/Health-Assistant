# 🩺 Health Assistant - Your AI Medical Companion

![Health Assistant](https://github.com/imanavpathak/Health-Assistant/blob/main/A%20doctor%20sits%20in%20his%20office%20and%20visualizes%20hologra%20(1).png)

Welcome to the **Health Assistant** — a smart, AI-powered medical chatbot built using **Streamlit** and **LangChain**, powered by NVIDIA's cloud function API. It provides users with:
- 💊 Personalized health advice
- 🍽️ Custom nutrition plans
- 💡 Medical suggestions and lifestyle tips

---

## 🚀 Features

✅ Human-like chat experience  
✅ Accurate and friendly health advice  
✅ Customizable responses based on your needs  
✅ Simple UI via Streamlit  

---

## 📦 Tech Stack

- 🧠 **LangChain** – for natural language processing
- 🎛️ **Streamlit** – for UI
- ☁️ **NVIDIA API** – for inference
- 🔐 **Python-dotenv** – for environment config

---

## 🛠️ Installation & Setup

Follow these steps to set up and run the Health Assistant locally:

### 1. Clone the Repository

```bash
git clone https://github.com/imanavpathak/Health-Assistant.git
cd Health-Assistant

---

2. Install Dependencies
    bash
    Copy
    Edit
    pip install -r requirements.txt
---
3. Run the App
bash
Copy
Edit
streamlit run app.py
Visit http://localhost:8501 in your browser to use the app.

⚙️ Optional Steps (Recommended for Development)
🧪 Use a Virtual Environment
bash
Copy
Edit
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
This helps keep dependencies isolated.

🧾 Store API Keys with .env (If customizing)
env
Copy
Edit
OPENAI_API_KEY=your_key_here
NVIDIA_API_KEY=your_key_here
Use python-dotenv to load them securely in your code.

🔬 Try Out Prompts in the Notebook
Launch Jupyter:

bash
Copy
Edit
jupyter notebook
Open langchain_notebook.ipynb to test or tweak prompt logic.
