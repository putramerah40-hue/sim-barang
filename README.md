# SIM-Barang

Sistem Informasi Manajemen Barang berbasis web untuk mencatat dan memantau inventaris barang (kode, nama, kategori, jumlah, kondisi). Proyek ini dikerjakan bertahap sebagai tugas Praktikum Pemrograman Web.

## Teknologi
- HTML5, CSS3, JavaScript
- PHP Native
- MySQL
- XAMPP (Apache) dan Git/GitHub

## Konsep HTTP Request dan Response
HTTP adalah protokol komunikasi antara klien (browser) dan server web.

- **HTTP Request**: permintaan yang dikirim browser ke server. Berisi metode (GET untuk mengambil data, POST untuk mengirim data formulir), alamat URL, header, dan kadang body data.
- **HTTP Response**: jawaban dari server. Berisi status code (200 OK, 404 Not Found, 500 Server Error), header, dan isi halaman (HTML, CSS, JS, atau data).

Alur: pengguna membuka alamat di browser, browser mengirim Request, server (Apache + PHP) memproses dan mengambil data dari MySQL bila perlu, lalu mengirim Response yang ditampilkan browser.

## Gambaran Umum Proyek
SIM-Barang akan memiliki fitur:
1. Tabel inventaris barang
2. Formulir input barang dengan validasi
3. Pencarian barang
4. Login admin dan pembatasan akses
5. Penyimpanan data ke database MySQL

## Cara Menjalankan
1. Letakkan folder di `C:\xampp\htdocs\sim-barang`
2. Jalankan Apache di XAMPP
3. Buka `http://localhost/sim-barang`

## Pembuat
Nama: rahmad syaputra - npm 062530801593