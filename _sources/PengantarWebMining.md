# Pengantar Web Mining

## Pengantar Web Mining

Web mining adalah salah satu cabang ilmu data mining yang secara khusus diarahkan untuk menggali informasi maupun pola yang tersembunyi dalam data yang terdapat di World Wide Web (WWW). Data di web memiliki karakteristik yang sangat besar, bervariasi, dan sebagian besar tidak terstruktur, sehingga metode konvensional sering kali tidak cukup efektif.

Bidang ini pertama kali diperkenalkan oleh Oren Etzioni pada tahun 1996. Secara sederhana, web mining dapat diartikan sebagai usaha mengombinasikan teknik data mining, machine learning, serta teknologi web untuk memperoleh informasi yang bermanfaat dari data online.

Web mining memiliki tiga kategori utama:

1.	Web Content Mining – menambang informasi dari isi atau konten web.

2.	Web Structure Mining – menganalisis hubungan antar halaman melalui hyperlink.

3.	Web Usage Mining – mengekstraksi pola perilaku pengguna berdasarkan data log dan interaksi mereka di web.

Perbedaan utama dengan data mining biasa adalah pada sumber datanya. Data mining tradisional menggunakan data warehouse yang tersusun rapi, sedangkan web mining lebih sering menghadapi data tidak terstruktur yang tersebar di berbagai situs.

## Penerapan Web Mining

Implementasi web mining kini banyak digunakan pada layanan digital, terutama karena jumlah data yang terus meningkat setiap detik. Beberapa penerapan yang paling umum antara lain:

•	Mesin Pencari: meningkatkan performa search engine dengan mengklasifikasikan dokumen web dan mengenali relevansi halaman (contohnya Google dan Yahoo).

•	Pencarian Vertikal: digunakan pada mesin pencari khusus (contohnya FatLens).

•	Prediksi Perilaku Pengguna: membantu perusahaan memahami pola belanja atau navigasi pengguna.

•	Optimasi Website: misalnya, memperbaiki desain halaman arahan (landing page) agar lebih sesuai dengan kebutuhan pengunjung.

Tahapan proses yang biasa digunakan dalam web mining meliputi: pengumpulan data (crawling), pembersihan data, transformasi, ekstraksi fitur, hingga menemukan pola yang bermakna.

## Web Crawling

Web crawling adalah proses pengumpulan dan pengindeksan data dari internet yang dilakukan oleh program otomatis seperti web crawler, web spider, atau bot. Hasil dari crawling kemudian disimpan di database mesin pencari agar informasi dapat ditemukan dengan cepat.

Proses ini sangat penting karena tanpa crawling, search engine tidak dapat memberikan hasil pencarian yang relevan. Crawling juga dikenal sebagai proses indexing, yakni membaca, mengarsip, dan menyimpan seluruh konten web untuk memudahkan pencarian di kemudian hari.

## Data Preprocessing

Data yang diperoleh dari web umumnya masih mentah, tidak teratur, dan mengandung banyak noise. Oleh karena itu, dilakukan data preprocessing agar data lebih siap untuk dianalisis.

Tahapan preprocessing meliputi:

1.	Data Cleaning – menghapus data tidak konsisten, memperbaiki nilai hilang, serta mengurangi noise.

2.	Data Integration – menggabungkan data dari berbagai sumber menjadi satu dataset besar.

3.	Data Transformation – mengubah format, struktur, atau nilai data agar sesuai dengan kebutuhan analisis

## Supervised Learning

Supervised Learning adalah salah satu metode pembelajaran mesin (machine learning) yang menggunakan data berlabel (memiliki input dan output). Tujuannya adalah membuat model yang mampu memprediksi output baru berdasarkan pola data latih.

Langkah-langkahnya meliputi:

•	Mengumpulkan dataset yang relevan.

•	Melakukan preprocessing (normalisasi, pembersihan, pembagian data training dan testing).

•	Memilih model (misalnya regresi linier, decision tree, SVM, neural network).

•	Melatih model menggunakan data training.

•	Mengevaluasi dengan data testing menggunakan metrik seperti akurasi, presisi, recall, F1-score.

•	Melakukan tuning parameter untuk meningkatkan kinerja.

•	Menggunakan model untuk prediksi data baru.

## Unsupervised Learning

