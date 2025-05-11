# 🧠 Intelligent Symptom Interpretation System

## 📘 Project Overview
The **Intelligent Symptom Interpretation System** is a chatbot designed for healthcare settings that interprets vague or indirect symptom descriptions from patients and maps them to probable medical conditions. This is especially useful in hospitals where patients may describe symptoms like “I feel dizzy when I get up” instead of using clinical terminology.

---

## 🎯 Objectives
- Interpret vague, non-clinical symptom inputs from users.
- Use NLP for preprocessing and Named Entity Recognition (NER).
- Map identified symptoms to medical conditions using a simple ontology.
- Provide a chatbot-style interface with helpful responses.

---

## 🧩 Components
| Module | Function |
|--------|----------|
| `app.py` | Main chatbot loop |
| `preprocessing.py` | Cleans and lemmatizes input |
| `ner_module.py` | Extracts medical-related symptoms |
| `ontology_mapper.py` | Maps symptoms to probable conditions |
| `chatbot_response.py` | Generates user-facing replies |

---

## 🗃 Example Input & Output

**User Input:**

I feel lightheaded sometimes, and my legs feel weak after walking.

**Chatbot Output:**

Based on your symptoms (lightheadedness, leg weakness), you might be experiencing one of the following conditions: Anemia, Orthostatic Hypotension, Peripheral Neuropathy, Multiple Sclerosis. Please consult a healthcare professional for an accurate diagnosis.


---

## 🛠 How to Run (Windows, macOS, Linux)

### ✅ Prerequisites
- Python 3.8+
- `spaCy` and English language model

---

### 🖥 Installation Steps (Windows)

1. **Install Python** (if not already installed) from [python.org](https://www.python.org/downloads/).
2. **Open Command Prompt** (press `Win + R`, type `cmd`, and press Enter).
3. **Install required packages**:
    ```bash
    pip install -r requirements.txt
    python -m spacy download en_core_web_sm
    ```
4. **Run the Chatbot**:
    ```bash
    python app.py
    ```

---

### 🍏 Installation Steps (macOS)

1. **Install Python** (if not already installed) from [python.org](https://www.python.org/downloads/).
2. **Open Terminal** (press `Cmd + Space`, type `Terminal`, and press Enter).
3. **Install required packages**:
    ```bash
    pip install -r requirements.txt
    python -m spacy download en_core_web_sm
    ```
4. **Run the Chatbot**:
    ```bash
    python app.py
    ```

---

### 🐧 Installation Steps (Linux)

1. **Install Python** (if not already installed) from [python.org](https://www.python.org/downloads/).
2. **Open Terminal**.
3. **Install required packages**:
    ```bash
    pip install -r requirements.txt
    python -m spacy download en_core_web_sm
    ```
4. **Run the Chatbot**:
    ```bash
    python app.py
    ```

---

## 📂 Files Included
- `app.py` – Main chatbot script
- `preprocessing.py` – Input cleaner
- `ner_module.py` – Extracts symptoms
- `ontology_mapper.py` – Symptom-condition mapping
- `chatbot_response.py` – Response builder
- `requirements.txt` – Python dependencies
- `README.md` – This file

---

## 🧠 Future Improvements
- Real medical NER using SciSpacy or Med7
- Use SNOMED or ICD-10 for advanced ontology mapping
- Deep learning model for better context understanding
- Web-based interface

---

## 👨‍⚕️ Disclaimer
This tool is **not a diagnostic system**. It is an academic project for demonstration purposes only. Always consult a healthcare professional for medical advice.

---

## 📜 License
MIT License (for academic use)
