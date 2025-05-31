# NLP
# Legal Document Classification Project

This repository contains code and documentation for a legal document classification project using different approaches:

## 📂 Files

- **`legal_classification.py`**: Python script that demonstrates:
  - Data loading (LexGLUE - LEDGAR dataset)
  - Preprocessing and tokenization
  - Model training and evaluation
  - Visualizations comparing BERT and classical models
- **`legal_classification_notebook.ipynb`**: Jupyter Notebook version of the above script for interactive experimentation.
- **`report.pdf`**: Detailed report comparing BERT with TF-IDF + Logistic Regression, including experiments and results.

## 📊 Models & Techniques

✅ **BERT-based model**  
Fine-tuned transformer model (bert-base-uncased) for legal document classification.

✅ **TF-IDF + Logistic Regression**  
Classical ML pipeline for quick and efficient baseline performance.

✅ **GPT-2 Prompting (Baseline)**  
Using GPT-2 text-generation for classification prompt-based baseline.

## ⚡️ Dataset
We used the **LEDGAR** subset of the LexGLUE benchmark – a collection of legal contract clauses.

## 💡 Key Results
- **BERT** achieved ~67% accuracy.
- **TF-IDF + Logistic Regression** achieved ~53% accuracy.
- BERT significantly outperforms the traditional baseline in all metrics.

## 🔧 How to Run
Clone this repo and install the dependencies:

```bash
git clone https://github.com/shams8795/NLP.git
cd NLP
pip install -r requirements.txt
