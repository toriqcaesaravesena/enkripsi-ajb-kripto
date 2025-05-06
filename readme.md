# Sistem Enkripsi AJB (Akta Jual Beli)

## Deskripsi

Sistem Enkripsi AJB adalah aplikasi web berbasis PHP yang dirancang untuk mengamankan dokumen Akta Jual Beli melalui proses enkripsi. Aplikasi ini memungkinkan pengguna untuk mengunggah dokumen AJB, mengenkripsi dokumen tersebut menggunakan berbagai algoritma kriptografi, serta mendekripsi kembali dokumen yang telah dienkripsi dengan aman.

## Fitur

- Autentikasi dan otorisasi pengguna
- Upload dokumen AJB
- Enkripsi dokumen menggunakan algoritma Caesar Cipher dan RSA
- Dekripsi dokumen terenkripsi
- Manajemen dokumen AJB terenkripsi
- Tampilan dashboard untuk monitoring

## Teknologi yang Digunakan

- PHP
- MySQL/MariaDB
- HTML5
- CSS3
- JavaScript
- Bootstrap
- Algoritma kriptografi: Caesar Cipher dan RSA

## Penggunaan

1. Akses aplikasi melalui web browser
2. Login menggunakan kredensial yang telah ditentukan
3. Upload dokumen AJB di halaman upload_enkripsi.php
4. Pilih algoritma enkripsi yang diinginkan
5. Proses enkripsi dokumen
6. Lihat hasil enkripsi di halaman hasil_enkripsi.php
7. Untuk dekripsi, gunakan halaman upload_dekripsi.php

## Struktur Proyek

```
/enkripsi-ajb/
    │
    ├── /assets/ # Aset statis (CSS, JS, gambar)
    │ ├── /css/ # File CSS kustom
    │ ├── /js/ # File JavaScript kustom
    │ └── /img/ # Logo atau ikon
    │
    ├── /includes/ # File reusable PHP (fungsi, koneksi DB, dll)
    │ ├── config.php # Konfigurasi database
    │ ├── functions.php # Fungsi enkripsi, dekripsi, dll
    │ └── auth.php # Cek login pengguna
    │
    ├── /uploads/ # Tempat menyimpan file dokumen AJB
    │ ├── /encrypted/ # Hasil file terenkripsi
    │ └── /decrypted/ # Hasil file didekripsi
    │
    ├── /templates/ # Template halaman (header, footer, dll)
    │ ├── header.php
    │ ├── footer.php
    │ └── sidebar.php
    │
    ├── /pages/ # Halaman utama sistem
    │ ├── dashboard.php
    │ ├── upload_enkripsi.php
    │ ├── hasil_enkripsi.php
    │ ├── upload_dekripsi.php
    │ ├── hasil_dekripsi.php
    │ └── login.php
    │
    ├── /algoritma/ # Logika kriptografi
    │ ├── caesar_cipher.php
    │ └── rsa.php
    │
    ├── database.sql # File SQL untuk membuat struktur tabel database
    ├── index.php # Entry point (redirect ke login atau dashboard)
    └── README.md # Dokumentasi proyek
```

## Algoritma Enkripsi yang Digunakan

1. **Caesar Cipher** - Algoritma enkripsi klasik yang melakukan pergeseran karakter
2. **RSA** - Algoritma kriptografi asimetris yang menggunakan pasangan kunci publik dan pribadi
