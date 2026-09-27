## Anggota Kelompok:
- Diyanatul Fauziyah
- Asy syifa Ainaya Zahra
- Nasya Awaliyah
- Raveska Hinayah

## Jawaban Bagian F:
1. Baris : 1212, Kolom : 11, Satu Baris merepresentasikan satu transaksi penjualan
2. - **Numerik** : jumlah, harga_satuan, diskon_persen, rating_pelanggan, total_bayar
   - **Kategorikal** : kota, kategori, produk, metode_bayar
   - **Tanggal** : tanggal
3. Kolom Bermasalah
   - **'metode_bayar'** : terdapat 25 data kosong (missing values)
   - **'rating_pelanggan'** : terdapat 61 data kosong (missing values)
   - **12 baris terduplikasi** (baris yang isinya sama persis perlu di hapus salah satunya)
   - **'kota'** : nilai tidak konsisten akibat perbedaan kapitalisasi (contoh: "Depok" dan "DEPOK", terhitung beda, padahal kota yang sama)
4. Sudah Cukup
