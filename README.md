# Praktikum Data Science dan Machine Learning

Selamat datang di proyek analisis data dan machine learning yang dibuat dalam notebook berikut:

- `Praktikum_202431002_David Lie Agatha.ipynb`

Proyek ini berisi serangkaian eksperimen data science yang mencakup eksplorasi data, web scraping, pemodelan regresi, serta klasifikasi berbasis algoritma machine learning. Tujuan utamanya adalah memahami proses analisis data dari tahap awal hingga evaluasi model secara praktis dan sistematis.

## Ringkasan Program

Program ini mencakup beberapa bagian utama:

1. Exploratory Data Analysis (EDA)
   - Mengimport dataset `loan_prediction.csv`
   - Memeriksa struktur data, missing values, duplikasi, dan distribusi kategori
   - Melakukan pembersihan data awal sebelum analisis lanjutan

2. Web Scraping Data Inflasi
   - Mengambil data inflasi historis dari website sumber eksternal
   - Menangkap informasi tahun, tingkat inflasi Januari, dan rata-rata inflasi
   - Menyimpan hasil scraping ke file `data_scraping.csv`

3. Regresi Linear
   - Menganalisis hubungan antar variabel pada data inflasi
   - Membuat model regresi linear untuk memprediksi nilai rata-rata inflasi
   - Menilai koefisien dan intercept dari model

4. Decision Tree
   - Membangun model pohon keputusan untuk data inflasi
   - Menggunakan variabel `average` dan `year` sebagai fitur untuk memprediksi `january`
   - Menampilkan visualisasi struktur pohon keputusan

5. Naive Bayes untuk Prediksi Penyakit Jantung
   - Menggunakan dataset `heart.csv`
   - Melakukan preprocessing seperti encoding pada fitur kategorikal
   - Melatih model `GaussianNB`
   - Mengevaluasi performa model dengan confusion matrix dan classification report
   - Menguji model pada data baru untuk prediksi penyakit jantung

---

## Struktur File

```text
Laprak/
├── Praktikum_202431002_David Lie Agatha.ipynb
├── data_scraping.csv
├── heart.csv
├── inflation.csv
├── loan_prediction.csv
├── README.md
├── Laporan1&2_202431002_David Lie Agatha_Pemsin_C.pdf
└── Laporan1&2_202431002_David Lie Agatha_Pemsin_C.docx
```

### Penjelasan file utama

- `Praktikum_202431002_David Lie Agatha.ipynb`  
  Notebook utama berisi seluruh proses analisis data dan pemodelan.

- `loan_prediction.csv`  
  Dataset yang digunakan untuk analisis EDA dan proses cleaning data.

- `data_scraping.csv`  
  Hasil scraping data inflasi yang diolah menjadi dataset tabular.

- `heart.csv`  
  Dataset untuk klasifikasi penyakit jantung menggunakan Naive Bayes.

---

## Teknologi yang Digunakan

Proyek ini dibangun dengan bahasa pemrograman Python dan library utama berikut:

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Requests
- BeautifulSoup
- Jupyter Notebook

---

## Cara Menggunakan Program

### 1. Persiapan lingkungan

Pastikan Python sudah terinstal di sistem Anda. Kemudian install library yang diperlukan dengan perintah berikut:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn requests beautifulsoup4 jupyter
```

### 2. Buka notebook

Buka file berikut di Jupyter Notebook atau VS Code dengan dukungan notebook:

```text
Praktikum_202431002_David Lie Agatha.ipynb
```

### 3. Jalankan sel-sel kode

Run semua cell secara berurutan dari atas ke bawah. Setiap bagian dalam notebook dirancang untuk dijalankan secara berurutan agar hasil analisis dan model dapat terbentuk dengan benar.

### 4. Hasil yang diharapkan

Setelah seluruh sel dijalankan, Anda akan mendapatkan:

- informasi dataset dan data cleaning
- visualisasi distribusi data
- hasil scraping data inflasi
- model regresi linear
- visualisasi decision tree
- evaluasi performa model Naive Bayes
- prediksi data baru untuk kasus penyakit jantung

---

## Catatan Penting

- Pastikan file dataset berada di direktori yang sama dengan notebook agar proses pembacaan file berjalan lancar.
- Jika Anda menggunakan VS Code, disarankan untuk membuka folder proyek sebagai workspace agar semua jalur file terdeteksi dengan benar.
- Perlu diperhatikan bahwa notebook ini dibuat untuk keperluan pembelajaran dan eksperimen praktis, bukan untuk deployment aplikasi produktif.

---

## Kesimpulan

Proyek ini menunjukkan siklus lengkap dalam analisis data dan machine learning, mulai dari pengumpulan data, pembersihan data, visualisasi, pemodelan, hingga evaluasi hasil. Selain itu, proyek ini juga memperlihatkan penerapan berbagai teknik prediksi yang umum digunakan di bidang data science.

Semoga proyek ini bermanfaat sebagai referensi belajar dan pengembangan kemampuan analisis data serta machine learning.
