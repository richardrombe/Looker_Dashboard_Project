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
   - Informasi umum mengenai aktivitas pelanggan dari setiap negara bagian.

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

<img width="2134" height="1350" alt="Customer_Credit_Dashboard_page-0001" src="https://github.com/user-attachments/assets/7e0da280-f4a3-4d25-b02d-f1139a9c0a67" />

1. **Demografis Pelanggan**

   Analisis untuk segmen pertama ini terfokus pada pembahasan mengenai profil dan karakteristik nasabah yang tersebar di beberapa wilayah dengan jumlah lebih dari 5000 pelanggan. Terdapat 5 grafik yang tersedia dan berikut adalah penjelasan dari setiap temuan yang ada.
   + Secara visual, terlihat ada 3 negara bagian dengan jumlah pelanggan terbanyak (semakin tua warna pada suatu wilayah, maka semakin banyak jumlah pelanggannya). Ketiga negara bagian itu adalah California (1.225 pelanggan), Texas (1.181 pelanggan), dan New York (1.149 pelanggan). Secara letak geografis, sebagian besar nasabah dalam bank Payflow berdomisili di bagian selatan Amerika Serikat.
   + Jenis pekerjaan adalah hal yang wajib untuk bank ketahui sebelum pelanggan dapat menggunakan layanannya. Menurut data yang tersedia, nasabah dengan pekerjaan *Self-employeed* (wiraswasta) menduduki peringkat terbanyak dalam hal jumlah pelanggan terbanyak (1.279 pelanggan). Untuk peringkat kedua jatuh kepada nasabah dengan pekerjaan sebagai *Businessman* atau pengusaha (932 pelanggan).
   + Jenjang pendidikan terakhir pelanggan yang paling dominan adalah *Graduate* atau jenjang program S2 (2.094 pelanggan). Ini berarti hampir sebagian besar nasabah yang memiliki kredit di bank Payflow merupakan nasabah yang berpendidikan tinggi. Posisi kedua yang terdapat dalam grafik batang adalah pelanggan dengan pendidikan terakhir *High school* atau SMA (988 pelanggan). Sedangkan untuk level pendidikan *Doctorate* atau S3 menduduki peringkat akhir dari total keseluruhan pelanggan (226 pelanggan).
   + Poin ini membahas mengenai jumlah nasabah berdasarkan status perkawinan. Separuh dari total nasabah yang menggunakan layanan bank ini sudah menikah (51.2% / 2.586 pelanggan). Kemudian untuk nasabah yang belum menikah menduduki posisi kedua dengan selisih hanya 10% dari nasabah yang telah menikah (41.5% / 2.099 pelanggan). Sisa dari total jumlah pelanggan merupakan nasabah yang tidak diketahui status perkawinannya (7.3% / 369 pelanggan).
   + Jenis pengalaman kartu kredit yang paling banyak nasabah pilih yaitu *Bills* atau pengalaman kredit dalam memberikan keuntungan untuk membayar tagihan (1.482 pelanggan). Tidak kalah jauh dari sebelumnya, jenis pengalaman kredit *Entertainment* atau hiburan secara kuantitas juga tergolong banyak yang digunakan oleh nasabah (962 pelanggan).

<img width="2134" height="1350" alt="Customer_Credit_Dashboard_page-0002" src="https://github.com/user-attachments/assets/c6625000-d7fc-4bd2-9e22-f9199d1da349" />

