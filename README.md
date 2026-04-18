<!-- ============== HEADER ============== -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,6,20,24&height=180&section=header&text=NLP%20%C2%B7%20LLM%20Projects&fontSize=40&fontAlign=50&fontAlignY=40&desc=Transformers%20%C2%B7%20RAG%20%C2%B7%20Agents%20%C2%B7%20Semantic%20Search&descAlign=50&descAlignY=70&descSize=14&fontColor=ffffff&animation=fadeIn" alt="NLP LLM Projects header"/>

<p align="center">
A curated index of my NLP, transformer, RAG, and multi-agent LLM work. Ranges from text classification to production RAG pipelines, multi-agent systems, and LLM evaluation. Each card links to a standalone repo with full code and walkthroughs.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black"/>
  <img src="https://img.shields.io/badge/Transformers-FF6B35?style=flat-square"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/FAISS-0081CB?style=flat-square"/>
  <img src="https://img.shields.io/badge/spaCy-09A3D5?style=flat-square&logo=spacy&logoColor=white"/>
</p>

---

## 📝 Text Classification & Core NLP

<table>
<tr>
<td width="50%" valign="top">
<h4>📧 <a href="https://github.com/anthonyrodrigues443/Email-Spam-Classification">Email Spam Classification</a></h4>
Flask web app classifying emails as spam or legitimate using an ANN over NLTK/BeautifulSoup-preprocessed text features.
<br><br>
<img src="https://img.shields.io/badge/NLTK-2E8B57?style=flat-square"> <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white"> <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white">
</td>
<td width="50%" valign="top">
<h4>⚖️ <a href="https://github.com/anthonyrodrigues443/Legal-Contract-Analyzer">Legal Contract Analyzer</a></h4>
NER-based clause extraction and risk scoring from legal contracts using transformer models on the CUAD dataset.
<br><br>
<img src="https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black"> <img src="https://img.shields.io/badge/spaCy-09A3D5?style=flat-square&logo=spacy&logoColor=white"> <img src="https://img.shields.io/badge/CUAD-10B981?style=flat-square">
</td>
</tr>
</table>

## 🔤 Semantic Embeddings & Recommendation

<table>
<tr>
<td width="50%" valign="top">
<h4>🎬 <a href="https://github.com/anthonyrodrigues443/CineSemantics-Transformer-Powered-Movie-Recommendation-Engine">CineSemantics — Transformer-Powered Recommender</a></h4>
Content-based movie recommender using BERT/SBERT embeddings over titles, descriptions, and tags for semantic similarity.
<br><br>
<img src="https://img.shields.io/badge/BERT-FFD21E?style=flat-square&logo=huggingface&logoColor=black"> <img src="https://img.shields.io/badge/SBERT-F59E0B?style=flat-square"> <img src="https://img.shields.io/badge/Recsys-FF4B6E?style=flat-square">
</td>
<td width="50%" valign="top">
<h4>💘 <a href="https://github.com/anthonyrodrigues443/MatchMind-Dating_Profile_Recommendation_System">MatchMind — Dating Profile Matcher</a></h4>
Hybrid dating recommender combining SBERT semantic embeddings with cross-encoder re-ranking and multi-signal weighting.
<br><br>
<img src="https://img.shields.io/badge/SBERT-F59E0B?style=flat-square"> <img src="https://img.shields.io/badge/CrossEncoder-8B5CF6?style=flat-square"> <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white">
</td>
</tr>
</table>

## 🔍 RAG & Retrieval Systems

