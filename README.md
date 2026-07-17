# UAS Kecerdasan Buatan - Estimasi Tingkat Obesitas

**Nama:** Fauziah Zaenudin  
**NIM:** 2406061  

## Deskripsi Proyek
Proyek ini dibuat untuk memenuhi tugas UAS mata kuliah Kecerdasan Buatan.
Prediksi Tingkat Obesitas Menggunakan Algoritma Decision Tree dan Naive Bayes
Proyek ini bertujuan untuk memprediksi tingkat obesitas berdasarkan karakteristik individu dan gaya hidup menggunakan metode machine learning. Dataset diperoleh dari Kaggle dan diproses melalui tahapan Business Understanding, Data Understanding, EDA, Data Preparation, Modeling, dan Evaluation. Model yang digunakan adalah Decision Tree dan Naive Bayes, kemudian dibandingkan menggunakan metrik Accuracy, Precision, Recall, dan F1-Score untuk menentukan model terbaik.

### Algoritma yang Digunakan

* Decision Tree
* Naive Bayes

## 📁 Struktur Repositori
```text
UAS-KecerdasanBuatan/
├── README.md
├── Laporan_uas.md
├── uas_model.ipynb
└── data/
    ├── dataset/
    │   └── obesity.csv
    └── Jurnal/
        ├── jurnal_1.pdf
        ├── jurnal_2.pdf
        ├── jurnal_3.pdf
        ├── jurnal_4.pdf
        └── jurnal_5.pdf
```

## 🛠️ Penjelasan Langkah Pengerjaan
1. **Business & Data Understanding:** Mengidentifikasi masalah tingkat obesitas dan mengunduh dataset resmi dari Kaggle.
2. **Exploratory Data Analysis (EDA):** Memeriksa kualitas data, visualisasi korelasi antar-fitur (*heatmap*), serta deteksi data tidak seimbang (*imbalanced classes*).
3. **Data Preparation:** 
   * Melakukan pembersihan data (*handling missing values* & duplikat).
   * Mengubah data teks kategorikal menjadi numerik menggunakan `LabelEncoder`.
   * Melakukan normalisasi skala data numerik menggunakan `StandardScaler`.
   * Membagi proporsi data menjadi **80% Training Data** dan **20% Testing Data**.
4. **Modeling & Evaluation:** Melatih dataset menggunakan minimal 2 algoritma yaitu **Decision Tree** dan **Naive Bayes**, lalu mengukur performanya menggunakan metrik *Accuracy*, *Precision*, *Recall*, dan *F1-score*.
5. **Penyusunan Laporan:** Merangkum seluruh hasil evaluasi dan referensi jurnal ilmiah ke dalam file Markdown di GitHub.