2. **Penghasilan yang didapatkan dari pelanggan**

   Bagian kedua dalam analisis saat ini bertujuan untuk memahami sumber pendapatan terbesar bank dari data yang telah divisualisasi. Indikator yang digunakan pada segmen ini difokuskan pada jenis pekerjaan nasabah.
   + Biaya berlangganan nasabah termasuk salah satu pendapatan bank. Menurut data yang tersedia, pelanggan dengan pekerjaan sebagai *Self-employeed* (wiraswata) adalah segmen pelanggan dengan kontribusi terbesar dalam menghasilkan keuntungan bagi bank Payflow ($370.985). Mengapa demikian? Hal ini terjadi karena, sebagian besar jumlah nasabah yang memiliki kredit dalam bank ini merupakan pelanggan dengan pekerjaan sebagai wiraswata (lihat segmen *Customer Demographic*, grafik *Customer Occupation*).
   + *Interest* (bunga) merupakan sumber pendapatan bank yang datang dari nasabah yang memiliki hutang. Agregasi yang digunakan dalam grafik adalah nilai rata-rata. Tujuannya untuk melihat siapa segmen nasabah penghasil pendapatan terbesar bank dari sisi bunga yang didapat. Dari sini sudah nampak, bahwa pelanggan dengan profesi sebagai *Businessman* (pengusaha) merupakan penghasil keuntungan bank terbanyak secara rata-rata ($1.311) dari bunga yang didapat. Di sisi lain menunjukkan hal yang berseberangan, nasabah dengan profesi *Self-employeed* (wiraswasta) memiliki kontribusi paling sedikit dalam hal ini ($434). Walaupun secara kuantitas kalah dengan nasabah berprofesi *Self-employeed*, *Businessman* lebih dominan dalam hal penyumbang pendapatan terbesar bank dari bunga yang didapat.
   + Nilai transaksi yang semakin banyak memiliki dampak yang positif bagi bank dalam meraup keuntungan. Berdasarkan statistik yang tersedia, segmen pelanggan yang berprofesi sebagai *Businessman* telah melakukan transaksi dengan nominal tertinggi dibanding dengan segmen profesi pelanggan lainnya ($6.954.061). Sesuai dengan jenis pekerjaannya, pengusaha memang memerlukan banyak modal untuk membangun dan mengembangkan usahanya. Selanjutnya adalah segmen pelanggan dengan profesi sebagai *White-collar* (pekerja kantoran) dengan akumulasi total transaksi dengan nominal tertinggi kedua ($4.413.864). Segmen pelanggan *Retirees* (pensiunan) merupakan segmen profesi pelanggan yang total nilai transaksinya paling sedikit ($1.794.937).
   + *Utilization rate* (rasio pemanfaatan kredit) yang semakin rendah menandakan nasabah dapat mengelola kredit dengan baik, dengan kata lain nasabah tidak terlalu bergantung pada hutang. Batas aman penggunaan kredit yang baik yaitu berada pada rasio di bawah 30%. Berdasarkan statistik yang tersaji, semua segmen pelanggan berdasarkan profesinya berada pada rasio pemanfaatan kredit yang wajar. Untuk yang teratas, yaitu segmen pelanggan *Retirees* (sudah pensiun) yang secara rata-rata memiliki rasio penggunaan kredit tertinggi (29.22%). Ini sudah hampir mencapai batas aman penggunaan kredit yang ideal. Sedangkan untuk segmen pelanggan *Businessman* (pengusaha) memiliki skor rasio penggunaan kredit yang paling baik jika disandingkan dengan segmen lainnya (25.43%).
   + Aktivitas penggunaan kredit dapat dilihat dari volume transaksi yang telah dilakukan. Jika dilihat pada tabel yang tersedia, segmen pelanggan berprofesi *Businessman* (pengusaha) memiliki rata-rata volume bertransaksi paling banyak dan untuk pelanggan yang bekerja sebagai *Self-employeed* (wiraswasta) justru sebaliknya. Nasabah *Businessman* yang jenjang pendidikannya *Unknown* (tidak diketahui) merupakan segmen pelanggan yang paling banyak melakukan transaksi menggunakan kredit bank (84 kali). Nasabah *Businessman* dengan pendidikan *Uneducated* (tidak sekolah) mengikuti dengan rata-rata jumlah bertransaksi terbanyak kedua (81 kali). Sedangkan untuk nasabah *Self-employeed* dengan pendidikan akhir *Doctorate* (S3) merupakan segmen pelanggan yang memiliki rata-rata bertransaksi terendah (44 kali).

<img width="2134" height="1350" alt="Customer_Credit_Dashboard_page-0003" src="https://github.com/user-attachments/assets/927d9102-fdbe-46ac-89a7-9b17a5d87e45" />

