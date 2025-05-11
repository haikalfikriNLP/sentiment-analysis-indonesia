# Sentimen Analisis Indonesia – Twitter Dataset

Repositori ini merupakan bagian dari portofolio analisis sentimen menggunakan data Twitter berbahasa Indonesia. Proyek ini mencakup tahap preprocessing teks, pelabelan sentimen otomatis menggunakan VADER, dan evaluasi beberapa algoritma klasifikasi serta pendekatan hybrid model.

## 📁 Struktur Proyek

```
sentiment-analysis-indonesia/
├── README.md
├── requirements.txt
├── data/
│   └── labeling_vader.csv
├── notebooks/
│   ├── A1 Preprocessing Sentiment Analysis.ipynb
│   └── A1 Perbandingan Model dan Hybrid Model.ipynb
└── src/
    └── (opsional: utils.py atau modul preprocessing/model)
```

## 📝 Deskripsi Notebook

- **A1 Preprocessing Sentiment Analysis.ipynb**  
  Melakukan pembersihan teks, tokenisasi, stopword removal, dan pelabelan otomatis menggunakan VADER untuk membentuk dataset sentimen.

- **A1 Perbandingan Model dan Hybrid Model.ipynb**  
  Menggunakan dataset hasil preprocessing untuk membandingkan beberapa model:
  - Naive Bayes
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
  - Neural Network (2 hidden layer)
  - Hybrid model (gabungan beberapa prediksi)

## ⚙️ Tools dan Library

- Python
- Scikit-learn
- Pandas
- NumPy
- NLTK
- VADERSentiment
- Keras / TensorFlow

## 📊 Evaluasi Model
Model dievaluasi menggunakan:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## 📦 Instalasi

Clone repositori dan install dependensi:
```bash
git clone https://github.com/haikalfikriNLP/sentiment-analysis-indonesia.git
cd sentiment-analysis-indonesia
pip install -r requirements.txt
```

## 🧪 Cara Menjalankan

1. Jalankan `A1 Preprocessing Sentiment Analysis.ipynb` untuk membuat dataset.
2. Gunakan hasil `.csv` untuk menjalankan `A1 Perbandingan Model dan Hybrid Model.ipynb`.

## 👨‍💻 Author

**Haikal Fikri**  
GitHub: [@haikalfikriNLP](https://github.com/haikalfikriNLP)