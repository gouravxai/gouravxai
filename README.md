# Gourav Sharma

ML engineer building stuff with Python, PyTorch, NLP. Currently exploring LLMs and production ML systems.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gourav-sharma-504906235/) [![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gouravsharma4406@gmail.com) [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/gouravxai)

---

## What I'm working on

Mostly deep learning and NLP. I deploy things on Streamlit because it's fast. Right now I'm interested in how LLMs actually work in production, not just training.

---

## Projects

### AI Interview Coach  
[Live demo](https://ai-interview-coach-pzmflblqnkpbcdf7ec8zmt.streamlit.app/) | [Repo](https://github.com/gouravxai/AI-INTERVIEW-COACH)

Record yourself answering interview questions. Gets scored (0-10), detects filler words, gives feedback. Built this because every interview prep resource is either outdated videos or bad UI. Wanted actual real-time feedback.

- Transcribes in <2 seconds using Groq Whisper
- Evaluates with Llama
- Tracks filler words (um, uh, like, basically)
- Keeps context across questions

Live and people use it. Works well.

---

### PDF RAG Bot
[Live demo](https://dynamic-pdf-rag-bot-xsbozwiqebofdkwf8txbwk.streamlit.app/) | [Repo](https://github.com/gouravxai/DYNAMIC-PDF-RAG-BOT)

PDF ingestion + embeddings + retrieval. You throw documents at it, it answers questions with sources cited. Actual useful tool for document analysis.

---

### TimelineViz
[Live demo](https://timelineviz-using-cnn-and-bilstm-wcg7jujqmruxxylqzc2azy.streamlit.app/)

Most emotion detection models just classify the whole text as one emotion. This breaks it into sentences and shows how emotions change throughout. CNN handles local patterns, BiLSTM gets the sequence.

Trained on GoEmotions (28 different emotions). Gets 44% accuracy, which is solid for 28 classes. The visualization is clean—you actually see the emotional arc.

[Repo](https://github.com/gouravxai/TimeLineViz-using-CNN-and-BiLSTM)

---

## Other stuff I've built

- **ANN vs CNN** — Built both from scratch, CNN hit 99.05%, ANN 97.69%. Shows why conv layers matter
- **House Price Prediction** — Log transforms, feature engineering, XGBoost. Proper ML work
- **Trader Sentiment** — NLP for extracting market signals from discussions
- **Emotion Detection** — Standard classification, preprocessing, evaluation

---

## Stack

**Deep Learning:** PyTorch, TensorFlow  
**Data:** Pandas, NumPy, SQL  
**NLP:** NLTK, Groq API, LangChain  
**Viz:** Plotly, Matplotlib  
**Deploy:** Streamlit  

---

## Learning

Right now into GRUs, Transformers, fine-tuning LLMs properly, how to actually scale inference without it being slow or expensive.

---

[GitHub](https://github.com/gouravxai) | [LinkedIn](https://www.linkedin.com/in/gourav-sharma-504906235/) | [Email](mailto:gouravsharma4406@gmail.com)
