
# 🩺 Radiology Report Dual Summarizer  

This project focuses on automatic summarization of radiology reports using deep learning and transformer-based models. The goal is to generate concise and clinically meaningful summaries from long radiology findings. The system is designed to support both **doctors** and **patients** by providing two types of summaries:

1. Clinical summary (technical – for doctors)
2. Simplified summary (easy language – for patients)
Colab link : https://colab.research.google.com/drive/1Odu0TZYMBcNygUXyGF2G__z5A3-Iac5j
---

## 📌 Project Overview  

Radiology reports are long and contain technical medical language. This makes it difficult for doctors to quickly identify important findings and for patients to understand their reports.  

This project uses **Artificial Intelligence, Natural Language Processing (NLP), and Large Language Models (LLMs)** to automatically generate:

- Doctor-level clinical impressions  
- Patient-friendly summaries  

The model is based on transformer architectures such as **T5 and BART**, which are widely used for text summarization.

---

## 🎯 Key Features  

✔ Dual summarization (Doctor + Patient)  
✔ Transformer-based deep learning  
✔ Fine-tuning on radiology text  
✔ Synthetic + real-style dataset  
✔ Training and loss visualization  
✔ End-to-end workflow from data to summary  

---

## 📊 Dataset  

The dataset contains radiology **findings and impressions** used to train the summarization model.

You can download it from the link below:

👉 Radiology Dataset:  
https://drive.google.com/drive/folders/1cUcUEgto8l4CFEeDz3YzDMSN9PTQiWEq?usp=sharing  

The dataset contains:
- 5000+ radiology report samples  
- Structured format: Findings → Impression  
- Suitable for training transformer models  

Public datasets such as MIMIC-CXR inspired the structure of this data. These datasets contain paired radiology findings and impressions used for supervised learning. :contentReference[oaicite:0]{index=0}  

---

## ⚙️ Model Architecture  

This project uses:

- Transformer-based models (T5, BART)
- Encoder–decoder architecture
- Sequence-to-sequence learning
- Prompt-based dual summarization  
  - "Summarize medically" → Doctor summary  
  - "Summarize simply" → Patient summary  

---

## 🚀 Workflow  

1. Data preprocessing  
2. Tokenization  
3. Model training  
4. Dual summarization  
5. Evaluation  
6. Visualization  
7. Testing  

---

## 📉 Training Loss Curve  

The model shows decreasing training loss, indicating learning and convergence.

<img width="580" height="466" alt="Screenshot 2026-02-14 at 1 32 46 PM" src="https://github.com/user-attachments/assets/feab5d1e-2d39-44db-a076-9504e9c34641" />

---

## 🧪 Sample Results  

### 🔹 Input  
Patchy opacity in left lower lobe. Possible pneumonia.

### 🔹 Doctor Summary  
Possible pneumonia.

### 🔹 Patient Summary  
This means there may be an infection in the lower part of the lung.

<img width="580" height="170" alt="Screenshot 2026-02-14 at 1 40 59 PM" src="https://github.com/user-attachments/assets/4f0178c6-0a24-4463-b11c-bb67b93fb2e8" />


---

## 🛠 Technologies Used  

- Python  
- Hugging Face Transformers  
- PyTorch  
- NLP and Deep Learning  
- Google Colab  

---

## 📌 Future Improvements  

- Real hospital datasets  
- Indian demographic data  
- Multilingual summaries  
- Image + report multimodal system  
- Explainable AI  
- Clinical validation  

---

## 📖 Conclusion  

This work demonstrates how AI can improve clinical efficiency and patient understanding by generating accurate and easy-to-read summaries from complex radiology reports.

---

## 👨‍🏫 Guidance  

Under the guidance of **Dr. Onkar Singh**
