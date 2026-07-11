# Laporan Akhir UAS - Komputasi Cerdas / AI

**Nama:** Fauziah Zaenudin  
**NIM:** 2406061  

## 1. Judul Proyek
Prediksi Tingkat Obesitas Berdasarkan Kebiasaan Makan dan Kondisi Fisik Menggunakan Algoritma Decision Tree dan Naive Bayes.

## 2. Business Understanding
* **Permasalahan:** Meningkatnya angka obesitas di masyarakat yang memicu berbagai penyakit kronis. Diperlukan sistem cerdas yang mampu memprediksi tingkat risiko obesitas seseorang secara dini.
* **Tujuan Proyek:** Membandingkan performa algoritma Machine Learning untuk mendapatkan model prediksi terbaik.
* **Sektor Pengguna:** Praktisi kesehatan, dokter gizi, atau masyarakat umum.

## 3. Data Understanding
* **Sumber Data:** Dataset dari Kaggle ("Estimation of Obesity Levels Based on Eating Habits and Physical Condition").
* **Deskripsi Fitur:** Kolom mencakup umur (`Age`), jenis kelamin (`Gender`), tinggi (`Height`), berat (`Weight`), riwayat keluarga (`family_history_with_overweight`), dll.
* **Target Klasifikasi:** `NObeyesdad` (Tingkat Obesitas).

## 4. Hasil Analisis Visualisasi (EDA) & Data Preparation
* Dataset telah diperiksa dan bebas dari data kosong (*missing values*).
* Semua fitur kategorikal (teks) telah diubah menjadi numerik menggunakan `LabelEncoder`.
* Skala data numerik telah disamakan menggunakan `StandardScaler` dan dibagi menjadi **80% Data Training** dan **20% Data Testing**.

## 5. Hasil Evaluasi & Perbandingan Model
Model dievaluasi menggunakan metrik Akurasi (*Accuracy Score*) dengan hasil sebagai berikut:

* **Algoritma Decision Tree:** [ISI ANGKA PERSENNYA DARI COLAB]%
* **Algoritma Naive Bayes:** [ISI ANGKA PERSENNYA DARI COLAB]%

## 6. Kesimpulan
Berdasarkan hasil uji coba, algoritma **[Sebutkan yang akurasinya lebih tinggi, misal: Decision Tree]** memiliki performa yang lebih baik dan lebih akurat dalam memprediksi tingkat obesitas pada dataset ini dibandingkan dengan algoritma **[Sebutkan yang lebih rendah]**.
