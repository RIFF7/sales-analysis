# Analisa Warmindo [Menggunakan Excel] 📊🖩

Pada folder ini akan berisi penjelasan dan juga file hasil dari analisa yang sudah dilakukan menggunakan Excel, untuk langkah selanjutnya adalah membersihkan dan merapikan data di Excel agar siap untuk dianalisis, saya menggunakan cara dibawah ini untuk menyelesaikannya:

1. Pemeriksaan Duplikasi
    - Cari dan Hapus Duplikasi:
        - Pilih seluruh data.
        - Buka tab **Data** > **Remove Duplicates**.
        - Pastikan semua kolom dipilih untuk memastikan bahwa hanya baris dengan semua kolom yang identik yang akan dihapus.
        - Klik OK dan lihat berapa banyak duplikasi yang dihapus.

2. Penanganan Nilai Kosong (Missing Data)
    - Identifikasi Nilai Kosong:
        - Gunakan fitur Filter untuk mencari baris yang memiliki nilai kosong di salah satu kolom.

    - Pengisian atau Penghapusan:
        - Jika memungkinkan, isi nilai kosong berdasarkan konteks (misalnya, mengganti nilai kosong di kolom jenis_pembayaran dengan "Unknown").
        - Jika nilai kosong tidak bisa diisi dan datanya penting, pertimbangkan untuk menghapus baris tersebut jika tidak terlalu banyak.

3. Pemformatan Tanggal
    - Pastikan Kolom Tanggal Benar:
        - Cek kolom tanggal_transaksi untuk memastikan semua data tanggal diformat dengan benar.
        - Ubah format tanggal jika perlu dengan memilih kolom dan menggunakan format tanggal yang konsisten.

4. Pembersihan Data Teks
    - Pemeriksaan Konsistensi:
        - Pastikan kolom yang berisi teks seperti nama_produk, jenis_pembayaran, dan jenis_pesanan konsisten dalam penulisan (misalnya, semua huruf kecil atau besar, tidak ada spasi ekstra).

    - Penggunaan TRIM dan PROPER:
        - Gunakan fungsi TRIM untuk menghapus spasi ekstra di sekitar teks.
        - Gunakan fungsi PROPER untuk memformat teks menjadi format title case (misalnya, "Indomie Ayam Spesial").

5. Pemeriksaan dan Koreksi Data Angka
    - Cek Konsistensi Angka:
        - Pastikan kolom seperti quantity, harga_jual, dan nilai_penjualan hanya berisi angka dan tidak ada karakter non-numeric.

    - Kalkulasi Ulang Nilai Penjualan:
        - Jika diperlukan, cek konsistensi nilai_penjualan dengan mengalikan quantity dengan harga_jual.

6. Pemeriksaan Kolom Kategori
    - Pastikan Kategori Konsisten:
        - Cek kolom kategori_produk dan jenis_produk untuk memastikan bahwa kategorisasi produk dilakukan dengan konsisten dan benar.

7. Penambahan Kolom Indeks
    - Menambahkan Nomor Baris atau ID:
        - Jika diperlukan, tambahkan kolom yang berisi nomor urut untuk memudahkan referensi pada data.

8. Pengaturan Ulang Kolom
    - Sesuaikan Urutan Kolom:
        - Jika urutan kolom tidak sesuai dengan kebutuhan analisis Anda, atur ulang kolom sesuai dengan alur kerja yang paling nyaman.

Setelah saya menyelesaikan langkah-langkah di atas, dataset akan lebih bersih dan siap untuk dianalisis. Juga kita bisa mulai melakukan eksplorasi data atau analisis lebih lanjut. Jika terdapat langkah yang terlewat ataupun salah dalam penulisan langkah silakan informasikan kembali pada saya 😁