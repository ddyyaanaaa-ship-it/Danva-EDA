# Data Dictionary

Satu baris merepresentasikan satu transaksi/nota supermarket. Dataset memiliki 17 kolom.

| Kolom | Tipe data | Deskripsi | Skala/satuan |
|---|---|---|---|
| Invoice ID | Teks | Identitas unik transaksi | ID |
| Branch | Kategorikal | Kode cabang supermarket | Nominal |
| City | Kategorikal | Kota cabang | Nominal |
| Customer type | Kategorikal | Tipe pelanggan (Member/Normal) | Nominal |
| Gender | Kategorikal | Kategori gender pada data | Nominal |
| Product line | Kategorikal | Kelompok produk | Nominal |
| Unit price | Numerik | Harga satuan produk | Mata uang dataset |
| Quantity | Numerik | Jumlah unit barang pada transaksi | Unit |
| Tax 5% | Numerik | Pajak 5% transaksi | Mata uang dataset |
| Total | Numerik | Total nilai transaksi termasuk pajak | Mata uang dataset |
| Date | Tanggal/teks tanggal | Tanggal transaksi | Tanggal |
| Time | Waktu/teks waktu | Waktu transaksi | Jam |
| Payment | Kategorikal | Metode pembayaran | Nominal |
| cogs | Numerik | Cost of goods sold / biaya pokok | Mata uang dataset |
| gross margin percentage | Numerik | Persentase margin kotor | Persen |
| gross income | Numerik | Pendapatan kotor transaksi | Mata uang dataset |
| Rating | Numerik | Penilaian pelanggan | Skala 1–10 |

## Catatan
- `Invoice ID` adalah pengenal transaksi, bukan nama atau kontak pelanggan.
- Struktur kolom yang tersedia tidak memuat nama, alamat rumah, nomor telepon, atau email pelanggan.
- `Date` dan `Time` perlu dikonversi ke tipe tanggal/waktu sebelum analisis temporal.
- `gross margin percentage` perlu diperiksa variasinya; variabel konstan tidak informatif untuk korelasi.
- Tim harus memverifikasi satuan mata uang, sumber unduhan, dan lisensi sesuai metadata sumber dataset yang benar-benar digunakan. Jangan menebak informasi yang tidak tersedia.
