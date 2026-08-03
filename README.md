# HumorSense: Humor Detection in Text Using Ensemble Approach

> Undergraduate Thesis — CSE, Port City International University (PCIU)

## 🏆 Results
| Model | Accuracy |
|-------|----------|
| Logistic Regression | 88.59% |
| SVM | 86.82% |
| CNN | 88.28% |
| BiLSTM | 88.31% |
| BiGRU | 88.52% |
| DistilBERT | 90.40% |
| RoBERTa | 90.68% |
| Stacked Ensemble | 95.03% |
| **Tuned Hybrid (Ours)** | **96.22%** ✅ |
| Base Paper (Fahim et al., 2024) | 93.00% |

## 📌 Our Approach
Hybrid Ensemble: LR-Liblinear + Mini-Batch K-Means + Fine-tuned XGBoost  
**Outperforms base paper by +3.22%**

## 📊 Dataset
- 50,000 samples (Kaggle)
- Binary classification: Humor / Non-Humor
- Balanced 50/50

## 🛠️ Tools & Technologies
Python, Scikit-learn, PyTorch, HuggingFace Transformers, XGBoost, Google Colab

## 👨‍💻 Author
Shakhi sultana — CSE 28th Batch, PCIU  
Supervisor: Farzina Akther
