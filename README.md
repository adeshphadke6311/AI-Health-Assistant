# 🏥 AI Health Assistant Chatbot

A simple and interactive **AI-powered healthcare chatbot** built using **Streamlit**, **Hugging Face Transformers**, and **NLTK**.
This chatbot provides basic guidance related to symptoms, appointments, and medications, along with AI-generated responses for general queries.

---

## 🚀 Features

* 💬 Interactive chatbot UI using Streamlit
* 🤖 AI-generated responses using `distilgpt2`
* 🩺 Basic healthcare query handling:

  * Symptoms → Suggest consulting a doctor
  * Appointment → Scheduling prompt
  * Medication → Reminder guidance
* ⚡ Real-time response with loading spinner

---

## 🛠️ Tech Stack

* **Python**
* **Streamlit** – Web interface
* **Transformers (Hugging Face)** – AI model
* **NLTK** – Text processing

---

## 📂 Project Structure

```
AI-Health-Assistant/
│── app.py              # Main application file
│── requirements.txt    # Dependencies
│── README.md           # Project documentation
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/adeshphadke6311/AI-Health-Assistant.git
cd AI-Health-Assistant
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Download NLTK Resources

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

Then open your browser at:

```
http://localhost:8501
```

---

## 💡 How It Works

* The chatbot first checks for **keyword-based queries**:

  * `"symptom"` → Suggests consulting a doctor
  * `"appointment"` → Offers scheduling
  * `"medication"` → Provides general advice

* If no keyword is matched, it uses a **pre-trained language model (`distilgpt2`)** to generate a response.

---

## ⚠️ Disclaimer

> This chatbot is **not a substitute for professional medical advice**.
> Always consult a qualified healthcare provider for medical concerns.

---

## 📌 Future Improvements

* ✅ Add symptom-based disease prediction
* ✅ Integrate real healthcare APIs
* ✅ Add user authentication & history
* ✅ Improve NLP accuracy with fine-tuned models
* ✅ Deploy on cloud (AWS / Render / Hugging Face Spaces)

---

## 👨‍💻 Author

**Adesh Phadke**
B.E. Computer Engineering Student
💻 Passionate about AI, Web Development & Problem Solving

---

## ⭐ Support

If you like this project:

* ⭐ Star the repository
* 🍴 Fork it
* 🤝 Contribute

---
