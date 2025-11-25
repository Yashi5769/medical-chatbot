# Medical Chatbot

A machine learning-powered conversational AI designed to assist users with healthcare-related queries, symptom assessment, and preliminary medical guidance. This project leverages Natural Language Processing (NLP) to understand user inputs and provide accurate, context-aware responses.

## 📌 Project Overview

The Medical Chatbot acts as a virtual health assistant. It allows users to discuss their symptoms and receive information about potential conditions, precautions, and medications. While it serves as a helpful tool for preliminary information, it is **not a substitute for professional medical advice**.

[Image of medical chatbot architecture NLP flow]

## ✨ Features

* **Symptom Analysis:** Users can input symptoms, and the bot predicts potential diseases.
* **Health Precautions:** Provides precautionary measures for identified conditions.
* **Doctor Recommendations:** Suggests the type of specialist to consult based on the diagnosis.
* **Natural Language Understanding:** Uses NLP techniques to interpret varied user inputs effectively.
* **User-Friendly Interface:** (Optional: Mention if you used Flask/Streamlit/Tkinter for the UI).

## 🛠️ Tech Stack

* **Language:** Python
* **Machine Learning:** Scikit-learn / TensorFlow / Keras
* **NLP:** NLTK (Natural Language Toolkit) / Spacy
* **Web Framework:** Flask / Streamlit (for deployment)
* **Data Handling:** Pandas, NumPy
* **Dataset:** (Mention if you used a specific dataset, e.g., Disease-Symptom Knowledge Database)

## 📂 Project Structure

```plaintext
├── datasets/               # Dataset files (CSV, JSON)
├── model/                  # Saved trained models (e.g., chatbot_model.h5, model.pkl)
├── templates/              # HTML templates (if using Flask)
├── static/                 # CSS/JS files (if using Flask)
├── app.py                  # Main application script
├── training.py             # Script to train the ML model
├── chat.py                 # Script to test the chatbot in the console
├── requirements.txt        # List of dependencies
└── README.md               # Project documentation

```

## 🚀 Installation & Usage

Follow these steps to set up and run the project locally.

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/Yashi5769/medical-chatbot.git](https://github.com/Yashi5769/medical-chatbot.git)
    cd medical-chatbot
    ```

2.  **Create a Virtual Environment (Optional but Recommended)**
    ```bash
    # For Windows
    python -m venv venv
    venv\Scripts\activate

    # For macOS/Linux
    python3 -m venv venv
    source venv/bin/activate
    ```

3.  **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Train the Model**
    If you need to retrain the model on the dataset:
    ```bash
    python training.py
    ```

5.  **Run the Application**
    Start the chatbot interface:
    ```bash
    python app.py
    ```
    Open your browser and navigate to `http://127.0.0.1:5000/` (or the URL provided in the terminal).

---

## 📊 Dataset

The model is trained on a dataset containing various symptoms and their corresponding diseases, precautions, and treatments.

* **Input:** User text (e.g., *"I have a headache and shivering"*)
* **Output:** Predicted Disease & Advice

---

## ⚠️ Disclaimer

> **Note:** This chatbot is for **educational and informational purposes only**. It should not be used for medical diagnosis, advice, or treatment. Always consult with a qualified healthcare professional for medical concerns.

---
