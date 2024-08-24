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

---

## Hasil Analisa KPI

[!Image KPI](KPI.png)

Warung makan sederhana yang akrab disebut "Warmindo." Selama beberapa waktu, Warmindo telah menjadi tempat favorit bagi banyak orang untuk menikmati berbagai hidangan mie instan yang lezat. Dengan pelayanan yang ramah dan suasana yang nyaman, Warmindo tidak hanya menyajikan makanan, tetapi juga menciptakan pengalaman yang tak terlupakan bagi pelanggannya. <br />

Dari sekian banyak transaksi yang tercatat, Warmindo berhasil mengumpulkan total penjualan sebesar **Rp 9.202.000**. Angka ini bukan sekadar jumlah, melainkan cerminan dari kepercayaan dan kepuasan yang diberikan oleh pelanggan. Setiap kali pelanggan datang, mereka tahu bahwa mereka akan mendapatkan rasa yang konsisten dan pelayanan yang cepat, yang membuat mereka kembali lagi dan lagi. <br />

Selama periode ini, Warmindo melayani **499** transaksi. Setiap transaksi adalah bukti bahwa warung ini berhasil mempertahankan aliran pelanggan yang stabil. Mereka datang dari berbagai tempat, entah itu untuk sekadar makan siang cepat atau mengisi waktu bersama teman di sore hari. Dalam setiap transaksi, pelanggan menghabiskan rata-rata **Rp 18.441**. Ini menunjukkan bahwa harga yang ditawarkan oleh Warmindo sesuai dengan nilai yang dirasakan oleh pelanggan—tidak terlalu mahal, namun tetap memberikan kualitas yang baik. <br />

Di antara berbagai menu yang ditawarkan, **Indomie Rasa Soto Betawi** menjadi primadona. Pelanggan tampaknya tidak bisa menolak kelezatan kuah soto yang kaya akan rempah, berpadu sempurna dengan mie yang kenyal. Keberhasilan produk ini mungkin bisa menjadi inspirasi bagi Warmindo untuk mencoba varian menu lain yang serupa atau bahkan meningkatkan promosi untuk produk-produk sejenis. <br />

Dalam hal metode pembayaran, mayoritas pelanggan lebih memilih untuk membayar secara tunai **(CASH)**. Meski di zaman serba digital ini banyak pilihan pembayaran yang tersedia, ternyata pelanggan Warmindo masih lebih nyaman dengan cara yang tradisional. Ini menjadi catatan penting bagi Warmindo, apakah mereka perlu memperkenalkan lebih banyak opsi pembayaran digital, atau justru fokus memberikan pelayanan terbaik untuk transaksi tunai. <br />

Yang menarik, kebanyakan pelanggan lebih memilih untuk makan di tempat **(Dine-In)** daripada memesan untuk dibawa pulang atau diantar. Ini menunjukkan bahwa Warmindo tidak hanya menjadi tempat makan, tetapi juga tempat berkumpul dan bersosialisasi. Pelanggan datang untuk merasakan atmosfer kedai yang hangat dan bersahabat, selain menikmati makanannya 😄. <br />

Dengan semua data ini, Warmindo tidak hanya memahami apa yang disukai oleh pelanggan, tetapi juga bagaimana mereka bisa terus meningkatkan pengalaman yang diberikan. Ini membuktikan bahwa sebuah warung kecil pun bisa menjadi favorit di hati banyak orang 😎. <br />

---

Diatas adalah hasil analisa yang saya buat dengan menerapkan konsep layaknya bercerita, jika terdapat bahasa yang kurang pas silakan infokan pada saya dengan memberikan **Issues** pada repo ini atau bisa juga komen pada postingan LinkedIn saya mengenai pembahasan Excel, Terima kasih dan sampai jumpa pada project selanjutnya 🤗