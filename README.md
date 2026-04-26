# Proyek Akhir: Matematika untuk Data Science

[![Dicoding Submission](https://img.shields.io/badge/Dicoding-Submission-blue)](https://www.dicoding.com/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-green)](https://www.python.org/)

## 📋 Profil Proyek
* **Username Dicoding:** fahmi fadillah30
* **Waktu Pengerjaan:** April 2026
* **Tugas Akhir:** Belajara Matematika Untuk Data Science

---

## 📌 Deskripsi
Proyek ini merupakan implementasi mendalam dari prinsip-prinsip matematika yang menjadi fondasi algoritma Machine Learning dan analisis data. Fokus utama terletak pada pembangunan model klasifikasi secara manual (*from scratch*) dan validasi fitur melalui eksperimen A/B Testing yang ketat.

## 📊 Studi Kasus dan Implementasi

### 1. Klasifikasi Spesies Burung (Naive Bayes From Scratch)
Membangun model prediksi jenis burung berdasarkan fitur morfologi dengan menerapkan **Teorema Bayes**. Proyek ini menekankan pada pemilihan distribusi yang tepat untuk setiap jenis fitur:

* **Gaussian Distribution**: Digunakan untuk variabel kontinu seperti berat badan (`weight_g`) dan rentang sayap (`wingspan_cm`).
* **Binomial Distribution**: Digunakan untuk variabel diskrit berupa frekuensi kejadian, yaitu hari berkicau (`sing_days`).
* **Uniform Distribution**: Digunakan untuk rasio fisik tertentu seperti paruh-kepala (`beak_head_ratio`).



### 2. A/B Testing: Optimalisasi Sistem Rekomendasi
Menganalisis efektivitas algoritma rekomendasi artikel terhadap keterlibatan (*engagement*) pengguna.
* **Metodologi**: Menggunakan **Welch's t-test** untuk menangani dua populasi dengan varians yang berbeda (*unequal variance*).
* **Pemodelan**: Data frekuensi bacaan dimodelkan dengan **Distribusi Poisson**.
* **Parameter**: Menghitung *t-statistic*, *degrees of freedom* (Satterthwaite approximation), dan *p-value*.



### 3. A/B Testing: Retensi Pengguna pada Software Dev
Validasi fitur baru untuk meningkatkan *conversion rate* menggunakan statistik inferensial.
* **Power Analysis**: Menentukan ukuran sampel minimum untuk menghindari kesalahan Tipe II ($\beta$).
* **Uji Hipotesis**: Implementasi **Z-test untuk Dua Proporsi** guna membandingkan tingkat retensi antara kelompok kontrol dan varian.
* **Eksperimen**: Estimasi durasi pengujian berdasarkan trafik harian untuk efisiensi bisnis.



---

## ⚙️ Tahapan Eksekusi
1.  **Analisis Distribusi**: Mengidentifikasi jenis data (diskrit vs kontinu) dan mengestimasi parameter ($\mu, \sigma, \lambda$).
2.  **Uji Hipotesis**: Merumuskan $H_0$ (Hipotesis Nol) dan $H_1$ (Hipotesis Alternatif) dengan tingkat signifikansi $\alpha = 0.05$.
3.  **Evaluasi**: Menghitung skor akurasi untuk model klasifikasi dan menentukan signifikansi statistik untuk hasil A/B Test.

## 📦 Requirements
Proyek ini dikembangkan menggunakan stack berikut:
* `numpy` & `pandas`: Manipulasi data dan komputasi array.
* `scipy.stats`: Perhitungan distribusi probabilitas dan uji statistik.
* `matplotlib` & `seaborn`: Visualisasi distribusi data.
* `sklearn.metrics`: Evaluasi performa model.

---

## ✨ Penutup
Proyek ini menunjukkan bahwa penguasaan matematika dasar sangat krusial dalam memahami bagaimana sebuah model bekerja di balik layar, serta memastikan kesimpulan yang diambil dari sebuah data bersifat valid dan dapat dipertanggungjawabkan secara ilmiah.

---
© 2026 fahmi fadillah30. All Rights Reserved.