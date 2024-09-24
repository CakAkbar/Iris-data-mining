# Eksperimen Penambangan Data Iris

## Daftar Isi

1. [Memahami Data](#memahami-data)
   - [Pengertian Bunga Iris](#pengertian-bunga-iris)
2. [Pembersihan Data dan Pra-pemrosesan](#pembersihan-data-dan-pra-pemrosesan)
   - [Penanganan Missing Value](#penanganan-missing-value)
   - [Deteksi Outlier](#deteksi-outlier)
3. [Implementasi Naive Bayes](#implementasi-naive-bayes)


### Pengertian Bunga Iris

Dataset Iris adalah dataset klasik yang digunakan dalam pembelajaran mesin untuk klasifikasi spesies bunga iris berdasarkan empat fitur: panjang sepal, lebar sepal, panjang petal, dan lebar petal. Dataset ini mencakup tiga spesies: Iris Setosa, Iris Versicolor, dan Iris Virginica.

## Pembersihan Data dan Pra-pemrosesan

### Penanganan Missing Value

1. **Percobaan Melakukan Missing Value**: Identifikasi dan tangani nilai hilang dalam dataset.
   - **Menghapus Baris**: Menghapus baris yang memiliki missing value.
   - **Menampilkan Fitur dengan Missing Value**: Melihat fitur-fitur yang memiliki nilai hilang.

2. **Metode Penanganan Missing Value**:
   - **Metode Nilai Rata-rata (Mean)**: Mengisi missing value dengan nilai rata-rata fitur tersebut.
   - **Metode K Nearest Neighbour (KNN)**: Mengisi missing value menggunakan nilai dari tetangga terdekat berdasarkan fitur yang ada.

### Deteksi Outlier

1. **Teori Local Outlier Factor (LOF)**: LOF adalah teknik untuk mendeteksi data yang tidak biasa atau outlier dalam dataset.
2. **Menghitung LOF Manual dan Menggunakan Python**:
   - **Manual**: Menghitung LOF secara manual untuk pemahaman mendalam.
   - **Menggunakan Python**: Menggunakan pustaka Python seperti Scikit Learn untuk menghitung LOF.
3. **Implementasi LOF pada Data Iris**: Menerapkan LOF untuk mendeteksi outlier dalam dataset Iris.

## Implementasi Naive Bayes

Naive Bayes adalah algoritma klasifikasi berbasis probabilitas yang dapat diterapkan untuk mengklasifikasikan spesies bunga iris berdasarkan fitur-fitur yang ada. Implementasi ini melibatkan:
- **Penggunaan Algoritma**: Menerapkan Naive Bayes untuk klasifikasi data Iris.
- **Analisis Hasil**: Mengevaluasi hasil klasifikasi dan kinerja model.

## Kontak

Untuk pertanyaan lebih lanjut atau dukungan, silakan hubungi:

- Nama: Nama Anda
- Email: abdul.hijjah.akbarul.hidayatulloh
- GitHub: [CakAkbar](https://github.com/CakAkbar)

## Lisensi

Proyek ini dilisensikan di bawah lisensi MIT - lihat file [LICENSE](LICENSE) untuk detail lebih lanjut.
