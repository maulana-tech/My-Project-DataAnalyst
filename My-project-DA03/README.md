# Analisis Kinerja Situs Web

## Tujuan
Proyek ini bertujuan untuk menganalisis kinerja sebuah situs web dengan memeriksa lalu lintas sesi, metrik keterlibatan pengguna, efektivitas saluran pemasaran, dan meramalkan lalu lintas situs web di masa depan.

## Dataset
Proyek ini menggunakan file CSV bernama `data-export.csv`. Dataset ini mencakup metrik-metrik seperti:
- `Session primary channel group`: Saluran pemasaran (misalnya, Langsung, Sosial Organik).
- `Date + hour`: Tanggal dan jam spesifik dari sesi pengguna.
- `Users`, `Sessions`, `Engaged sessions`: Jumlah lalu lintas dan keterlibatan.
- `Average engagement time per session`, `Engagement rate`, `Events per session`: Metrik yang mengukur kualitas interaksi pengguna.

## Metodologi & Langkah Analisis
1.  **Pemuatan dan Pembersihan Data:** Memuat dataset menggunakan `pandas`, memperbaiki header, dan mengonversi tipe data.
2.  **Analisis Data Eksplorasi (EDA) & Visualisasi Deret Waktu:** Memvisualisasikan tren total pengguna dan sesi dari waktu ke waktu.
3.  **Analisis Keterlibatan Pengguna:** Menganalisis metrik keterlibatan utama dari waktu ke waktu dan melihat korelasi di antara mereka.
4.  **Analisis Kinerja Saluran:** Membandingkan kinerja berbagai saluran pemasaran berdasarkan lalu lintas dan keterlibatan.
5.  **Peramalan Lalu Lintas Situs Web:** Membangun model SARIMA untuk meramalkan sesi situs web untuk 24 jam ke depan.

## Pustaka yang Digunakan
- `pandas`
- `matplotlib.pyplot`
- `statsmodels`

## Cara Menjalankan
1. Pastikan Anda telah menginstal semua pustaka yang diperlukan.
2. Buka file `My_Project_DA03.ipynb` di Jupyter Notebook atau JupyterLab.
3. Jalankan sel-sel secara berurutan untuk mereproduksi analisis.
