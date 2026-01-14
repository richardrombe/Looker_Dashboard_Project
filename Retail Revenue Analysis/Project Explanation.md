## Looker Retail Revenue Analysis Dashboard  (Portfolio Project)

## 📌 Ringkasan Proyek
Di dalam proyek ini tersaji penjelasan mengenai proses pembuatan *dashboard* untuk menganalisa pendapatan suatu ritel dengan menggunakan alat bantu visualisasi data. Tujuan utama dari pembuatan *dashboard* ini adalah untuk membantu manajer produk (PM) dalam menganalisis performa penjualan berdasarkan metrik dan kategori yang ada dalam data yang telah diberikan.

## 📁 Dataset
Untuk proyek saat ini diberikan set data mengenai hasil penjualan dari suatu ritel berdasarkan pembelian dari setiap pelanggan. *Dataset* dalam proyek ini diambil dari situs pembelajaran mandiri bernama MySkill dalam bentuk *spreadsheet* Excel (.xlsx). Dari *dataset* yang tersedia, terdapat beberapa baris yang memiliki informasi sebagai berikut:
- **`id`**: kode pemesanan
- **`customer_id`**: kode konsumen
- **`sku_id`**: kode produk
- **`payment_id`**: kode dari setiap metode pembayaran yang tersedia
- **`order_date`**: tanggal pemesanan
- **`price`**: harga satuan
- **`qty_ordered`**: kuantitas pemesanan
- **`before_discount`**: harga sebelum diskon
- **`discount_amount`**: total potongan
- **`after_discount`**: harga setelah diskon
- **`payment_method`**: nama metode pembayaran
- **`sku_name`**: nama produk
- **`base_price`**: harga dasar
- **`cogs`**: biaya perolehan atau biaya yang dibayarkan oleh perusahaan
- **`category`**: kategori dari setiap produk
- **`registered_date`**: tanggal registrasi

🔗 [Akses Dataset Proyek Di sini](https://docs.google.com/spreadsheets/d/1UR6FXMqCyIJgaIrOVPINOKk2gS2AyWvK/edit?usp=drive_link)

## 🗒️Dashboard Requirements
Sebelum membuat *dashboard* untuk melakukan visualisasi data mengenai hasil penjualan, manajer produk memberikan beberapa persyaratan (*requirements*) sebagai patokan untuk membuat *dashboard*. Berikut ini merupakan *requirements* yang diberikan dan aksi yang dilakukan.
1. **Menampilkan performa transaksi secara keseluruhan**

   Dari permintaan bagian ini metrik yang dapat ditampilkan dalam visualisasi data selanjutnya adalah dengan memberikan informasi mengenai total penjualan, total konsumen yang melakukan transaksi, keuntungan, total diskon yang diberikan, dan kuantitas barang.
2. **Mencari *trend* penjualan**

   Kata kunci dari permintaan pembuatan *dashboard* untuk bagian ini terlihat jelas dari kata *trend*, yaitu perubahan penjualan dari waktu ke waktu. Hal ini dapat dipresentasikan dalam bentuk diagram baris (*line chart*).
3x. Mengetahui performa dari setiap metode pembayaran
5. Mencari produk-produk mana saja yang laku
6. Mengetahui pengeluaran dalam pemberian diskon
7. Ringkasan transaksi untuk setiap produk dan konsumen
