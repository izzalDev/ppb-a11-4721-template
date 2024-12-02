# TEMPLATE PROJECT PRAKTIKUM PPB 4721

## Daftar Isi
1. [Requirements](#requirements)
2. [Instalasi](#instalasi)
3. [Integrasi dengan Google Drive (opsional)](#integrasi-dengan-google-drive-opsional)
4. [Penggunaan](#penggunaan)
   - [Membuat projek baru](#membuat-projek-baru)
   - [Menyimpan projek ke remote repositori](#menyimpan-projek-ke-remote-repositori)
   - [Generate dokumentasi](#generate-dokumentasi)
5. [Kontribusi](#kontribusi)

## Requirements
- Akun Github dan sudah melakukan 2FA (untuk menjalankan Github Action)
- Version Control (Git)
- Flutter SDK
- IDE Visual Studio Code

## Instalasi
1. pastikan anda login di github & sudah melakukan 2fa (wajib sebagai requirement untuk menjalankan github action)
2. Tekan tombol star (bintang) di pojok kanan atas sebagai dukungan anda kepada kami

1. Buat repository baru dengan template repository ini
2. Clone repository yang sudah dibuat
3. Buka projek di Visual Studio Code
4. Pastikan semua rekomendasi extension terinstall
5. Menambahkan Variable ke repositori (optional)

## Integrasi dengan Google Drive (opsional)
1. Buka `https://console.cloud.google.com/` di browser
2. Buat project baru di Google Cloud Console
3. Aktifkan API Google Drive dan buat kredensial OAuth 2.0
4. Unduh file kredensial (biasanya dalam format JSON) dan simpan di dalam projek
5. Instal package `googleapis` dan `googleapis_auth` pada Flutter menggunakan `pub get`
6. Implementasikan autentikasi OAuth 2.0 untuk mengakses Google Drive
7. Konfigurasikan API untuk melakukan operasi yang diinginkan seperti upload, download, atau listing file

## Penggunaan

### Membuat projek baru
1. Buka terminal di Visual Studio Code dan navigasi ke folder dimana projek akan disimpan.
2. Jalankan perintah `flutter create nama_projek` untuk membuat projek Flutter baru.
3. Tambahkan file atau dependensi yang dibutuhkan sesuai dengan template ini.

### Menyimpan projek ke remote repositori
1. Inisialisasi Git di folder projek dengan menjalankan perintah `git init`.
2. Tambahkan remote repository dengan menjalankan perintah `git remote add origin <URL_REPOSITORY>`.
3. Tambahkan perubahan pada repositori dengan `git add .`.
4. Commit perubahan dengan `git commit -m "Initial commit"`.
5. Push ke repositori dengan `git push -u origin master`.

### Generate dokumentasi
1. Gunakan tools seperti `dartdoc` untuk menghasilkan dokumentasi API dari komentar dalam kode.
2. Jalankan perintah `dart doc` di terminal untuk menghasilkan dokumentasi dalam format HTML.
3. Dokumentasi yang dihasilkan dapat ditemukan di folder `doc/api`.

## Kontribusi
1. Fork repository ini dan buat branch baru untuk fitur yang ingin dikembangkan.
2. Lakukan perubahan dan
