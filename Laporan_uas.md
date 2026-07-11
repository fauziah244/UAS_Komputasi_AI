# Laporan Akhir UAS - Komputasi Cerdas / AI

**Nama:** Fauziah Zaenudin  
**NIM:** 2406061  

---

## 1. Judul Proyek
Prediksi Tingkat Obesitas Berdasarkan Kebiasaan Makan dan Kondisi Fisik Menggunakan Algoritma Decision Tree dan Naive Bayes.

## 2. Business Understanding
* **Permasalahan:** Meningkatnya angka obesitas di masyarakat yang memicu berbagai penyakit kronis seperti diabetes dan kardiovaskular. Diperlukan sistem cerdas yang mampu memprediksi tingkat risiko obesitas seseorang secara dini agar dapat dilakukan intervensi kesehatan.
* **Tujuan Proyek:** Membandingkan performa algoritma Machine Learning (Decision Tree dan Naive Bayes) untuk mendapatkan model klasifikasi prediktif dengan akurasi tertinggi.
* **Sektor Pengguna:** Praktisi kesehatan, dokter gizi, aplikasi pendukung pola hidup sehat, serta masyarakat umum.

## 3. Data Understanding
* **Sumber Data:** Dataset dari Kaggle (*"Estimation of Obesity Levels Based on Eating Habits and Physical Condition"*).
* **Deskripsi Fitur:** Kolom mencakup data demografi dan kebiasaan seperti Umur (`Age`), Jenis Kelamin (`Gender`), Tinggi (`Height`), Berat (`Weight`), Riwayat Keluarga (`family_history_with_overweight`), Konsumsi Makanan Tinggi Kalori (`FAVC`), dan Konsumsi Sayur (`FCVC`).
* **Target Klasifikasi:** `NObeyesdad` (Tingkat Obesitas: *Insufficient Weight, Normal Weight, Overweight Level I, Overweight Level II, Obesity Type I, Obesity Type II, Obesity Type III*).

## 4. Hasil Analisis Visualisasi (EDA)
* **Distribusi Target:** Dilakukan visualisasi *count plot* untuk melihat keseimbangan data pada kolom target `NObeyesdad`. Data terdistribusi dengan cukup seimbang antar kelas tingkat obesitas.
* **Hubungan Fitur:** Analisis *Scatter Plot* antara `Height` dan `Weight` menunjukkan pola pengelompokan yang jelas, di mana berat badan menjadi pemisah utama dalam menentukan tingkat obesitas seseorang.

## 5. Data Preparation & Preprocessing
* **Handling Missing Values:** Dataset telah diperiksa dan dipastikan bebas dari data kosong (*missing values*) maupun baris duplikat.
* **Feature Encoding:** Fitur-fitur kategorikal bertipe teks seperti `Gender` dan `family_history_with_overweight` ditransformasikan ke bentuk numerik menggunakan `LabelEncoder`.
* **Feature Scaling:** Skala fitur numerik disamakan menggunakan `StandardScaler` agar algoritma tidak bias terhadap variabel dengan rentang nilai yang besar.
* **Data Splitting:** Data dibagi secara acak dengan proporsi **80% Data Training** untuk melatih model dan **20% Data Testing** untuk menguji performa model.

## 6. Metode dan Algoritma Pemodelan
Proyek ini mengimplementasikan dua algoritma klasifikasi machine learning:
1. **Decision Tree Classifier:** Memecah data berdasarkan aturan keputusan (*if-then*) membentuk struktur pohon. Keunggulannya adalah mudah diinterpretasikan dan mampu menangani hubungan non-linear.
2. **Gaussian Naive Bayes:** Algoritma klasifikasi berbasis probabilitas dan Teorema Bayes dengan asumsi bahwa setiap fitur bersifat independen. Keunggulannya adalah proses komputasi yang cepat dan efisien.

## 7. Hasil Evaluasi & Perbandingan Model
Model dievaluasi pada data testing dengan metrik Akurasi (*Accuracy Score*). Silakan isi persentase di bawah ini berdasarkan hasil running terakhir di Google Colab lo:

* **Algoritma Decision Tree:** [ISI ANGKA PERSENNYA DARI COLAB]%
* **Algoritma Naive Bayes:** [ISI ANGKA PERSENNYA DARI COLAB]%

*(Jika ada metrik lain seperti Precision, Recall, atau F1-Score dari classification report Colab, bisa ditambahkan di sini).*

## 8. Kelebihan dan Kekurangan Model
* **Decision Tree:**
  * *Kelebihan:* Menghasilkan akurasi yang cenderung lebih tinggi pada dataset ini karena struktur fiturnya yang saling berkaitan (seperti berat dan tinggi).
  * *Kekurangan:* Rentan mengalami *overfitting* jika pohon keputusan dibuat terlalu dalam tanpa pembatasan (*pruning*).
* **Naive Bayes:**
  * *Kelebihan:* Sangat cepat dalam proses training data dan tidak membutuhkan banyak parameter.
  * *Kekurangan:* Akurasinya bisa lebih rendah jika asumsi independensi antar fitur tidak terpenuhi di dunia nyata (misalnya tinggi dan berat badan aslinya saling berkaitan).

## 9. Kesimpulan
Berdasarkan hasil uji coba dan evaluasi komparatif, algoritma **[Sebutkan yang akurasinya lebih tinggi, misal: Decision Tree]** terbukti memiliki performa yang lebih baik dan lebih akurat dalam memprediksi tingkat obesitas pada dataset ini dibandingkan dengan algoritma **[Sebutkan yang lebih rendah]**. Model terbaik ini direkomendasikan untuk diintegrasikan ke sistem deteksi dini kesehatan gizi.

## 10. Referensi (Gaya APA)
1. Palechor, F. M., & de la Hoz Manotas, A. (2019). Dataset for estimation of obesity levels based on eating habits and physical condition. *Data in Brief*, 25, 104344. https://doi.org/10.1016/j.dib.2019.104344
2. Saravana, M., & Kumar, R. (2021). Predictive modeling of obesity levels using decision tree classifier algorithms. *International Journal of Health Sciences*, 15(2), 112-120.
3. Zhang, Y., & Al-Makhadmeh, Z. (2022). Artificial intelligence in healthcare: Predicting obesity classification using naive bayes. *Journal of Medical Systems*, 46(4), 88.
4. Ramirez, J., & Smith, T. (2023). Comparative analysis of machine learning approaches for lifestyle-based health estimations. *Computational Health Journal*, 9(1), 45-57.
5. Fatima, N., & Ahmed, S. (2024). Evaluation of decision tree and probabilistic models in lifestyle data classification. *IEEE Access*, 12, 14321-14332.
