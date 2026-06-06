# Portofolio Pengantar Data Science - Universitas Siber Asia

Selamat datang di repositori portofolio data science saya. Repositori ini disusun sebagai pemenuhan komponen pada mata kuliah Pengantar Data Science (IF405). Di dalamnya terdapat dokumentasi lengkap pipeline pengolahan data end-to-end dari Pertemuan 1 hingga Pertemuan 7 berdasarkan kerangka kerja industri CRISP-DM.

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

## Kesimpulan Umum Perjalanan Belajar (Pertemuan 1–7)

Perjalanan belajar intensif selama tujuh pertemuan ini memberikan pemahaman mendalam mengenai siklus hidup proyek data science yang terstruktur secara end-to-end berbasis kerangka kerja CRISP-DM. Saya tidak hanya dilatih untuk menulis baris kode pemrograman, melainkan diajarkan cara berpikir analitis dalam menyusun sebuah pipeline data yang valid guna menghindari jebakan *data leakage*.

Melalui pembersihan anomali data mentah, eksplorasi statistik, hingga rekayasa fitur (*encoding* dan *scaling*), saya memahami bagaimana mempersiapkan data mentah agar siap diproses oleh algoritma matematika. Puncaknya, pada pemodelan Regresi Linear, saya berhasil membuktikan secara ilmiah bagaimana variasi data input dapat memprediksi target kontinu dengan akurasi tinggi sebesar 97%. Kompetensi portofolio ini membentuk pondasi kuat bagi saya untuk menerapkan solusi berbasis data dalam memecahkan masalah nyata di masa depan.
