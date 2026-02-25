# 🛡️ Industrial Safety Risk Analysis – NLP Chatbot

## Overview
This project focuses on **industrial safety risk analysis** using **Natural Language Processing (NLP)** and **Machine Learning (ML)** techniques.  
The goal is to design a chatbot utility that can analyze accident descriptions and highlight potential safety risks, helping professionals proactively mitigate hazards.

The dataset used comes from one of the largest industrial organizations in Brazil, covering **425 accident records** across **12 plants in 3 countries**.  
Each record contains details such as accident level, potential severity, industry sector, critical risk, and narrative descriptions.

---

## Objectives
- Identify key safety risks from historical accident data.
- Predict potential accident severity using ML/DL models.
- Extract insights from unstructured incident descriptions.
- Support proactive risk mitigation strategies via a chatbot interface.

---

## Project Milestones
### Milestone 1
- Data import, cleansing, and preprocessing (TF-IDF, GloVe embeddings).
- Exploratory Data Analysis (EDA).
- Training baseline ML classifiers (Random Forest, Extra Trees, XGBoost, Logistic Regression).

### Milestone 2
- Advanced modeling with Neural Networks, RNN/LSTM.
- Model evaluation and selection.
- Pickling the best-performing classifier.

### Milestone 3 (Optional)
- Development of a clickable chatbot interface (Tkinter for desktop, Flask/Django for web).

---

## Key Findings
- **Extra Trees Classifier with TF-IDF embedding** achieved the best performance:
  - Accuracy: **0.813**
  - F1 Score (Macro): **0.811**
- After hyperparameter tuning and oversampling, **Random Forest and Extra Trees** achieved **~99.55% accuracy** for accident level prediction.
- Strong correlations were observed between:
  - Accident severity and description length.
  - Potential vs. actual accident levels.
  - Third-party involvement and higher accident severity.

---

## Repository Contents
- 📄 **[Final Report](Final%20Report.pdf)** – Detailed technical analysis, EDA, model training, and evaluation.
- 📄 **[Capstone Project Guidelines](AIML%20Capstone%20Project%20-%20NLP%20chatbot-3.pdf)** – Problem statement, milestones, and scoring rubric.
- 📄 **[Final Submission](NLP_Chatbot_Project_Final_submission.pdf)** – Consolidated project submission including chatbot interface (too large to preview directly).

---

## Other Project Files
- **Final Report for Industrial Safety Risk Analysis – Milestone 1,2,3**  
  Comprehensive technical report with data preprocessing, exploratory analysis, model training, and evaluation results.

- **NLP Chatbot Project Final Submission**  
  Full consolidated submission including trained models and chatbot interface implementation.

- **AIML Capstone Project – NLP Chatbot**  
  Project guidelines, scoring rubric, and milestone descriptions.

---

## Tools & Libraries
- **Python** (scikit-learn, pandas, numpy, matplotlib, seaborn)
- **NLP**: TF-IDF, GloVe, MiniLM (SBERT)
- **ML Models**: Random Forest, Extra Trees, XGBoost, Bagging, Logistic Regression
- **GUI**: Tkinter (desktop), Flask/Django (web)

---

## Contributors
- Bindhu Sukumaran  
- Chaitanya Soman  
- Gurudath Sadanandan  
- Ankit Dadhich  
- Bharath  

---

## License
This project is for **academic and research purposes only**.  
Unauthorized sharing or publishing of the contents is prohibited.