3. **Risiko yang dialami oleh perusahaan dari pelanggan**

   Segmen terakhir dalam visualisasi data saat ini membahas mengenai risiko yang mengancam bank dari sisi pelayanan yang diberikan kepada nasabah. Tujuannya untuk mengetahui indikator apa saja yang membuat perusahaan bank ini dapat rugi dan dari hal tersebut dapat digunakan sebagai pedoman untuk mencegahnya.
   + *Delinquent* merupakan istilah bank dalam merujuk nasabah yang pernah melakukan gagal bayar pelunasan hutang. Jika dilihat data dari setiap negara bagian, pelanggan yang berdomisili di Oregon (OR) menunjukkan negara bagian yang memiliki persentase gagal bayar paling tinggi (33%). Hal yang menarik adalah pelanggan yang berasal dari California (CA) memiliki persentase gagal bayar yang rendah (5%), padahal negara bagian tersebut merupakan jumlah nasabah bank Payflow terbanyak (1.225 pelanggan). Untuk negara bagian Nebraska (NE) hingga Connecticut (CT) sama sekali tidak memiliki nasabah yang pernah melakukan gagal bayar pinjaman (0%).
   + Jika ditinjau lebih dalam lagi, segmen pelanggan yang paling besar kontribusinya dalam hal gagal bayar hutang tepat waktu sebagian besar berasal dari nasabah yang bekerja di sektor *Govt* (pemerintahan). Persentase terbesar dalam hal ini terlihat jelas datang dari pelanggan yang bekerja di *Govt* (pemerintahan) dengan pendidikan akhir *Uneducated* (tidak sekolah) (14%). Untuk segmen pelanggan dengan profesi lainnya yang persentase gagal bayarnya tinggi berasal dari nasabah *Retirees* (pensiunan) yang jenjang pendidikannya *Unknown* (tidak diketahui) (11%). Menariknya, segmen pelanggan berprofesi *Businessman* (pengusaha) memiliki rasio melakukan gagal bayar pinjaman paling rendah. Segmen pelanggan tersebut memang sangat menguntungkan untuk bank ini.
   + Jumlah nasabah yang "nakal" dapat dilihat juga dari status perkawinan. Dari grafik yang tersaji cukup mengejutkan. Pelanggan dengan status perkawinan *Single* (belum menikah) justru termasuk segmen pelanggan yang pernah gagal bayar pinjaman terbanyak (46.4% / 147 pelanggan) dibandingkan dengan nasabah yang sudah *Married* (menikah) dengan persentase yang berbeda tipis (43.8% / 139 pelanggan). Padahal untuk segmen pelanggan yang belum menikah seharusnya bisa melakukan pembayaran hutang dengan tepat waktu, karena mereka belum memiliki banyak kewajiban dan berkeluarga. Yang terakhir, yaitu untuk nasabah yang status perkawinannya *Unknown* (tidak diketahui) jumlahnya hanya beberapa saja (9.8% / 31 pelanggan).
   + *Acquisition cost* merupakan pengeluaran yang dikeluarkan oleh bank untuk memperoleh nasabah. Menurut grafik yang tersedia, bank ini mengucurkan dana yang totalnya tidak jauh berbeda dalam mengakusisi nasabah baru untuk setiap segmen pelanggan berdasarkan profesinya. Tetapi yang pasti, terlihat jelas bahwa bank Payflow fokus mencari nasabah baru yang berprofesi *Businessman* (pengusaha) sebagai target utama. Hal ini dibuktikan dengan dana yang dikeluarkan paling besar nominalnya ($98). Sedangkan target untuk mendapatkan nasabah yang bekerja sebagai *Self-employeed* (wiraswasta), bank ini mengucurkan dana yang sedikit lebih kecil dibandingkan dengan profesi lainnya ($93).

## 💡 Recommendations
Interpretasi data mengenai profil pelanggan, keuntungan yang didapat, dan risiko yang dihadapi sudah dilakukan. Dari analisis dan penjabaran tersebut, ada beberapa temuan yang berguna untuk dijadikan sebagai tolak ukur dalam mencapai tujuan yang lebih baik. Dalam mencapai tujuan yang diinginkan, diperlukan juga suatu rekomendasi atau saran agar bisnis dapat terus berkembang. Tentunya saran yang diberikan kepada bank Payflow ini diharap dapat memberikan layanan yang bermutu dan tepat sasaran kepada setiap pelanggan. Saran atau rekomendasi tersebut memuat beberapa hal seperti berikut.
