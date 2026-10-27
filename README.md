# Chaitanya Kashyap

I'm a B.Tech student in AI & ML at NIT Sikkim (2024–2028). Most of my time right now goes into NLP for Indian cybercrime: complaints and scam messages written in English, Hindi and Hinglish, usually full of typos.

[LinkedIn](https://linkedin.com/in/chaitanya-kashyap) · [chaitanyawork03@gmail.com](mailto:chaitanyawork03@gmail.com) · [Telegram](https://t.me/itschaitanyahere)

## Projects

**[CyberLens](https://github.com/ChaitanyaKash/CyberLens)**
Classifies cybercrime complaints from the I4C CyberGuard dataset into 39 fraud subtypes, and checks whether a message is a scam.

- Cleaned about 93.7K records. Found that my "leak-proof" train/test split was actually hiding recurring complaint templates, so I went back to the official split.
- Combined a fine-tuned XLM-RoBERTa with a TF-IDF model. Macro-F1 went from 0.2345 to 0.2745 over 39 classes. Many classes are rare, so the score is low, but the gain held up under bootstrap tests.
- The scam detector scored ~0.97 on synthetic data but ~0.76 on 2,264 real scam SMS and 3,481 real normal messages. It mostly struggles with genuine promotional SMS. That gap is what I'm working on now.
- Streamlit app with PII masking and a few follow-up questions when one missing detail changes the answer.
- Next: a RAG layer over RBI, I4C and DoT documents so the app can point people to the right steps.

**[Customer Segmentation](https://github.com/ChaitanyaKash/CustomerSegmentation)**
Course project for Data Warehousing & Mining. ETL into a star schema, RFM features, K-Means/DBSCAN/GMM, anomaly detection and XGBoost with SHAP. I'm redoing the labels and evaluation after finding problems in the original setup.

**[Krishi Mitra](https://github.com/ChaitanyaKash/KrishiMitra)**
Hackathon project. A farmer-support site that uses ISRO's NDVI satellite data for crop-health alerts.

## Tools I use

Python, SQL, PyTorch, Hugging Face Transformers, scikit-learn, XGBoost, SHAP, Pandas, NumPy, Streamlit, Git

## Looking for

Internships or research work in ML, NLP or data science. Happy to talk if you're working on something similar.
