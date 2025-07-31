# 🚴‍♂️ Dashboard Analisis Penjualan Sepeda – Portofolio Data Excel

Repositori ini berisi proyek analisis data penjualan sepeda menggunakan **Microsoft Excel** dengan bantuan **Pivot Table**, **Slicer**, dan Visualisasi interaktif dalam bentuk **Dashboard**. Analisis ini dilakukan berdasarkan kategori sepeda, jenis kelamin pelanggan, segmentasi pelanggan, metode pembayaran dan periode waktu.

## 📊 Ringkasan Proyek

Proyek ini bertujuan untuk menganalisis data penjualan sepeda berdasarkan informasi seperti:
- Kategori sepeda (contoh: Road Bike, Electric Bike)
- Jenis kelamin pelanggan
- Lokasi toko
- Periode waktu (bulanan)

Output akhir berupa **Dashboard interaktif** yang dapat digunakan untuk mengambil keputusan berbasis data.

## 🔍 Fitur Utama

- ✅ **Pembersihan Data**:
  - Format tanggal diubah menjadi nama bulan (contoh: "Jan")
  - Kategori umur dibuat (misalnya: <30, 30–50, >50)

- 📈 **Analisis Pivot Table**:
  - Total revenue per bulan
  - Volume penjualan berdasarkan kategori sepeda
  - Distribusi pelanggan berdasarkan jenis kelamin dan usia
  - Performa toko berdasarkan lokasi

- 🎯 **KPI (Key Performance Indicators)**:
  - Tren pendapatan bulanan
  - Rata-rata pendapatan
  - Jumlah item terjual

- 🧩 **Dashboard Interaktif**:
  - Slicer untuk filter berdasarkan gender, tahun, dan lokasi toko
  - Tombol reset slicer (opsional via VBA)
  - Persentase otomatis jika filter gender dipilih (misal: laki-laki = 100%)

## 📂 Struktur Folder
Excel-for-Data-Analysis/
├── data/
│   └── bike_sales_100k_raw_data.csv
├── dashboard/
│   ├── bike_sales_100k.xlsm
├── preview/
│   └── Dashboard.png
├── README.md

## 🛠 Alat yang Digunakan

- **Microsoft Excel**:
  - Pivot Table & Pivot Chart
  - Slicer (filter interaktif)
  - Rumus IF, TEXT, IFERROR, dan lainnya
- **(Opsional)** VBA untuk tombol reset slicer
- **Jenis Grafik**:
  - Grafik garis (Tren Pendapatan)
  - Grafik lingkaran (Distribusi Gender)
  - Grafik batang (Kinerja Kategori)

## 📊 Dashboard
![Dashboard Penjualan](preview/dashboard.png)

---
Feel free to fork, clone, or contribute! 🚀
