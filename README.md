# Sentiment Analysis - E-Commerce Product Reviews (Bahasa Indonesia)

## Identitas Mahasiswa

| Field | Value |
|-------|-------|
| **Nama**  | Arif Rahmat Riski |
| **NIM**   | 24146092 |
| **Kelas** | 02 |

---

## Deskripsi Proyek

Proyek ini melakukan analisis sentimen pada dataset ulasan produk e-commerce berbahasa Indonesia menggunakan teknik **Natural Language Processing (NLP)**. Dataset bersumber dari [Hugging Face – dipawidia/ecommerce-product-reviews-sentiment](https://huggingface.co/datasets/dipawidia/ecommerce-product-reviews-sentiment).

---

## Alur Preprocessing Teks

1. **Case Folding** – Mengubah seluruh teks menjadi huruf kecil
2. **Cleaning** – Menghapus URL, angka, tanda baca, dan karakter khusus
3. **Tokenisasi** – Memisahkan teks menjadi token/kata
4. **Stopword Removal** – Menghapus kata-kata tidak penting (Bahasa Indonesia)
5. **Stemming** – Mengubah kata ke bentuk dasar menggunakan PySastrawi

---

## Struktur Repository

```
sentiment-analysis-nlp/
├── Sentiment_Analysis_ECommerce_Indonesia.ipynb   # Jupyter Notebook utama
├── README.md                                       # File ini
└── laporan_sentiment_analysis.pdf                  # Laporan PDF
```

---

## Cara Menjalankan

1. Clone repository ini:
   ```bash
   git clone https://github.com/Arifcom2203/sentiment-analysis-nlp.git
   cd sentiment-analysis-nlp
   ```

2. Install dependensi:
   ```bash
   pip install datasets pandas matplotlib seaborn nltk PySastrawi wordcloud
   ```

3. Jalankan notebook:
   ```bash
   jupyter notebook Sentiment_Analysis_ECommerce_Indonesia.ipynb
   ```

---

## Dependensi

- Python 3.8+
- `datasets` (Hugging Face)
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `nltk`
- `PySastrawi`
- `wordcloud`

---

## Dataset

- **Sumber:** [Hugging Face – dipawidia/ecommerce-product-reviews-sentiment](https://huggingface.co/datasets/dipawidia/ecommerce-product-reviews-sentiment)
- **Bahasa:** Indonesia
- **Task:** Sentiment Classification

---

*Tugas NLP – Teknik Informatika*
