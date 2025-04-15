# Tutorial Install Bootstrap dan Webpack

## Prasyarat

Pastikan Node.js sudah terinstal di komputer Anda. Jika belum, unduh dan instal Node.js dari [situs resmi Node.js](https://nodejs.org/).

## Langkah-langkah

### 1. Inisialisasi Proyek

1. Buka terminal.
2. Buat folder proyek baru

### 2. Instal Bootstrap

1. Gunakan npm untuk menginstal Bootstrap:
   ```bash
   npm install bootstrap
   ```

### 3. Instal Webpack

1. Instal Webpack dan Webpack CLI sebagai dependensi pengembang:
   ```bash
   npm install --save-dev webpack webpack-cli
   ```

### 4. Jalankan Build

1. Tambahkan konfigurasi Webpack dan struktur proyek sesuai kebutuhan.
2. Jalankan perintah berikut untuk membangun proyek:
   ```bash
   npm run build
   ```

## Selesai

Bootstrap dan Webpack telah berhasil diinstal. Anda dapat melanjutkan dengan konfigurasi dan pengembangan proyek Anda.

## Langkah Tambahan: Commit, Push, dan Pull ke/dari Repository Git

### 1. Inisialisasi Git di Proyek Anda

1. Buka terminal di folder proyek Anda.
2. Jalankan perintah berikut untuk menginisialisasi Git:
   ```bash
   git init
   ```

### 2. Tambahkan Semua File ke Staging Area

1. Gunakan perintah berikut untuk menambahkan semua file ke staging area:
   ```bash
   git add .
   ```

### 3. Buat Commit

1. Buat commit dengan pesan deskriptif:
   ```bash
   git commit -m "Inisialisasi proyek dengan Bootstrap dan Webpack"
   ```

### 4. Hubungkan ke Repository Remote

1. Buat repository baru di GitHub atau platform Git lainnya.
2. Hubungkan repository lokal Anda ke repository remote:
   ```bash
   git remote add origin <URL-repository-remote>
   ```

### 5. Push ke Repository Remote

1. Push perubahan Anda ke branch utama (biasanya `main` atau `master`):
   ```bash
   git push -u origin main
   ```

### 6. Pull Perubahan dari Repository Remote

1. Jika ada perubahan di repository remote yang ingin Anda ambil, gunakan perintah berikut:

   ```bash
   git pull origin main
   ```

   **Catatan:** Ganti `main` dengan nama branch yang sesuai jika Anda menggunakan branch lain.

### 7. Selesai

Proyek Anda sekarang telah diunggah ke repository remote, dan Anda juga dapat mengambil perubahan terbaru dari repository remote. Anda dapat membagikan URL repository kepada teman atau tim Anda untuk kolaborasi.
