## 📌 Project Overview
Pada proyek saat ini, terdapat penjelasan mengenai pembuatan *dashboard* mengenai transaksi pelanggan yang ada dalam suatu industri perbankan *fiktif* penyedia kredit dan penjelasan mengenai temuan yang dihasilkan. Nama dari perusahaan perbankan tersebut adalah **Payflow**, yang berlokasi di negara Amerika Serikat (USA). Tujuan dari adanya visualisasi data bagi perusahaan perbankan tersebut adalah untuk memetakan strategi dalam menyediakan kredit bagi pelanggan dalam suatu wilayah dan menyediakan layanan prioritas bagi segmen pelanggan yang paling berpotensi dalam menghasilkan keuntungan terbanyak.

| Nama Proyek              | Deskripsi                 | Alat yang digunakan         |
| --------------------- | --------------------- |---------------------------|
| Customer Credit Transaction & Risk Analysis | Membuat visualisasi data untuk suatu industri perbankan dalam meninjau dan menganalisa transaksi penggunaan kartu kredit pelanggan dalam beberapa negara bagian. Hal tersebut berguna dalam mencari keuntungan perusahaan dan risiko yang mengintai dari pelanggan yang melakukan gagal bayar. | Google Looker Studio |

## 📁 Dataset
Visualisasi data dalam proyek ini menggunakan data *dummy* atau data yang disusun sedemikian rupa untuk digunakan sebagai contoh dalam mengerjakan latihan. Data diperoleh dari salah satu situs belajar daring secara mandiri, yaitu MySkill. Secara keseluruhan, data yang disediakan sudah rapih (tidak ada data yang hilang dan duplikasi data) dan tidak perlu untuk dibenahi, tetapi ada beberapa kolom numerik yang tipe datanya dilakukan perubahan agar visualisasi data dapat menunjukkan hasil yang maksimal. Perubahan tipe data dilakukan secara langsung menggunakan Google Sheets dan disambung ke Google Looker Studio.

Secara umum, data yang terkandung menceritakan mengenai identitas setiap nasabah dalam perusahaan bank Payflow mengenai jumlah transaksi yang dilakukan, jumlah uang yang digunakan, jenis kartu kredit yang dipakai, sampai pada apakah nasabah pernah melakukan gagal bayar.
- Jumlah baris yang tersedia: 5054 baris
- Jumlah kolom: 32 kolom dengan beragam tipe data

