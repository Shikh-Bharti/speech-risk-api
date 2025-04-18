python -m spacy download en_core_web_sm
https://speech-risk-api-10.onrender.com/docs
# speech-risk-api
# 🧠 Speech Cognitive Score API

This project is a FastAPI-based machine learning API that analyzes speech audio and returns a **cognitive risk score**. The goal is to help detect early signs of cognitive decline (like stress, confusion, or memory issues) from voice inputs using audio feature extraction and NLP.

---

## 🚀 Features

- Upload a `.wav` or `.mp3` audio file
- Extract features like MFCC, Chroma, ZCR, etc.
- Use basic NLP with spaCy to assess semantic coherence
- Generate a **cognitive risk score** (0 to 100)
- Clean API endpoint: `/upload-audio/`
- Swagger-based docs at `/docs`

---

## 🛠️ Tech Stack

- **FastAPI** – API framework
- **Uvicorn** – ASGI server
- **Librosa** – Audio processing
- **SpaCy** – NLP engine
- **Scikit-learn** – Model logic
- **Render.com** – Cloud deployment

---

## 📁 File Structure

```bash
.
├── main.py             # FastAPI app with ML logic
├── requirements.txt    # Python dependencies
└── README.md           # You're here!


