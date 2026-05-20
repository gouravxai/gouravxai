# Gourav Sharma
### Machine Learning Engineer | NLP & Deep Learning
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gourav-sharma-504906235/) [![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gouravsharma4406@gmail.com) [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/gouravxai)

---

## What I'm Doing

Building ML stuff that actually works—not just notebooks. Mostly NLP and deep learning, deploying on Streamlit because it's fast and simple.

Lately been into LLMs, RAG systems, and figuring out how to make models actually useful in production.

---

## Projects

### PDF RAG Bot
Real RAG system. You throw PDFs at it, it chunks them, stores embeddings, answers your questions with sources cited. The kind of thing companies actually need for document analysis.

**Repo:** [DYNAMIC-PDF-RAG-BOT](https://github.com/gouravxai/DYNAMIC-PDF-RAG-BOT)

---

### AI Interview Coach
[Live here](https://ai-interview-coach-pzmflblqnkpbcdf7ec8zmt.streamlit.app/)

Record yourself answering interview questions. It transcribes, scores your answer (0-10), tells you where you used filler words, gives feedback. Built this because interview prep sucks—you need actual feedback, not just pre-recorded questions.

How it works:
- Whisper transcribes your audio in <2 seconds
- Llama evaluates technical accuracy, confidence, how structured your answer was
- Detects filler words (um, uh, like, basically)
- Keeps context across multiple questions

The app is live and people are actually using it. Transcription accuracy is solid, latency is fast.

**Repo:** [AI-INTERVIEW-COACH](https://github.com/gouravxai/AI-INTERVIEW-COACH)

---

### TimelineViz
[Live here](https://timelineviz-using-cnn-and-bilstm-wcg7jujqmruxxylqzc2azy.streamlit.app/)

Most emotion detection just gives you one label for the whole text. This breaks it into sentences and tracks how the emotion changes throughout. So you get a timeline, not just a bucket.

Built with CNN for local features and BiLSTM to understand the sequence. Trained on GoEmotions (28 emotion classes). Gets 44% accuracy, which is decent for 28 different emotions.

The Plotly visualization is pretty clean—you can see the emotional arc of a paragraph.

**Repo:** [TimeLineViz-using-CNN-and-BiLSTM](https://github.com/gouravxai/TimeLineViz-using-CNN-and-BiLSTM)

---

## Other Stuff

- **ANN vs CNN** — Built both from scratch, CNN hit 99.05%, ANN was 97.69%. Shows why conv layers matter for images.
- **House Price Prediction** — Did proper feature engineering (log transforms, interactions), used XGBoost. The kind of project that teaches you how data actually works.
- **Trader Sentiment Analysis** — NLP pipeline for extracting signals from market discussions. Finance is the domain I actually care about.
- **Emotion Detection** — Straight classification work. Preprocessing, training, evaluation.

---

## Stack

**Deep Learning:** PyTorch, TensorFlow  
**Data:** Pandas, NumPy, SQL  
**NLP:** NLTK, Groq API, LangChain  
**Viz:** Plotly, Matplotlib  
**Deployment:** Streamlit  
**General:** Python, Git, Jupyter

---

## Numbers

- 5+ deployed projects (live and working)
- 99.05% accuracy (CNN on images)
- <2s latency (production inference)
- 44% on 28-way emotion classification

---

## What I'm Learning

GRUs, Transformers, fine-tuning LLMs properly, how to actually scale inference.

---

**[GitHub](https://github.com/gouravxai)** | **[LinkedIn](https://www.linkedin.com/in/gourav-sharma-504906235/)** | **[Email](mailto:gouravsharma4406@gmail.com)**