<table>
<tr>
<td width="50%" valign="top">
<h4>🧪 <a href="https://github.com/anthonyrodrigues443/RAG-Pipeline-Optimizer">RAG Pipeline Optimizer</a></h4>
Systematic evaluation of RAG configurations across chunking, embeddings, retrieval, re-ranking, and generation — with RAGAS benchmarking.
<br><br>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white"> <img src="https://img.shields.io/badge/RAGAS-FF6B35?style=flat-square"> <img src="https://img.shields.io/badge/FAISS-0081CB?style=flat-square">
</td>
<td width="50%" valign="top">
<h4>🤖 <a href="https://github.com/anthonyrodrigues443/RAG-Noah-Multi-Modal-LLM-Assistant">RAG-Noah — Multi-Modal LLM Assistant</a></h4>
Multi-modal LLM assistant combining RAG, reasoning, and real-time computer vision — designed to run on smart glasses.
<br><br>
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white"> <img src="https://img.shields.io/badge/OpenCV-27338e?style=flat-square&logo=opencv&logoColor=white"> <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white">
</td>
</tr>
</table>

## 🧩 Multi-Agent Systems

<table>
<tr>
<td width="50%" valign="top">
<h4>🌾 <a href="https://github.com/anthonyrodrigues443/AgriWise-Multi-Agent-Agricultural-Assistant-for-Crop-Advisory-and-Disease-Detection-System">AgriWise — Agricultural Multi-Agent Assistant</a></h4>
Multi-agent system that recommends crops via RAG over research papers and detects plant diseases with CV models.
<br><br>
<img src="https://img.shields.io/badge/Agents-7C3AED?style=flat-square"> <img src="https://img.shields.io/badge/RAG-FF4B6E?style=flat-square"> <img src="https://img.shields.io/badge/CNN-00C9A7?style=flat-square">
</td>
<td width="50%" valign="top">
<h4>🩺 <a href="https://github.com/anthonyrodrigues443/SwasthAI-Multi-Agent-Intelligent-Healthcare-Diagnostic-and-Advisory-System">SwasthAI — Healthcare Diagnostic System</a></h4>
Interoperable AI agents managing patient assessment, diagnosis, medical imaging, and clinical decision support.
<br><br>
<img src="https://img.shields.io/badge/Agents-7C3AED?style=flat-square"> <img src="https://img.shields.io/badge/RAG-FF4B6E?style=flat-square"> <img src="https://img.shields.io/badge/Medical%20Imaging-14B8A6?style=flat-square">
</td>
</tr>
</table>

## 📊 LLM & Agent Evaluation

<table>
<tr>
<td width="50%" valign="top">
<h4>🧮 <a href="https://github.com/anthonyrodrigues443/AI-Agent-Conversation-Quality-Scorer">Agent Conversation Quality Scorer</a></h4>
Multi-dimensional scoring of AI-agent conversations for quality, hallucination detection, and tone analysis.
<br><br>
<img src="https://img.shields.io/badge/LLM%20Eval-412991?style=flat-square&logo=openai&logoColor=white"> <img src="https://img.shields.io/badge/Hallucination-FF4B6E?style=flat-square"> <img src="https://img.shields.io/badge/NLP-06B6D4?style=flat-square">
</td>
<td width="50%" valign="top">
<h4>⚠️ <a href="https://github.com/anthonyrodrigues443/AI-Agent-Failure-Predictor">AI Agent Failure Predictor</a></h4>
Predicts AI-agent workflow failures from task complexity, token usage, and latency signals — before they happen.
<br><br>
<img src="https://img.shields.io/badge/XGBoost-0080FF?style=flat-square"> <img src="https://img.shields.io/badge/Observability-22C55E?style=flat-square"> <img src="https://img.shields.io/badge/Agents-7C3AED?style=flat-square">
</td>
</tr>
</table>

---

## 🚀 Getting Started

1. Click the repo link on any project card above.
2. Each repo contains its own setup guide, dataset notes, and walkthrough notebook.
3. Found something useful? A ⭐ on the individual project repo is appreciated.

## 📫 Connect

<p align="center">
  <a href="mailto:anthonyrodrigues443@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"></a>
  <a href="https://linkedin.com/in/anthonyrodrigues443"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://github.com/anthonyrodrigues443"><img src="https://img.shields.io/badge/Profile-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,6,20,24&height=100&section=footer" alt="footer"/>
