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
