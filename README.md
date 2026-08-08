# Portofolio Pengantar Data Science - Universitas Siber Asia

Selamat datang di repositori portofolio data science saya. Repositori ini disusun sebagai pemenuhan komponen pada mata kuliah Pengantar Data Science (IF405). Di dalamnya terdapat dokumentasi lengkap pipeline pengolahan data end-to-end dari Pertemuan 1 hingga Pertemuan 13 berdasarkan kerangka kerja industri CRISP-DM.

---

## Profil Mahasiswa
*   **Nama Lengkap:** Kafka Syahrial
*   **NIM:** 240401010045
*   **Kelas:** IF405
*   **Program Studi:** PJJ Informatika
*   **Institusi:** Universitas Siber Asia  

---

## Deskripsi Portofolio & Eksplorasi Data
Portofolio ini mendokumentasikan kapabilitas teknis saya dalam mengolah data mentah menjadi wawasan (*insight*) terukur yang siap pakai untuk kebutuhan bisnis maupun pemodelan prediktif. Proyek yang dikerjakan di dalam repositori ini mencakup:

1.  **Analisis Karakteristik Data Berlian (Dataset Diamonds):** Melakukan analisis data eksploratif (EDA) menggunakan *library* `Seaborn` dan `Matplotlib` untuk melihat persebaran harga berlian serta membandingkan variasi harganya berdasarkan tingkat kualitas potongan (`cut`) menggunakan visualisasi histogram dan *boxplot*.
2.  **Pra-pemrosesan Data Penumpang Kapal Titanic:** Melakukan integrasi data dan pembersihan data (*data cleansing*) tingkat lanjut. Tahapan ini meliputi penanganan *missing values* pada usia menggunakan nilai *median* dan pelabuhan keberangkatan menggunakan *modus*, transformasi fitur kategorikal melalui teknik *One-Hot Encoding* (`pd.get_dummies`), pemisahan data train-test secara *stratified*, hingga standardisasi skala numerik menggunakan `StandardScaler` untuk menghindari terjadinya kebocoran data (*data leakage*).
3.  **Pemodelan Prediktif Gaji Karyawan (Linear Regression):** Membangun dan mengevaluasi model Regresi Linear Sederhana untuk memprediksi besaran Gaji berdasarkan Pengalaman Kerja.

---

## Hasil Analisis & Evaluasi Model

Berdasarkan hasil pengujian pada proyek akhir Regresi Linear (Modul 7), model yang dibangun berhasil memenuhi asumsi linearitas dan homoskedastisitas dengan performa metrik evaluasi sebagai berikut:
*   **R-Squared ($R^2$):** **0.970** (Model mampu menjelaskan 97% variasi nilai Gaji berdasarkan variabel Pengalaman Kerja, mengindikasikan tingkat akurasi prediksi yang sangat tinggi).
*   **Mean Absolute Error (MAE):** **1.258** (Rata-rata kesalahan prediksi model meleset sekitar 1,25 unit nilai dari data aktual).
*   **Root Mean Squared Error (RMSE):** **1.562**.
*   **Analisis Grafik:** Evaluasi melalui *Residual Plot* menunjukkan sebaran sisa error yang acak dan merata di sekitar garis horizontal nol, membuktikan bahwa model regresi ini valid, stabil, dan bebas dari bias.

---

## Daftar Pertemuan & Topik Praktikum

Berikut adalah daftar indeks notebook praktikum beserta tautan langsung untuk membukanya:

