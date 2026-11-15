# Dokumentasi Kontaminasi Dataset (Simulasi)

`data/simulated/supermarket_sales_dirty.csv` merupakan salinan dataset yang diberi kesalahan secara terkontrol untuk kebutuhan latihan diagnosis dan pembersihan M2. Dataset asli di `data/raw/` tidak diubah.

Kontaminasi yang disisipkan:
- 18 nilai `Rating` dibuat kosong.
- 6 nilai `Rating` diubah menjadi nilai tidak valid (0 atau 11; rentang rating yang digunakan adalah 1–10).
- 4 nilai `Quantity` diubah menjadi teks `dua`.
- 12 label `Payment` diberi variasi kapitalisasi/format.
- 10 nilai `City` diberi spasi di ujung.
- 8 baris duplikat persis ditambahkan.

Seed pembuatan awal: `20261114`.

**Penting:** daftar ini menjelaskan kesalahan simulasi yang sengaja dibuat untuk latihan. Ini bukan klaim bahwa dataset asli memiliki semua masalah tersebut.
