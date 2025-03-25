# Bookshelf App

Bookshelf App adalah aplikasi web sederhana untuk mengelola daftar buku. Aplikasi ini memungkinkan pengguna untuk menambahkan, memindahkan, menghapus, dan mencari buku. Data buku disimpan di localStorage, sehingga data tetap ada meskipun halaman web ditutup.

Proyek ini merupakan bagian dari tugas kelas Belajar Membuat Front-End Web untuk Pemula di **Dicoding Indonesia.**

## Fitur

- **Menambahkan Buku**: Tambahkan buku baru dengan judul, penulis, tahun, dan status selesai dibaca.
- **Memindahkan Buku**: Pindahkan buku antara rak "Belum selesai dibaca" dan "Selesai dibaca".
- **Menghapus Buku**: Hapus buku dari rak.
- **Mencari Buku**: Cari buku berdasarkan judul.
- **Penyimpanan Lokal**: Data buku disimpan di localStorage browser.

## Teknologi yang Digunakan

- **HTML**: Struktur dasar aplikasi.
- **CSS**: Styling dan tata letak aplikasi.
- **JavaScript**: Logika dan fungsionalitas aplikasi.
- **LocalStorage**: Penyimpanan data buku di browser.

## Hasil Akhir Submission

Ini adalah hasil akhir dari submission setelah melalui proses review dari mentor. Berikut adalah beberapa poin penting yang telah disempurnakan:

- **Validasi Input**: Form input sekarang memastikan bahwa judul, penulis, dan tahun tidak boleh kosong atau invalid.
- **Konfirmasi Hapus Buku**: Pengguna akan diminta konfirmasi sebelum menghapus buku untuk mencegah penghapusan yang tidak disengaja.
- **Pembersihan Kode**: Template bawaan untuk menampilkan data buku dihapus dari HTML karena elemen-elemen tersebut sudah dibuat secara dinamis melalui JavaScript.
- **Pesan Feedback**: Jika rak buku kosong, aplikasi akan menampilkan pesan "Tidak ada buku yang ditemukan".
- **Struktur Kode yang Lebih Baik**: Kode JavaScript diorganisir dengan lebih baik untuk memudahkan pemeliharaan dan penambahan fitur di masa depan.

## Cara Menggunakan

1. **Clone Repository**  
   Clone repository ini ke komputer Anda menggunakan perintah berikut:

   ```bash
   git clone https://github.com/Dzakkiyansyah/bookshelf-app.git
   ```
