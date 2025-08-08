#  Sentiment Analysis: Nepal's Political Scenario

This project analyzes public sentiment surrounding Nepal's political landscape using machine learning and NLP techniques. We collected comments from social media platforms like **YouTube** and **Twitter** targeting major political figures before and after elections, allowing us to observe changes in public opinion over time.

---

##  Tools & Models Used

- **Pretrained Models**:
  - `DistilBERT` – English sentiment classification
  - `DistilRoBERTa` – English emotion detection
  - `Nepali BERT` – Devanagari sentiment classification
- **Libraries**: Python, Hugging Face Transformers, NLTK, SpaCy, TextBlob, Langdetect, Deep_Translator
- **Visualization**: Word clouds, bar charts, comparative emotion/sentiment plots

---

## 📊 Model Performance

| Model                          | Accuracy | Precision | Recall | F1 Score |
|-------------------------------|----------|-----------|--------|----------|
| DistilRoBERTa (Emotion - EN)  | 0.710    | 0.749     | 0.710  | 0.685    |
| DistilBERT (Sentiment - EN)   | 0.913    | 0.898     | 0.930  | 0.914    |
| Nepali BERT (Sentiment - NP)  | 0.760    | 0.810     | 0.781  | 0.757    |

---

## Features

- Web scraping and dataset creation for 4 politicians:
  - KP Sharma Oli
  - Sher Bahadur Deuba
  - Prachanda
  - Balen Shah
- Exploratory Data Analysis (EDA): Word clouds, frequency graphs, sentiment shifts before vs after elections
- Real-time multilingual sentiment & emotion classification
- Fine-grained emotion analysis using transformer-based architectures

---

## Limitations & Future Work

### Limitations
- Sarcasm and slang remain challenging to detect
- Dataset imbalance in political texts
- Dependency on pretrained models not optimized for local political context

### Future Enhancements
- Integrate sarcasm detection
- Real-time dashboards for visualizing sentiment shifts
- Optimize for large-scale data and latency using cloud-based solutions
