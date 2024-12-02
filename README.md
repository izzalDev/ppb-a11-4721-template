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
<img width="1280" alt="Screenshot 2024-12-02 at 13 21 43" src="https://github.com/user-attachments/assets/692b1574-7861-4d53-beee-0a5b15b96c1b">
3. Buat repository baru dengan template repository ini, dengan cara klik "Use this template" -> "Create a new repository"
<img width="1280" alt="Screenshot 2024-12-02 at 13 13 54" src="https://github.com/user-attachments/assets/d4f79066-475a-4e3f-a0fd-752d95070e67">
<img width="1280" alt="Screenshot 2024-12-02 at 13 14 01" src="https://github.com/user-attachments/assets/fa03d6aa-db0b-4a93-a732-184c1769c82d">
4. Tulis nama repository sesuai keinginan pada field "Repository name"
<img width="1280" alt="Screenshot 2024-12-02 at 13 14 24" src="https://github.com/user-attachments/assets/1ba54b50-2cc3-4b9c-9eba-54cf0d36cf94">
5. Pastikan visibilitas repository sebagai "Public" agar fitur github pages nantinya bisa digunakan
<img width="1280" alt="Screenshot 2024-12-02 at 13 14 32" src="https://github.com/user-attachments/assets/6049a0e8-4dbf-4c82-a2c3-7ad413e7bd99">
6. Tekan "Create repository" untuk menginisiasi repository
<img width="1280" alt="Screenshot 2024-12-02 at 13 14 38" src="https://github.com/user-attachments/assets/e6c55edd-a0c2-4f65-91b1-e7b9dbdca334">
7. Tunggu Github selesai membuat repositori
<img width="1280" alt="Screenshot 2024-12-02 at 13 14 44" src="https://github.com/user-attachments/assets/0dd2efdc-e72d-4b1c-a136-bf686e37422d">
8. tekan tombol "settings" untuk menyesuaikan repositori
<img width="1280" alt="Screenshot 2024-12-02 at 13 15 11" src="https://github.com/user-attachments/assets/dd616b09-2701-49d4-83f4-2c51fa50c704">

<img width="1280" alt="Screenshot 2024-12-02 at 13 17 41" src="https://github.com/user-attachments/assets/6b5692b5-7f50-4fb5-a3e5-714b3818b8ae">

<img width="1280" alt="Screenshot 2024-12-02 at 13 17 45" src="https://github.com/user-attachments/assets/4ad8c8a1-a309-4559-ab4c-cfc45d8fb805">
<img width="1280" alt="Screenshot 2024-12-02 at 13 17 52" src="https://github.com/user-attachments/assets/8e27d28b-79af-44c8-8706-cff9be08e699">
<img width="1280" alt="Screenshot 2024-12-02 at 13 17 59" src="https://github.com/user-attachments/assets/1079616d-e411-4281-bacb-72e47510d6ca">
<img width="1280" alt="Screenshot 2024-12-02 at 13 18 29" src="https://github.com/user-attachments/assets/9ad13a0a-b78b-46d9-940c-2c42d02418a0">

<img width="1280" alt="Screenshot 2024-12-02 at 13 18 40" src="https://github.com/user-attachments/assets/0ba47f6b-abd1-4d91-8d7a-4d7d23d7d778">

<img width="1280" alt="Screenshot 2024-12-02 at 13 19 03" src="https://github.com/user-attachments/assets/4e4620f9-a774-4b60-b436-58e344afd9aa">



kdjsflj
<img width="1280" alt="Screenshot 2024-12-02 at 13 15 20" src="https://github.com/user-attachments/assets/13cb89cf-397d-49b4-b615-0432d9875b72">
<img width="1280" alt="Screenshot 2024-12-02 at 13 15 40" src="https://github.com/user-attachments/assets/b7e4a920-f2bf-417c-ab54-b0b4dbf42077">
<img width="1280" alt="Screenshot 2024-12-02 at 13 19 16" src="https://github.com/user-attachments/assets/91226ff5-ef0b-4a23-8d08-562240aba7a5">


<img width="1280" alt="Screenshot 2024-12-02 at 13 16 00" src="https://github.com/user-attachments/assets/412f676c-8a60-44a6-ba9d-1bf2f4be8a41">

<img width="1280" alt="Screenshot 2024-12-02 at 13 16 05" src="https://github.com/user-attachments/assets/be2fa88d-9a8b-4b8f-8f4c-f40cedbdbdaa">
<img width="1280" alt="Screenshot 2024-12-02 at 13 16 20" src="https://github.com/user-attachments/assets/42256965-8ae5-4e87-b533-b58b61dc3057">
<img width="1280" alt="Screenshot 2024-12-02 at 13 21 00" src="https://github.com/user-attachments/assets/794c0e70-8415-433b-9083-50acf9698fb6">



3. Clone repository yang sudah dibuat
4. Buka projek di Visual Studio Code
5. Pastikan semua rekomendasi extension terinstall
6. Menambahkan Variable ke repositori (optional)

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
