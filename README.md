# Proyek Akhir: Belajar Matematika untuk Data Science

## Proyek Studi Math For Data Science
Username Dicoding : fahmi fadillah30
April 2026

Proyek ini dibuat untuk memenuhi submission **Dicoding: Matematika untuk Data Science**. Proyek ini berfokus pada penerapan prinsip-prinsip **Probabilitas dan Statistika** dalam penyelesaian masalah Data Science, mencakup distribusi probabilitas, algoritma Naive Bayes, dan A/B Testing.

---

## 📊 Soal dan Studi Kasus

Proyek ini terdiri dari tiga bagian utama yang masing-masing menyelesaikan permasalahan spesifik menggunakan pendekatan statistik.

### 1. Distribusi Probabilitas & Algoritma Naive Bayes
**File**: `soal_1_distribusi_dan_algoritma_naive_bayes.py`

* **Deskripsi**: Membangun model klasifikasi Naive Bayes dari nol (scratch) untuk memprediksi jenis burung.
* **Fitur Utama**:
  * **Generasi Data Sintetis**: Membuat data dummy yang mengikuti distribusi tertentu (Gaussian, Binomial, Uniform).
  * **Implementasi Distribusi**:
    * Gaussian: Berat badan (`weight_g`), Rentang sayap (`wingspan_cm`)
    * Binomial: Hari berkicau (`sing_days`)
    * Uniform: Rasio paruh-kepala (`beak_head_ratio`)
  * **Klasifikasi Naive Bayes**: Menghitung *Posterior Probability* menggunakan *Prior* dan *Likelihood* dari distribusi yang sesuai.

### 2. A/B Testing: Sistem Rekomendasi
**File**: `soal_2_sistem_rekomendasi_ab.py`

* **Deskripsi**: Mengevaluasi efektivitas fitur rekomendasi artikel baru terhadap jumlah artikel yang dibaca pengguna.
* **Metode**:
  * Menggunakan **Two-Sample t-test** (Welch's t-test).
  * Data dimodelkan menggunakan distribusi Poisson.
  * Menghitung t-statistic, degree of freedom (Satterthwaite), dan p-value untuk pengambilan keputusan.

### 3. A/B Testing: Software Development
**File**: `soal_3_software_dev_ab.py`

* **Deskripsi**: Menentukan apakah fitur baru dalam aplikasi berhasil meningkatkan *retention rate* (conversion rate).
* **Metode**:
  * **Power Analysis**: Menghitung ukuran sampel minimum (`sample_size`) yang dibutuhkan untuk mendeteksi dampak fitur.
  * **Z-test untuk Dua Proporsi**: Menguji perbedaan proporsi keberhasilan (konversi) antara kelompok kontrol dan varian.
  * Menghitung durasi eksperimen yang dibutuhkan berdasarkan traffic harian.

---

## ⚙️ Tahapan & Implementasi

1.  **Analisis & Pemodelan Data** 🔬
    *   Mengidentifikasi jenis distribusi data (Diskrit/Kontinu).
    *   Estimasi parameter distribusi ($\mu, \sigma, p$, dll) dari data training.

2.  **Uji Hipotesis** 🧪
    *   Merumuskan Hipotesis Nol ($H_0$) dan Alternatif ($H_1$).
    *   Menghitung statistik uji (t-score, z-score).
    *   Mengambil keputusan berdasarkan *p-value* dan tingkat signifikansi ($\alpha$).

3.  **Evaluasi Model** 📈
    *   Mengukur akurasi prediksi model Naive Bayes.
    *   Menentukan signifikansi statistik dari hasil eksperimen A/B testing.

---

## 📦 Requirements

Proyek ini dikembangkan menggunakan Python dengan library berikut:
*   `numpy`: Komputasi numerik & array.
*   `pandas`: Manipulasi & analisis data tabular.
*   `matplotlib` & `seaborn`: Visualisasi data.
*   `scipy`: Fungsi-fungsi statistik ilmiah (stats, special).
*   `sklearn` (Scikit-learn): Metrik evaluasi model.

---

## ✨ Penutup

Submission ini mendemonstrasikan kemampuan fundamental dalam menerapkan matematika—khususnya probabilitas dan statistika—sebagai fondasi utama algoritma Machine Learning dan pengambilan keputusan berbasis data (Data-Driven Decision Making).

Semoga bermanfaat! 🙌
