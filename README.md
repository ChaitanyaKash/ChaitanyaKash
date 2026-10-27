## Hi, I'm Chaitanya Kashyap 👋

AI/ML undergrad at **NIT Sikkim** (B.Tech, 2024–2028). I like taking messy, real-world data through cleaning, modelling and honest evaluation. Lately that means **NLP for Indian cybercrime**, in English, Hinglish and Hindi.

> Data doesn't lie, but it takes the right questions to make it speak.

### 🔭 What I'm working on

**[CyberLens](https://github.com/ChaitanyaKash/CyberLens)** · multilingual cybercrime complaint and scam classifier

- Sorts Indian cybercrime complaints (English, Hinglish, typo-heavy text) into **39 fraud subtypes**, using the I4C CyberGuard dataset.
- Cleaned **93,686 records** and found that a "leak-proof" train/test split was hiding recurring complaint templates, so I switched to the official protocol.
- Fused a fine-tuned **XLM-RoBERTa** with a TF-IDF model: macro-F1 **0.2345 → 0.2745** across 39 classes, with bootstrap confidence intervals above zero, including on unseen templates.
- Built a **scam vs. not-scam** detector and tested it on **2,264 real reported scam SMS** and **3,481 real non-scam messages**. Real-world macro-F1 is about **0.76** (vs. ~0.97 on synthetic data), and the main failure is legit promotional SMS. I report that gap instead of hiding it.
- Rejected several model variants (including a newer v3 and HingRoBERTa) because they didn't pass adoption rules I fixed before testing.
- **Streamlit app** with confidence-graded verdicts, PII masking (GLiNER), and rule-based **clarifying questions** when one missing fact decides the answer.
- In progress: a **RAG** layer over official RBI, I4C and DoT documents to give step-by-step guidance and a complaint draft.

**[Customer Segmentation & E-Commerce Analytics](https://github.com/ChaitanyaKash/CustomerSegmentation)** · course project (Data Warehousing & Mining)

- ETL of 25K+ sessions into a star-schema warehouse, RFM features, K-Means / DBSCAN / GMM clustering, Isolation Forest anomalies, and XGBoost with SHAP.
- Currently reworking the labels and evaluation after an audit showed the original target and dataset couldn't support the predictions.

**[Krishi Mitra](https://github.com/ChaitanyaKash/KrishiMitra)** · hackathon farmer-support platform using ISRO NDVI satellite data for crop-health alerts.

### 🛠️ Tools

Python · SQL · PyTorch · Hugging Face Transformers · scikit-learn · XGBoost · SHAP · Pandas · NumPy · Streamlit · Git

### 🌱 Learning

NLP for code-mixed Indian languages, retrieval-augmented generation, and building evaluations that hold up on real data.

### 🤝 Open to

Internships and research in ML engineering, NLP and data science.

### 📫 Reach me

[LinkedIn](https://linkedin.com/in/chaitanya-kashyap) · chaitanyawork03@gmail.com · Telegram [@itschaitanyahere](https://t.me/itschaitanyahere)
