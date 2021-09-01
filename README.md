# Wabill

Kirim pesan unik ke banyak nomor sekaligus.

![screenshot app](client/assets/ss-app.png)

## Cara penggunaan:
1. Jalankan server aplikasinya, ada dua cara untuk menjalankan aplikasi ini, menggunakan executable atau clone repo ini dan jalankan dengan `node index.js`.
Untuk menjalankan dengan executable, download aplikasi ini di bagian Release di samping kanan, sesuaikan dengan sistem operasi anda. Setelah itu klik dua kali (untuk windows), dan akan terbuka command prompt. Disitu akan keluar url, buka url tersebut di browser anda (saya pakai google chrome). Lalu scan kode qr nya, setelah aktif, buka halaman client di `url/client` contohnya `http://localhost:8000/client`.
2. Buat data di Google Sheet/Microsoft Excel

![contoh data excell](client/assets/ss1.png)

3. Salin dan tempel data, **Pastikan baris pertama adalah judul kolomnya, dan kolom pertama adalah nomor WhatsApp penerima (dengan format 62xxxxxxxx).**

![baris dan kolom pertama](client/assets/ss2.png)

4. Buat template, bungkus judul kolom dengan simbol **{}**, contoh template (sesuai data diatas):
>Pelanggan Yth,

>Bersama ini kami informasikan tagihan Wabill Anda {nomor} atas nama {nama}, bln tagihan 08-2021 sebesar {tagihan} akan jatuh tempo pada tanggal 05-09-2021.

>Mohon segera lakukan pembayaran agar Wabill Anda tdk terisolir.

>Abaikan notifikasi ini jika sudah melakukan pembayaran.

>Terima kasih
5. Cek preview terlebih dahulu
6. Kirim!

Klik [link ini](https://youtu.be/) untuk melihat panduan instalasi dan penggunaan.

**Aplikasi/tool ini gratis. mohon tidak diperjualbelikan!**

**Saya tidak mencatat/mengumpulkan data dari aplikasi ini.**