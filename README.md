<h1> Business Understanding </h1>

<h2> Latar Belakang </h2>

Warmindo, kependekan dari Warung Makan Indomie, adalah salah satu jenis usaha kuliner yang sangat populer di Indonesia. Warung ini menawarkan berbagai macam produk berbasis mi instan dan menu sederhana lainnya yang digemari oleh berbagai kalangan. Untuk memahami dan mengoptimalkan operasional bisnis, penting bagi Warmindo untuk menganalisis data transaksi yang terjadi di warung mereka.

<h3> Tujuan Analisis </h3>

Analisis data transaksi dari dataset data_warmindo.csv memiliki beberapa tujuan utama:

1. Mengidentifikasi Pola Pembelian Pelanggan
    - Menganalisis kapan (tanggal dan waktu) transaksi terjadi untuk mengetahui jam sibuk dan periode waktu dengan penjualan tertinggi.
    - Melihat produk apa yang paling sering dibeli dan bagaimana permintaan produk berubah dari waktu ke waktu.
    - Siapa pelanggan setia dan bagaimana kita bisa meningkatkan loyalitas mereka?
    - Bagaimana efektivitas promosi dan diskon?

2. Segmentasi Pelanggan
    - Mengelompokkan pelanggan berdasarkan pola pembelian mereka, seperti frekuensi pembelian, jenis produk yang dibeli, dan nilai penjualan.
    - Mengetahui siapa pelanggan setia dan pelanggan yang jarang berbelanja.

3. Optimasi Stok dan Inventaris
    - Menggunakan data penjualan untuk memperkirakan kebutuhan stok produk.
    - Mengurangi risiko kekurangan stok atau overstocking yang dapat mengurangi profitabilitas.

4. Evaluasi Promosi dan Diskon
    - Menganalisis efektivitas berbagai jenis promosi dan diskon yang diberikan kepada pelanggan.
    - Mengidentifikasi metode pembayaran mana yang paling sering digunakan oleh pelanggan dan apakah ada pengaruhnya terhadap nilai penjualan.

<h3> Hasil yang Diharapkan </h3>

Dengan melakukan analisis mendalam terhadap data ini, Warmindo dapat mengambil keputusan bisnis yang lebih baik berdasarkan wawasan yang diperoleh. Hasil analisis diharapkan dapat membantu dalam:

- Mengoptimalkan strategi penjualan dan pemasaran.
- Memperbaiki manajemen inventaris dan rantai pasokan.
- Meningkatkan kepuasan dan loyalitas pelanggan melalui layanan yang lebih baik dan penawaran yang disesuaikan dengan kebutuhan pelanggan.

<h1> Data Understanding </h1>

- **Koleksi Data:** Dataset data_warmindo.csv dengan 499 rows dengan kolom id, invoice_id, tanggal_transaksi, customer_id, nama_produk, jenis_produk, kategori_produk, quantity, harga_jual, jenis_pembayaran, jenis_pesanan, nilai_penjualan. Dari masing-masing kolom ini memiliki penjelasan sebagai berikut:

    - id: ID unik untuk setiap entri transaksi.
    - invoice_id: ID faktur untuk transaksi tertentu.
    - tanggal_transaksi: Tanggal transaksi terjadi.
    - customer_id: ID unik untuk setiap pelanggan.
    - nama_produk: Nama produk yang dibeli.
    - jenis_produk: Jenis produk (misalnya, mi instan, minuman, dll.).
    - kategori_produk: Kategori produk (misalnya, makanan, minuman).
    - quantity: Jumlah produk yang dibeli.
    - harga_jual: Harga jual per unit produk.
    - jenis_pembayaran: Jenis pembayaran yang digunakan (misalnya, tunai, kartu kredit).
    - jenis_pesanan: Jenis pesanan (misalnya, makan di tempat, bawa pulang).
    - nilai_penjualan: Total nilai penjualan untuk transaksi tersebut.

- **Eksplorasi Data:**
    - Mengidentifikasi distribusi dan statistik deskriptif dari masing-masing kolom.
    - Mengamati pola temporal dari tanggal_transaksi.
    - Menggali hubungan antara nama_produk, jenis_produk, dan kategori_produk dengan nilai_penjualan.

<h1> Data Preparation </h1>

- **Pembersihan Data:**
    - Mengisi atau menghapus data yang hilang.
    - Mengoreksi atau menghapus data anomali.

- **Transformasi Data:**
    - Mengubah format tanggal_transaksi menjadi datetime.
    - Mengelompokkan produk berdasarkan kategori_produk.
    - Menambahkan kolom baru jika diperlukan (misalnya, hari dalam minggu, bulan, dll).

- **Integrasi Data:**
    - Menggabungkan data yang mungkin terpisah (jika ada dataset tambahan).  

<h1> Exploratory data analysis (EDA) </h1>

Pada tahapan analisa ini akan menjawab pertanyaan yang ada pada Business Understanding, berdasarkan pada data yang sudah dilakukan pengecekan dan proses cleaning pada tahap sebelumnya.

![Penjualan Harian](image_visual/Penjualan_Harian.png)