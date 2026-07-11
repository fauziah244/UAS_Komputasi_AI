# UAS Kecerdasan Buatan - Estimasi Tingkat Obesitas

**Nama:** Fauziah Zaenudin  
**NIM:** 2406061  

Repositori ini dibuat untuk memenuhi tugas UAS mata kuliah Kecerdasan Buatan / Komputasi Cerdas menggunakan algoritma Machine Learning.

## 📁 Struktur Repositori
* `Data/Dataset/` : Berisi file dataset mentah berbentuk `.csv`.
* `Data/Jurnal/` : Berisi dokumen teks berisi minimal 5 referensi jurnal ilmiah terkait.
* `uas_model.ipynb` : File notebook kodingan pemodelan (Decision Tree & Naive Bayes).
* `Laporan_uas.md` : Dokumen laporan akhir komplit dari bab 1 sampai bab 9.

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