🔗 [Dataset proyek dapat dilihat disini](https://docs.google.com/spreadsheets/d/1xnoH76rmOHwfv9djW1H6I09xoM37djlrdamU36Bojjg/edit?usp=sharing)

## 🗒️ Dashboard Requirements
Penyusunan kebutuhan dalam membuat visualisasi diperlukan untuk mengetahui informasi apa saja yang akan ditampilkan dalam dasbor. Informasi yang akan disediakan dalam visualisasi data untuk proyek ini dibagi menjadi 3 segmen, yaitu data mengenai **profil pelanggan secara umum, keuntungan yang didapatkan oleh perusahaan, dan risiko yang dialami dari pelanggan**. Melalui ketiga garis besar itu, berikut ini adalah informasi mengenai apa saja yang akan disajikan dalam dasbor mengenai transaksi pelanggan kartu kredit dalam suatu bank.

1. **Demografis pelanggan**

   Pelanggan yang memiliki kartu kredit pastinya memiliki data mengenai profilnya saat mendaftarkan dirinya menjadi *member*. Tim analis kredit bank dapat memanfaatkan data nasabah sebagai alat ukur untuk mengetahui karakteristik pelanggan yang menggunakan layanan kartu kredit. Di bawah ini sudah tersedia mengenai informasi apa saja yang akan ditampilkan pada dasbor dalam segmen pertama, yaitu demografis pelanggan.
   - Sebaran mengenai jumlah nasabah kartu kredit berdasarkan negara bagian
   - Jumlah pelanggan yang dikategorikan berdasarkan jenis pekerjaannya
   - Jumlah pelanggan berdasarkan jenjang pendidikan terakhir
   - Jumlah pelanggan yang dikelompokkan berdasarkan status perkawinan
   - Jumlah pelanggan yang dikelompokkan berdasarkan jenis pengalaman kartu kredit yang dimiliki, dan
   - Informasi umum pelanggan dari setiap negara bagian.

2. **Penghasilan yang didapatkan dari pelanggan**

   Kinerja mengenai keuntungan yang didapatkan oleh industri bank dapat dilihat dari seberapa banyak nasabah melakukan transaksi. Oleh sebab itu, dalam segmen kedua visualisasi data mengenai transaksi pelanggan kartu kredit berisikan mengenai seberapa banyak perusahaan bank ini menghasilkan keuntungan dari beberapa jenis pemasukkan.
   - Jumlah keuntungan yang diraih dari biaya berlangganan berdasarkan jenis pekerjaan nasabah
   - Bunga (*interest*) yang diperoleh bank berdasarkan jenis pekerjaan
   - Total transaksi keseluruhan nasabah yang dikelompokkan sesuai dengan pekerjaannya
   - Nilai rata-rata dari persentase pemakaian kredit aktif (*utilization rate*) berdasarkan jenis pekerjaan, dan
   - Nilai rata-rata dari volume transaksi nasabah berdasarkan jenis pekerjaan dan jenjang pendidikan akhir.

3.  **Risiko yang dialami oleh perusahaan dari pelanggan**

    Selain keuntungan yang didapatkan oleh bank penyedia kredit ini, hal yang ingin diketahui selanjutnya adalah mengenai risiko yang bank hadapi dari sisi pelanggan. Risiko yang akan diperlihatkan dalam hal ini adalah pelanggan atau nasabah yang pernah melakukan gagal bayar. Tentu saja gagal bayar dapat merugikan penyedia kredit dan berikut ini merupakan poin yang akan dipakai dalam membuat dasbor untuk segmen profil risiko pelanggan.
    - Persentase mengenai jumlah rata-rata pelanggan yang melakukan gagal bayar dari setiap negara bagian
    - Nilai rata-rata dalam mengakuisisi nasabah (*acquisition cost*) berdasarkan jenis pekerjaan pelanggan
    - Persentase pelanggan gagal bayar yang dikategorikan dari status perkawinan, dan
    - Nilai persentase rata-rata pelanggan yang pernah gagal bayar berdasarkan jenis pekerjaan dan jenjang pendidikan akhir.

## 🔍 Data Findings
Bank Payflow memiliki ribuan nasabah yang menggunakan layanannya untuk mendapatkan berbagai keuntungan dalam mencukupi kebutuhan hidupnya. Untuk melihat berbagai kegiatan transaksi pelanggan dan pendapatan bank ini, maka diperlukan visualisasi data yang akan ditampilkan dan dijelaskan lebih lanjut. Nilai transaksi dan pendapatan dalam data yang digunakan saat ini menggunakan nilai mata uang Dolar Amerika (U$D). Dasbor telah tersedia dan untuk lebih jelasnya, dapat dilihat pada tautan yang tersedia di bawah. Pengguna dapat secara langsung berinteraksi dengan dasbor dalam setiap segmen yang tersedia.

### [Customer Credit Analysis Dashboard of Payflow Bank](https://lookerstudio.google.com/s/tQXZYvaV63A)

![Customer_Credit_Dashboard_page-0001](https://github.com/user-attachments/assets/a3a8909b-7375-46b0-ba0d-530cf501f434)

1. **Demografis Pelanggan**

   Analisis untuk segmen pertama ini terfokus pada pembahasan mengenai profil dan karakteristik nasabah yang tersebar di beberapa wilayah dengan jumlah lebih dari 5000 pelanggan. Terdapat 5 grafik yang tersedia dan berikut adalah penjelasan dari setiap temuan yang ada.
   + Secara visual, terlihat ada 3 negara bagian dengan jumlah pelanggan terbanyak (semakin tua warna pada suatu wilayah, maka semakin banyak jumlah pelanggannya). Ketiga negara bagian itu adalah California (1.225 pelanggan), Texas (1.181 pelanggan), dan New York (1.149 pelanggan). Sebagian besar nasabah dalam bank Payflow berdomisili di bagian selatan Amerika Serikat.
   - XX

2. **Penghasilan yang didapatkan dari pelanggan**

## 💡 Recommendations