| Pertemuan | Topik Utama & Hasil Analisis | Tautan Notebook |
| :--- | :--- | :--- |
| **Pertemuan 1** | Pengenalan Python Dasar & Ekosistem Google Colab | [Buka Notebook](./Pertemuan1_KafkaSyahrial_[240401010045].ipynb) |
| **Pertemuan 2** | Manipulasi Data & Agregasi menggunakan NumPy & Pandas | [Buka Notebook](./Pertemuan2_KafkaSyahrial_[240401010045].ipynb) |
| **Pertemuan 3** | Data Cleansing & Integrasi Data Fetching dari REST API Publik | [Buka Notebook](./Pertemuan3_KafkaSyahrial_[240401010045].ipynb) |
| **Pertemuan 4** | Statistik Deskriptif, Distribusi (Histogram + KDE Iris Dataset) | [Buka Notebook](./Pertemuan4_KafkaSyahrial_[240401010045].ipynb) |
| **Pertemuan 5** | Visualisasi Data Eksploratori (EDA) Diamonds dengan Seaborn & Matplotlib | [Buka Notebook](./Pertemuan5_KafkaSyahrial_[240401010045].ipynb) |
| **Pertemuan 6** | Preprocessing Data: Handling Missing Values, Encoding & Scaling Titanic | [Buka Notebook](./Pertemuan6_KafkaSyahrial_[240401010045].ipynb) |
| **Pertemuan 7** | Pengantar Machine Learning: Pemodelan & Evaluasi Regresi Linear Gaji | [Buka Notebook](./Pertemuan7_KafkaSyahrial_[240401010045].ipynb) |
| **Pertemuan 9**  | Klasifikasi: Logistic Regression, Decision Tree, Confusion Matrix, Precision/Recall/F1 (Breast Cancer) | [Buka Notebook](https://github.com/Kafkasyahrial/data-science-2026/blob/main/Pertemuan9_KafkaSyahrial_%5B240401010045%5D.ipynb) |
| **Pertemuan 10** | Ensemble Method (Random Forest) & Imbalanced Dataset — Customer Churn Prediction | [Buka Notebook](https://github.com/Kafkasyahrial/data-science-2026/blob/main/Pertemuan10_KafkaSyahrial_%5B240401010045%5D.ipynb) |
| **Pertemuan 11** | Unsupervised Learning: K-Means, Hierarchical Clustering, Metode Elbow | [Buka Notebook](https://github.com/Kafkasyahrial/data-science-2026/blob/main/Pertemuan11_KafkaSyahrial_%5B240401010045%5D.ipynb) |
| **Pertemuan 12** | Asosiasi Data (Algoritma Apriori) & Sistem Rekomendasi Dasar | [Buka Notebook](https://github.com/Kafkasyahrial/data-science-2026/blob/main/Pertemuan12_KafkaSyahrial_%5B240401010045%5D.ipynb) |
| **Pertemuan 13** | Pengantar Deep Learning & NLP Dasar: ANN dan TF-IDF untuk Analisis Sentimen | [Buka Notebook](https://github.com/Kafkasyahrial/data-science-2026/blob/main/Pertemuan13_KafkaSyahrial_%5B240401010045%5D.ipynb) |

---

## Tools & Library yang Digunakan
Seluruh proyek praktikum ini dibangun menggunakan ekosistem modern *open-source* Data Science berbasis Python:
*   **Bahasa Pemrograman:** Python 3
*   **Manipulasi Data:** Pandas (DataFrame & Series), NumPy (Ndarray Vektor)
*   **Komputasi & Uji Statistik:** SciPy (Stats modules)
*   **Visualisasi Data:** Matplotlib (Figure/Axes kustom), Seaborn (Statistik visual)
*   **Machine Learning:** Scikit-Learn (`LinearRegression`, `StandardScaler`, `OneHotEncoder`, `train_test_split`)
*   **Ekstraksi Data:** Requests API, JSON library

---

## Cara Menjalankan Notebook

Anda dapat menjalankan seluruh berkas analisis ini dengan dua cara alternatif:

### Opsi 1: Menggunakan Google Colab (Direkomendasikan)
1.  Buka salah satu berkas notebook `.ipynb` di atas.
2.  Unduh file `.ipynb` tersebut dan unggah secara manual ke [Google Colab](https://colab.research.google.com).
3.  Jalankan sel kode secara berurutan menggunakan kombinasi tombol `Ctrl + Enter`.

### Opsi 2: Eksekusi Lokal (Jupyter Notebook / VS Code)
1.  Kloning repositori ini ke komputer lokal Anda:
```bash
    git clone [https://github.com/Kafkasyahrial/data-science-2026.git](https://github.com/Kafkasyahrial/data-science-2026.git)
    ```
2.  Pastikan Anda telah menginstal pustaka yang dibutuhkan:
```bash
    pip install numpy pandas matplotlib seaborn scikit-learn scipy requests missingno
    ```
3.  Jalankan server Jupyter di terminal lokal Anda:
```bash
    jupyter notebook
    ```

---
## Kesimpulan Umum Perjalanan Belajar (Pertemuan 1–13)

Perjalanan belajar intensif selama tiga belas pertemuan ini memberikan pemahaman mendalam mengenai siklus hidup proyek data science yang terstruktur secara end-to-end, mulai dari fondasi kerangka kerja CRISP-DM (Pertemuan 1-7) hingga penerapan algoritma Machine Learning dan Deep Learning tingkat lanjut (Pertemuan 9-13).

Pada tahap awal, saya dilatih membersihkan anomali data mentah, melakukan eksplorasi statistik, hingga rekayasa fitur (*encoding* dan *scaling*), yang dipuncaki dengan pemodelan Regresi Linear berakurasi 97% untuk memprediksi target kontinu.

Pada tahap lanjutan, cakupan belajar meluas ke masalah klasifikasi menggunakan Logistic Regression, Decision Tree, dan Random Forest, termasuk penanganan data tidak seimbang (*imbalanced dataset*) pada kasus Customer Churn Prediction. Saya juga mempelajari teknik Unsupervised Learning (K-Means dan Hierarchical Clustering) untuk segmentasi data tanpa label, Algoritma Apriori untuk analisis asosiasi produk (Market Basket Analysis), serta pengantar Deep Learning melalui Artificial Neural Network dan pemrosesan teks (TF-IDF) untuk analisis sentimen.

Kompetensi portofolio ini membentuk pondasi yang komprehensif — mencakup pemodelan prediktif, klasifikasi, clustering, sistem rekomendasi, hingga dasar-dasar NLP — bagi saya untuk menerapkan solusi berbasis data dalam memecahkan masalah nyata di masa depan.
