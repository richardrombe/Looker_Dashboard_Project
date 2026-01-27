## Looker Retail Transaction Analysis Dashboard  (Portfolio Project)

## 📌 Ringkasan Proyek
Di dalam proyek ini tersaji penjelasan mengenai proses pembuatan *dashboard* untuk menganalisa pendapatan dan transaksi dalam suatu ritel dengan menggunakan alat bantu visualisasi data. Tujuan utama dari pembuatan *dashboard* ini adalah untuk membantu manajer produk (*Product Manager*) dalam menganalisis performa penjualan berdasarkan metrik dan kategori yang ada dalam data yang telah diberikan. Lain dari itu, kegiatan dalam proyek ini yaitu mentransformasi data mentah mengenai transaksi pembelian dalam suatu ritel menjadi informasi visual yang menunjukkan kegiatan transaksi ritel dari Januari 2021 hingga Desember 2022. Dengan adanya visualisasi data ini, ritel dapat mengidentifikasi pertumbuhan transaksi produk per kategori yang ingin fokus dikembangkan dan mempermudah pemangku kepentingan dalam membuat keputusan bisnis yang lebih strategis. 

| Proyek              | Deskripsi                 | Alat yang digunakan         |
| --------------------- | --------------------- |---------------------------|
| Retail Transaction Analysis with Looker | Merancang *dashboard* untuk suatu perusahaan ritel dalam meninjau dan menganalisa transaksi penjualan produk dari beberapa parameter | Google Looker Studio dan Draw.io |

## 📁 Dataset
Untuk proyek saat ini diberikan set data mengenai hasil penjualan dari suatu ritel berdasarkan pembelian dari setiap pelanggan. *Dataset* dalam proyek ini diambil dari situs pembelajaran mandiri bernama MySkill dalam bentuk *spreadsheet* Excel (.xlsx). Isi keseluruhan data yang tersedia memiliki 19 kolom dan lebih dari 5000 baris. Dari *dataset* yang tersedia, terdapat beberapa baris yang memiliki informasi sebagai berikut:
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
3. **Mengetahui performa dari setiap metode pembayaran**

   Performa dari setiap metode pembayaran dapat dilihat dari dua cara, yaitu berapa banyak transaksi dari setiap metode pembayaran dan nilai transaksi per metode pembayaran. Untuk kedua aksi tersebut dapat ditunjukkan dalam bentuk diagram batang, kolom, atau diagram pie.
4. **Mencari produk-produk mana saja yang laku**

   Untuk memenuhi persyaratan ini, hal yang dapat dilakukan adalah dengan cara menunjukkan nilai penjualan dari setiap produk dengan memanfaatkan diagram batang atau hanya menggunakan kolom.
5. **Mengetahui pengeluaran dalam pemberian diskon**

   Pengeluaran untuk diskon dalam perusahaan ritel ini dapat ditampilkan dengan cara mencari nilai diskon dari setiap produk atau bisa juga melalui kategori produk.
6. **Ringkasan transaksi untuk setiap produk dan konsumen**

   Persyaratan terakhir untuk membuat *dashboard* saat ini bisa dilihat dari dua bagian kunci, yaitu produk dan konsumen. Dari bagian produk dapat dilihat berapa yang laku, jumlah pendapatan, dan berapa jumlah diskon yang diberikan. Untuk bagian konsumen dapat ditampilkan informasi berupa jumlah transaksi yang dilakukan, jumlah pendapatan, dan jumlah keuntungan. Kedua bagian tersebut dapat disajikan dalam bentuk tabel.

## 📝 Purwarupa Dashboard (Prototype)
Tahap selanjutnya dalam pembuatan *dashboard* adalah dengan merancang purwarupa atau *prototype* dari *dashboard* yang akan dibangun. Tujuan dari aktivitas ini adalah untuk memudahkan dalam merancang *dashboard* dan memetakan setiap grafik agar terlihat lebih rapih dan tersusun dengan baik. Perancangan purwarupa untuk visualisasi data dalam proyek ini disusun berdasarkan *requirements* yang sudah didefinisikan dalam tahapan sebelumnya, dengan menggunakan bantuan perangkat lunak bernama Draw.io. *Dashboard* yang dirancang dalam proyek ini cukup berbeda dengan yang biasanya, yaitu menggunakan *layout* horizontal. Setelah disusun dan ditentukan penempatan setiap grafik yang akan ditampilkan, berikut ini adalah hasil dari purwarupa yang telah dirancang.

<img width="1124" height="2402" alt="Prototype of Retail Transaction Dashboard drawio" src="https://github.com/user-attachments/assets/cf8328d3-0f7c-4c2f-a6c8-359c2bd2893a" />

Dari purwarupa yang tersaji di atas, terdapat beberapa grafik dan informasi singkat berupa data numerik yang akan ditampilkan dalam alat visualusasi data. Tahap selanjutnya adalah membangun dan mendesain *dashboard* berdasarkan purwarupa yang sudah ada menggunakan Google Looker.

## 📈 Dashboard Interface (Tampilan Dashboard)

## 🔍 Data Insight (Penjelasan Data dalam Dashboard)
