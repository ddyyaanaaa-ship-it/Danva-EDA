# DANVA — Exploratory Data Analysis

## Topik proyek
**Analisis Pola Penjualan Supermarket Berdasarkan Produk, Kota, Pelanggan, dan Metode Pembayaran**

## Anggota kelompok
1. Diyanatul Fauziyah
2. Nasya Awaliyah
3. Raveska Hinayah
4. Asysyifa Ainaya Zahra

## Deskripsi singkat
Proyek ini menganalisis data transaksi supermarket untuk memahami pola nilai transaksi, kelompok produk, kota/cabang, tipe pelanggan, dan metode pembayaran.

## Struktur repository
```text
Danva-EDA/
├── data/
│   ├── raw/          # Dataset asli; jangan diubah
│   ├── simulated/    # Salinan dengan kontaminasi terkontrol untuk latihan M2
│   └── processed/    # Dataset hasil pembersihan
├── notebooks/        # Notebook resmi starter kit dan notebook praktikum anggota
├── reports/
│   └── figures/      # Grafik hasil analisis
├── knime/            # File workflow KNIME untuk milestone berikutnya
├── README.md
├── data_dictionary.md
├── cleaning_log.md
├── AI_usage_log.md
├── PENGOTORAN_DATASET.md
└── requirements.txt
```

## Urutan pengerjaan
- **M1:** rumusan masalah/pertanyaan analisis, sumber dan asal data, data dictionary, serta pemeriksaan privasi.
- **M2:** diagnosis kualitas data, pembersihan data, validasi, dan cleaning log.
- **M3:** analisis univariat, bivariat, dan multivariat.
- **M4–M5:** dikerjakan setelah materi dan instruksi dosen untuk milestone tersebut diberikan.

## Catatan dataset
- `data/raw/supermarket_sales_original.csv` adalah salinan data asli yang diterima kelompok. Jangan mengubah atau menimpanya.
- `data/simulated/supermarket_sales_dirty.csv` adalah salinan yang diberi kesalahan secara terkontrol untuk latihan M2.
- Hasil pembersihan nantinya disimpan di `data/processed/`.
- Kelompok perlu memastikan kembali tautan sumber asli dan lisensi dataset dari tempat file pertama kali diunduh sebelum laporan akhir.

## Cara menjalankan
Buka notebook dari folder `notebooks/` menggunakan Jupyter atau Google Colab. Sesuaikan path relatif bila menjalankan dari lingkungan yang berbeda. Jalankan notebook sesuai instruksi milestone dan pastikan hasil akhir disimpan pada folder repository, bukan di lokasi sementara.
