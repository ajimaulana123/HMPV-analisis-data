# Analisis Data Pasien COVID-19 (HMPV)

Proyek ini bertujuan untuk melakukan analisis dan pembersihan data terkait pasien COVID-19 menggunakan teknik data wrangling, eksplorasi data (EDA), visualisasi, dan analisis lanjutan. Data yang digunakan adalah data dummy pasien COVID-19, dan proses analisis akan memfokuskan pada pembersihan data, pengisian nilai yang hilang, serta menggali wawasan untuk mendukung pengambilan keputusan berbasis data.

## Fitur (On Going)

1. **Pembersihan Data (Data Cleaning)**: Mengidentifikasi dan menangani nilai yang hilang (missing values), duplikasi, dan kesalahan tipe data.
2. **Eksplorasi Data (EDA)**: Menganalisis dan menggambarkan statistik deskriptif data.
3. **Visualisasi Data**: Membuat grafik untuk membantu memahami distribusi dan hubungan antar variabel.
4. **Analisis Lanjutan**: Melakukan analisis lebih dalam untuk menggali wawasan yang relevan terkait faktor-faktor yang mempengaruhi hasil pasien COVID-19.
5. **Pemodelan Imputasi**: Menggunakan teknik-teknik imputasi untuk menangani missing values, seperti SimpleImputer dan KNNImputer.

## Teknologi yang Digunakan

- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- **Jupyter Notebook** untuk analisis interaktif
- **Matplotlib** dan **Seaborn** untuk visualisasi data
- **Scikit-learn** untuk teknik imputasi dan analisis lanjutan

## Cara Penggunaan

### Instalasi

Untuk menjalankan proyek ini di mesin lokal Anda, pastikan Anda memiliki Python versi 3.x dan pip terinstal. Kemudian, buat virtual environment dan instal semua dependensi yang diperlukan menggunakan file `requirements.txt`.

1. Clone repository ini:
   ```bash
   git clone https://github.com/username/repository.git
   cd repository
   ```

2. Buat virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate  # Untuk pengguna macOS/Linux
   env\Scripts\activate     # Untuk pengguna Windows
   ```

3. Instal dependensi:
   ```bash
   pip install -r requirements.txt
   ```

4. Buka file Jupyter Notebook untuk mulai analisis:
   ```bash
   jupyter notebook
   ```

### Struktur Folder (Coming Soon)

```
.
├── data/
│   └── covid19_patients_data.csv   # Data dummy pasien COVID-19
├── notebooks/
│   └── analysis_notebook.ipynb     # Notebook untuk analisis dan eksplorasi data
├── requirements.txt               # File dependensi Python
└── README.md                      # Dokumentasi proyek ini
```

### Proses Analisis

1. **Data Wrangling**:
   - Cek tipe data dan lakukan konversi jika diperlukan.
   - Periksa duplikasi dan nilai yang hilang, serta tangani missing values menggunakan teknik imputasi.
   - Bersihkan dan normalisasi data agar siap untuk analisis lebih lanjut.

2. **Eksplorasi Data (EDA)**: (On Going)
   - Hitung statistik deskriptif untuk setiap kolom numerik.
   - Visualisasikan distribusi data menggunakan histogram, box plot, dan grafik lainnya.
   - Identifikasi hubungan antar fitur menggunakan grafik scatter plot atau heatmap.

3. **Imputasi Missing Values**: (On Going)
   - Gunakan teknik imputasi seperti **SimpleImputer** (rata-rata, median, modus) dan **KNNImputer** untuk mengisi missing values.
   - Terapkan model prediktif atau imputasi berbasis algoritma untuk data yang lebih kompleks.

4. **Analisis Lanjutan**: (Coming Soon)
   - Melakukan analisis korelasi antara berbagai faktor (usia, durasi rawat, vaksinasi, dll.) terhadap hasil pasien (kematian, kesembuhan).
   - Lakukan analisis regresi atau model prediksi untuk menggali lebih dalam faktor-faktor yang mempengaruhi hasil COVID-19.

5. **Visualisasi**: (Coming Soon)
   - Visualisasikan hasil analisis menggunakan **Matplotlib** dan **Seaborn** untuk memahami tren, distribusi, dan hubungan antar variabel.
   - Buat dashboard atau visualisasi interaktif jika diperlukan.

## Insight Bisnis (Coming Soon)

Beberapa wawasan yang dapat diperoleh dari proyek ini termasuk:
- Faktor usia dan jenis kelamin memiliki pengaruh signifikan terhadap tingkat kesembuhan atau kematian pasien COVID-19.
- Durasi rawat inap dapat mempengaruhi tingkat kematian dan sembuh.
- Pentingnya vaksinasi dalam mengurangi kemungkinan kematian.
- Pemeriksaan yang lebih awal dan durasi tes dapat meningkatkan tingkat kesembuhan pasien.

## Pertanyaan Bisnis (Coming Soon)

Beberapa pertanyaan bisnis yang dapat digali dari analisis ini:
1. Apa faktor utama yang mempengaruhi tingkat kesembuhan pasien COVID-19?
2. Bagaimana pengaruh vaksinasi terhadap hasil pasien?
3. Apakah durasi rawat inap terkait dengan tingkat kematian atau kesembuhan?
4. Bagaimana kebijakan pemeriksaan dini dapat mengurangi tingkat kematian COVID-19?
5. Bagaimana pengaruh usia terhadap hasil pasien dalam kasus COVID-19?

## Referensi 

- [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)

## Kontribusi

Jika Anda ingin berkontribusi pada proyek ini, silakan lakukan fork dari repository ini dan kirimkan pull request dengan perubahan Anda. Pastikan untuk menambahkan deskripsi yang jelas mengenai kontribusi yang Anda buat.

---

Terima kasih telah menggunakan proyek ini! Semoga bermanfaat untuk analisis data COVID-19 yang lebih baik.