Berbeda dengan supervised learning, unsupervised learning bekerja tanpa data berlabel. Tujuan utamanya adalah menemukan pola tersembunyi, pengelompokan (clustering), atau asosiasi antar data.

Contoh penerapannya:

•	Segmentasi pelanggan berdasarkan kesamaan perilaku.

•	Analisis pasar untuk menemukan kelompok produk yang sering dibeli bersamaan.

•	Deteksi anomali dalam data keuangan atau jaringan komputer.

## Web Content Mining

Web Content Mining adalah proses otomatis untuk menemukan informasi dari konten yang terdapat pada halaman web, baik berupa teks, gambar, video, audio, metadata, maupun hyperlink. Fokus utamanya adalah mengekstraksi kata kunci atau data penting dari dokumen web.

Terdapat dua strategi umum:

1.	Melakukan mining secara langsung pada data web.

2.	Melakukan pencarian serta meningkatkan kualitas hasil pencarian, seperti cara kerja search engine.

Teknik ini sering juga disebut Web Text Mining karena sebagian besar fokusnya pada data berbasis teks. Hubungannya erat dengan Information Retrieval (IR), namun dengan perkembangan teknologi, akurasi serta efisiensi analisis semakin meningkat, sehingga mampu menghemat biaya pengolahan data.

Aplikasi Text Mining

1.	Information Extraction: mengambil entitas penting seperti nama orang, tempat, tanggal, dan organisasi.

2.	Text Classification: mengelompokkan teks ke dalam kategori tertentu (misalnya berita politik, olahraga, atau hiburan).

3.	Text Clustering: membentuk kelompok dokumen tanpa label awal, hanya berdasarkan kesamaan isi.

4.	Topic Modeling: menemukan tema-tema yang tersembunyi dalam kumpulan dokumen besar.

5.	Sentiment Analysis: menentukan opini atau emosi pengguna (positif, negatif, netral).

6.	Text Summarization: membuat ringkasan otomatis dari teks yang panjang.

## Web Usage Mining

Web Usage Mining berfokus pada pola interaksi pengguna saat mengakses website. Data yang digunakan berasal dari log file server, cookies, clickstream, hingga query pencarian.

Beberapa manfaatnya antara lain:

•	Menyesuaikan tampilan halaman berdasarkan preferensi pengguna.

•	Mengidentifikasi ketertarikan pelanggan terhadap produk tertentu.

•	Menentukan target pasar dan strategi pemasaran yang lebih tepat.

Aplikasi Web Usage Mining

1.	Sistem Rekomendasi – merekomendasikan produk atau jasa berdasarkan riwayat kunjungan pengguna.

2.	Personalisasi Konten – menampilkan hasil pencarian sesuai profil pengguna.

3.	Clickstream Analysis – menganalisis urutan klik pengguna untuk memahami pola navigasi.

## Web Structure Mining

Web Structure Mining berfokus pada struktur hyperlink di web. Analisis ini dapat menunjukkan hubungan antar halaman, otoritas sebuah situs, serta hierarki informasi di dalam halaman.

Jenis data yang digunakan antara lain:

•	Hyperlink antar dokumen (inter-document links) – misalnya tautan artikel A ke artikel B, yang dapat digunakan untuk menentukan otoritas (contoh: Google PageRank).

•	Struktur internal dokumen (intra-document structure) – berdasarkan Document Object Model (DOM) yang menggambarkan susunan elemen dalam halaman web.

Dengan teknik ini, peneliti maupun pengembang dapat memahami bagaimana informasi terhubung, sehingga memudahkan pembuatan ringkasan website, sistem navigasi, maupun optimasi SEO.

## Deployment System

Deployment adalah tahap akhir dari siklus pengembangan sistem, yaitu ketika aplikasi sudah siap digunakan dan ditempatkan di lingkungan produksi. Tujuannya adalah agar aplikasi bisa diakses langsung oleh pengguna dan memberikan manfaat sesuai kebutuhan.

Tahapan Deployment

1.	Persiapan: meninjau ulang aplikasi sebelum dipublikasikan.

2.	Pengujian: memastikan aplikasi berjalan baik di lingkungan uji yang menyerupai kondisi nyata.

3.	Konfigurasi Produksi: menyesuaikan database, server, jaringan, dan layanan pendukung agar aplikasi dapat bekerja optimal sesuai skala bisnis
 
