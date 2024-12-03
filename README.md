# TEMPLATE PROJECT PRAKTIKUM PPB 4721
<div align="justify">Template ini dirancang untuk mendukung pembelajaran praktikum Pemrograman Perangkat Bergerak (PPB) 4721 dengan menggunakan Flutter sebagai framework utama. Template ini mempermudah pengelolaan proyek praktikum, sekaligus memperkenalkan penggunaan Git untuk version control dan GitHub sebagai platform repository serta alat CI/CD. Dalam repository ini, telah ditambahkan workflow otomatis untuk menghasilkan dokumentasi dalam format PDF serta mengunggahnya ke Google Drive, sehingga memudahkan pengelolaan dan distribusi dokumentasi. Dukungan Anda sangat berarti, cukup dengan memberikan bintang (Star) atau mengikuti profil GitHub saya untuk membantu saya, yang kurang mahir dalam mempromosikan diri di media sosial. Selamat belajar! 🎉</div>


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
1. Pastikan Anda sudah login ke GitHub dan telah mengaktifkan 2FA (Two-Factor Authentication), karena ini merupakan syarat wajib untuk menjalankan GitHub Actions.
2. Tekan tombol **Star** di pojok kanan atas repository ini sebagai bentuk dukungan Anda.
   ![Screenshot](https://github.com/user-attachments/assets/692b1574-7861-4d53-beee-0a5b15b96c1b)
3. Buat repository baru menggunakan template ini dengan cara klik **Use this template** -> **Create a new repository**.
   ![Screenshot](https://github.com/user-attachments/assets/d4f79066-475a-4e3f-a0fd-752d95070e67)
   ![Screenshot](https://github.com/user-attachments/assets/fa03d6aa-db0b-4a93-a732-184c1769c82d)
4. Isi field **Repository name** sesuai keinginan Anda.
   ![Screenshot](https://github.com/user-attachments/assets/1ba54b50-2cc3-4b9c-9eba-54cf0d36cf94)
5. Pastikan visibilitas repository diatur sebagai **Public** agar fitur GitHub Pages dapat digunakan.
   ![Screenshot](https://github.com/user-attachments/assets/6049a0e8-4dbf-4c82-a2c3-7ad413e7bd99)
6. Tekan tombol **Create repository** untuk menginisialisasi repository.
   ![Screenshot](https://github.com/user-attachments/assets/e6c55edd-a0c2-4f65-91b1-e7b9dbdca334)
7. Tunggu hingga GitHub selesai membuat repository.
   ![Screenshot](https://github.com/user-attachments/assets/0dd2efdc-e72d-4b1c-a136-bf686e37422d)
8. Buka menu **Settings** untuk menyesuaikan pengaturan repository.
   ![Screenshot](https://github.com/user-attachments/assets/dd616b09-2701-49d4-83f4-2c51fa50c704)
9. Klik dropdown **Secrets and variables**.
   ![Screenshot](https://github.com/user-attachments/assets/6b5692b5-7f50-4fb5-a3e5-714b3818b8ae)
10. Pilih opsi **Actions**.
    ![Screenshot](https://github.com/user-attachments/assets/4ad8c8a1-a309-4559-ab4c-cfc45d8fb805)
11. Buka tab **Variables**.
    ![Screenshot](https://github.com/user-attachments/assets/8e27d28b-79af-44c8-8706-cff9be08e699)
12. Klik tombol **New repository variable**.
    ![Screenshot](https://github.com/user-attachments/assets/1079616d-e411-4281-bacb-72e47510d6ca)
13. Isi field **Name** dengan `NAMA` dan **Value** dengan nama Anda, lalu tekan **Add variable**.
    ![Screenshot](https://github.com/user-attachments/assets/9ad13a0a-b78b-46d9-940c-2c42d02418a0)
14. Tekan tombol **New repository variable** kembali.
    ![Screenshot](https://github.com/user-attachments/assets/0ba47f6b-abd1-4d91-8d7a-4d7d23d7d778)
15. Isi field **Name** dengan `NIM` dan **Value** dengan NIM Anda, lalu tekan **Add variable**.
    ![Screenshot](https://github.com/user-attachments/assets/4e4620f9-a774-4b60-b436-58e344afd9aa)
16. Buka menu **Pages** di sidebar.
    ![Screenshot](https://github.com/user-attachments/assets/13cb89cf-397d-49b4-b615-0432d9875b72)
17. Ubah dropdown **Source** menjadi **GitHub Actions**.
    ![Screenshot](https://github.com/user-attachments/assets/b7e4a920-f2bf-417c-ab54-b0b4dbf42077)
18. Kembali ke dashboard repository dengan mengklik nama repository di bagian atas.
    ![Screenshot](https://github.com/user-attachments/assets/91226ff5-ef0b-4a23-8d08-562240aba7a5)
19. Buka menu pengaturan detail dengan menekan **Settings**.
    ![Screenshot](https://github.com/user-attachments/assets/412f676c-8a60-44a6-ba9d-1bf2f4be8a41)
20. Centang opsi **Use your GitHub Pages website**, lalu tekan **Save changes**.
    ![Screenshot](https://github.com/user-attachments/assets/be2fa88d-9a8b-4b8f-8f4c-f40cedbdbdaa)
21. Tunggu hingga ikon **Pending** berubah menjadi tanda centang.
    ![Screenshot](https://github.com/user-attachments/assets/42256965-8ae5-4e87-b533-b58b61dc3057)
22. Klik link di bawah **About** untuk melihat dokumentasi yang telah dibuat.
    ![Screenshot](https://github.com/user-attachments/assets/794c0e70-8415-433b-9083-50acf9698fb6)
## Integrasi dengan Google Drive (opsional)
1. Akses Google Cloud Console  
Buka [https://console.cloud.google.com/](https://console.cloud.google.com/) di browser Anda.

2. Navigasi ke APIs & Services  
Klik **APIs & Services** pada menu utama.  
![APIs & Services](https://github.com/user-attachments/assets/ad2485a7-b1c6-44a3-b823-9d3ff215a6df)

3. Buat Proyek Baru  
Klik tab **Credentials** kemudian tekan tombol **Create Project**.  
![Create Project](https://github.com/user-attachments/assets/4ef0f9b2-8ddb-474c-b243-f296a50ef2a3)

4. Masukkan Nama Proyek  
Tulis nama proyek pada kolom **Project Name**, kemudian tekan tombol **Create**.  
![Project Name](https://github.com/user-attachments/assets/2aebde58-242e-46c2-afc2-404472aa5a9d)

5. Tunggu Proyek Selesai Dibuat  
Tunggu hingga proses pembuatan proyek selesai.  
![Project Created](https://github.com/user-attachments/assets/a7540da9-919b-407a-af01-1fb240fcaf45)

6. Kelola Service Accounts  
Klik **Manage Service Accounts** untuk mengelola akun layanan.  
![Manage Service Accounts](https://github.com/user-attachments/assets/0acda535-d0be-4c3c-bd8e-29721c7f44e7)

7. Buat Service Account Baru  
Klik **Create Service Account** untuk membuat akun layanan baru.  
![Create Service Account](https://github.com/user-attachments/assets/10620e99-5328-4e56-8568-42d31018c192)

8. Isi Nama Akun Layanan  
Isi kolom **Service Account Name**, salin alamat email, dan klik **Done**.  
![Service Account Name](https://github.com/user-attachments/assets/91400742-89b9-4f21-9936-1b0ba534ce32)  
![Copy Email Address](https://github.com/user-attachments/assets/b2c653cc-ab3b-4c1b-a31f-3c3cb54f8b1d)

9. Kelola Kunci Akun Layanan  
Klik **Action** pada akun layanan yang dibuat, lalu pilih **Manage Keys**.  
![Manage Keys](https://github.com/user-attachments/assets/4f10c200-af0e-409e-9b45-53638975e334)

10. Buat Kunci Baru  
Tekan **Add Key**, pilih **Create New Key**, dan pilih tipe **JSON**.  
![Add Key](https://github.com/user-attachments/assets/49e5a28b-9b41-4ac9-a24e-4512fd2bec57)  
![Select JSON](https://github.com/user-attachments/assets/fad19020-031f-4e45-a924-9a27ff684bea)

11. Simpan File JSON  
File JSON akan diunduh otomatis. Simpan file ini dengan aman.

12. Berikan Akses ke Google Drive  
Buka folder Google Drive, klik **Dibagikan**, tambahkan alamat email akun layanan sebagai editor, dan tekan **Bagikan**.  
![Share Folder](https://github.com/user-attachments/assets/7db494b9-a019-4cb9-95dd-553780090c0e)  
![Add Editor](https://github.com/user-attachments/assets/9f520e7f-2d5e-4d71-b86a-6bf324ecc9c9)

13. Salin Folder ID Google Drive  
Salin bagian **Folder ID** dari URL folder. Contoh:  
`https://drive.google.com/drive/u/1/folders/1jTQi9ApagFOppBTYl9Q0bAiiSf6R1yi7`  
Folder ID adalah: `1jTQi9ApagFOppBTYl9Q0bAiiSf6R1yi7`.

14. Tambahkan Secrets di GitHub  
Buka menu **Settings** di GitHub, pilih **Actions**, dan klik **New Repository Secret**.  
![New Repository Secret](https://github.com/user-attachments/assets/db1ffecb-4311-44d4-ba29-2361e184abf8)  

Isi:  
- **Name**: `FOLDER_ID`  
- **Secret**: Folder ID yang disalin sebelumnya.  

Klik **Add Secret**.  
![Add Folder ID](https://github.com/user-attachments/assets/55a84830-a120-4a32-a3ff-18622c9462d8)

15. Encode File JSON ke Base64  
Gunakan perintah berikut di terminal:  
`base64 <nama_file>.json > encoded_credentials.txt`  
Salin isi file `encoded_credentials.txt`.

16. Tambahkan Secret untuk Credentials  
Tambahkan secret baru:  
- **Name**: `CREDENTIALS`  
- **Secret**: Hasil Base64 encode.  

Klik **Add Secret**.  
![Add Credentials Secret](https://github.com/user-attachments/assets/8d3d5626-5e52-4ddd-9c7a-eba8e9d27822)

17. Selesai  
Setiap kali Anda melakukan push ke repositori, GitHub Actions akan membuat file PDF dan mengunggahnya ke Google Drive.


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
