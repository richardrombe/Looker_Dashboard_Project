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
### [Dashboard of Retail Transaction on Looker Studio](https://lookerstudio.google.com/s/uILPZxZTOM0)

<img width="1726" height="4928" alt="Retail_Transaction_Report_-_Portfolio_Project-1" src="https://github.com/user-attachments/assets/58177975-bcfb-41f7-b38d-27ba999992a1" />

Perusahaan ritel yang dianalisis pada proyek saat ini memiliki data transaksi pembelian produk setiap pelanggan selama dua tahun, di mulai pada bulan Januari 2021 hingga Desember 2022. Setiap data yang ingin diperlihatkan secara visual telah direpresentasikan melalui *dashboard* seperti pada tampilan gambar tertera di atas. Untuk elemen visual dalam *dashboard* memiliki penjelasan teknis mengenai bagaimana data dengan layak ditampilkan mulai dari bagian atas hingga bawah, dan berikut ini merupakan penjelasannya:
- Pada bagian atas kanvas dari *dashboard*, terdapat lima elemen data mengenai performa bisnis ritel secara keseluruhan yang ditampilkan secara berderet menggunakan *scorecard*. Dalam bisnis ritel ini, untuk setiap transaksi yang ditampilkan datanya menggunakan satuan kurs **Indonesian Rupiah (IDR)**.
- Bagian visual data kedua yang tertera berbicara mengenai performa penjualan dari waktu ke waktu yang dispesifikasikan berdasarkan bulan dalam tahun (*year month*). Grafik disusun menggunakan dua dimensi data, untuk dimensi vertikal (y) menggunakan data mengenai **pemasukkan sebelum dipotong diskon** dan dimensi horizontal (x) dari data **transaksi pelanggan**. Setiap bulan sudah diberikan titik tanda atau poin untuk mempermudah pembaca untuk melihat akumulasi data mengenai penjualan ritel.
- Selanjutnya adalah grafik mengenai transaksi pembelian berdasarkan metode pembayaran dan kategori produk divisualisasikan menggunakan grafik donat. Nilai dari setiap kategori yang tertera dalam grafik ditampilkan menggunakan satuan persen. Karena ada banyak sekali jenis kategori yang ada dalam kedua grafik, keputusan yang diambil adalah dengan menampilkan hanya **5 kategori teratas** dan selebihnya dikategorikan sebagai ***Others***.
- Sama seperti pada poin sebelumnya, untuk grafik mengenai nilai transaksi berdasarkan metode pembayaran dan kategori produk hanya ditampilkan 5 kategori dengan nilai terbesar dan sisanya digabungkan dalam satu grup bernama *Others*. Grafik disajikan dalam bentuk *bar* atau diagram batang dengan nilai transaksi pada bagian horizontal diringkas dalam bentuk milyaran (B).
- Pada bagian grafik mengenai diskon yang dikeluarkan ritel kepada pelanggan disajikan sama seperti sebelumnya, yaitu dalam bentuk diagram batang. Untuk dimensi vertikal (x) dalam grafik adalah data mengenai **diskon yang diberikan ritel kepada setiap pelanggan**, yang diringkas dalam bentuk jutaan (M) dan dimensi horizontal mengenai **kategori produk**. Seperti beberapa grafik sebelumnya, diagram ini disajikan hanya **9 ketagori dengan pengeluaran diskon terbanyak** dan sisanya digabungkan dalam satu batang, yaitu ***Others***.
- Dua bagian terakhir dalam *dashboard* untuk proyek ini adalah ringkasan mengenai transaksi setiap produk berdasarkan ketegorinya dan transaksi yang dilakukan oleh setiap pelanggan dalam bentuk tabel. Ringkasan data disajikan dengan beberapa metrik, yaitu **penjualan, diskon yang diberikan, kuantitas barang yang dibeli, dan keuntungan yang didapatkan**. Untuk setiap ringkasan transaksi produk per kategori dan transaksi per pelanggan, telah disajikan subtotal untuk setiap metrik yang tersedia.

## 🔍 Data Insight Summary (Penjelasan Data dalam Dashboard)
