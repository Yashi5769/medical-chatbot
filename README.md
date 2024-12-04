
A chatbot based on sklearn where you provide it with a symptom and answer some followup questions. It will help you by offering a diagnosis and some advice.

Dataset from "https://www.kaggle.com/datasets/itachi9604/disease-symptom-description-dataset?select=symptom_Description.csv"

RUN FOLLOWING CODE IN VS CODE TERMINAL:

python3 -m venv venv
source venv/bin/activate
pip install --upgrade pip
pip install streamlit
pip install pyttsx3
pip install scikit-learn
streamlit run chat_bot.py
