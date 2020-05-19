
#### By Anon_R7
All in one tool for **Information Gathering** and **Vulnerability Scanning**

# Scans That You Can Perform Using Anon_R7 :
+ Basic Scan
	- Site Title **NEW**
	- IP Address
	- Web Server Detection `IMPROVED`
	- CMS Detection
	- Cloudflare Detection
	- robots.txt Scanner
+ Whois Lookup `IMPROVED`
+ Geo-IP Lookup
+ Grab Banners `IMPROVED`
+ DNS Lookup
+ Subnet Calculator
+ Nmap Port Scan
+ Sub-Domain Scanner `IMPROVED`
	- Sub Domain
	- IP Address
+ Reverse IP Lookup & CMS Detection `IMPROVED`
	- Hostname
	- IP Address
	- CMS
+ Error Based SQLi Scanner
+ Bloggers View **NEW**
	- HTTP Response Code
	- Site Title
	- Alexa Ranking
	- Domain Authority
	- Page Authority
	- Social Links Extractor
	- Link Grabber
+ WordPress Scan **NEW**
	- Sensitive Files Crawling
	- Version Detection
	- Version Vulnerability Scanner
+ Crawler
+ MX Lookup **NEW**
+ Scan For Everything - _The Old Lame Scanner_

---
# Released Versions:
    - Version 1.0.0 [11-06-2017]
    - Version 1.1.0 [15-06-2017]
    - Version 2.0.0 [11-08-2017]

# Changelog:
- Version 1.0.0
    - Initial Launch
- Version 1.1.0
    - Updated The `fix` command
- Version 2.0.0
	- Separated all scans so that you are served the amount of information you need
	- `Sub-Domain Scanner` improved
	- `fix` command improved
	- `Web Server Detection` Improved
	- `CMS Detection` Improved
	- `Banner Grabbing` Improved
	- Added `WordPress Scanner`
	- Added `Bloggers View`
	- Added `MX Lookup`
	- Added `Update` option
	- Anon_R7 Banner Updated
	- Many Other Internal Fixes

# Installation:
1. Run The Tool and Type `fix` This will Install All Required Modules.
2. For The Bloggers View To Work Properly you have to configure Anon_R7 with moz.com's api keys for that follow the following steps:

**How To Configure Anon_R7 with moz.com for Bloggers View Scan**
+ Create an account in moz follow this link : https://moz.com/community/join
+ After successful account creation and completing the verification you need to generate the API Keys
+ You can get your API Keys here: https://moz.com/products/mozscape/access
+ Get your AccessID and SecretKey and replace the `$accessID` and `$secretKey` variable's value in the `config.php` file
+ All set, now you can enjoy the bloggers view.

# Usage:
- git clone `https://github.com/Tuhinshubhra/RED_HAWK`
- cd RED_HAWK
- php rhawk.php
- Use the "help" command to see the command list or type in the domain name you want to scan (without Http:// OR Https://).
- Select whether The Site Runs On HTTPS or not.
- Select the type of scan you want to perform
- Leave the rest to the scanner

# List of CMS Supported
Anon_R7's `CMS Detector` currently is able to detect the following CMSs (Content Management Systems) in case the website is using some other CMS, Detector will return _could not detect_.

- WordPress
- Joomla
- Drupal
- Magento
# Known Issues
**ISSUE:** Scanner Stops Working After Cloudflare Detection!

**SOLUTION:** Use The `fix` Command OR Manually Install *php-curl* & *php-xml*

Watch The Video TO See How To Solve This Isuue : https://www.youtube.com/watch?v=QuFPY9NFTM8

# Video Demonstration
<a href="https://www.youtube.com/watch?v=Jt9kBFiJDrE" target="_blank"><img src="https://i.imgur.com/SXDWohl.png" 
alt="Video Thumbnail" border="10" /></a>

# Suggestions And Feedbacks
Want to contribute to Anon_R7 or point out something wrong? Just create a new issue here: https://github.com/Tuhinshubhra/RED_HAWK/issues/new
I'd love to hear from you.

# Support and Donations
Found Anon_R7 cool? well you could buy me a cup of tea ;) (no alcohol plz xD) just send any amount of donations (in BTC) to this address : **1NbiQidWWVVhWknsfPSN1MuksF8cbXWCku**

Can't donate? well that's no problem just drop a **THANK YOU** this will motivate me to create more exciting stuffs for you ;)

# TODOs

- Make a proper update option ( Installs current version automatically )
- Add more CMS to the detector
- Improve The WordPress Scanner ( Add User, Theme & Plugins Enumeration )
- Create a web version of the scanner
- Add XSS & LFI Scanner
- Improve the Links grabber thingy under bloggers view
- Add some other scans under the Bloggers View

#### Oleh Anon_R7
Semua dalam satu alat untuk ** Pengumpulan Informasi ** dan ** Pemindaian Kerentanan **

# Pemindaian yang Dapat Anda Lakukan Menggunakan Anon_R7:
+ Pemindaian Dasar
- Judul Situs ** BARU **
- Alamat IP
- Deteksi Server Web `IMPROVED`
- Deteksi CMS
- Deteksi Cloudflare
- robots.txt Scanner
+ Whois Lookup `IMPROVED`
+ Pencarian Geo-IP
+ Raih Spanduk `IMPROVED`
+ Pencarian DNS
+ Subnet Calculator
+ Nmap Port Scan
+ Sub-Domain Scanner `IMPROVED`
- Sub Domain
- Alamat IP
+ Reverse IP Lookup & Deteksi CMS `IMPROVED`
- Nama Host
- Alamat IP
- CMS
+ Pemindai SQLi Berbasis Kesalahan
+ Tampilan Blogger ** BARU **
- Kode Respon HTTP
- Judul situs
- Peringkat Alexa
- Otoritas Domain
- Otoritas Halaman
- Extractor Tautan Sosial
- Tautan Grabber
+ Pindai WordPress ** BARU **
- Merangkak File Sensitif
- Deteksi Versi
- Versi Vulnerability Scanner
+ Crawler
+ Pencarian MX ** BARU **
+ Pindai Segalanya - _Pemindai Lumpuh Lama_

---
# Versi Dirilis:
    - Versi 1.0.0 [11-06-2017]
    - Versi 1.1.0 [15-06-2017]
    - Versi 2.0.0 [11-08-2017]

# Changelog:
- Versi 1.0.0
    - Peluncuran Awal
- Versi 1.1.0
    - Diperbarui Perintah `fix`
- Versi 2.0.0
- Pisahkan semua pemindaian sehingga Anda mendapatkan jumlah informasi yang Anda butuhkan
- `Pemindai Sub-Domain` ditingkatkan
- Perintah `fix` ditingkatkan
- `Deteksi Server Web` Ditingkatkan
- `Deteksi CMS` Ditingkatkan
- `Banner Grabbing` Ditingkatkan
- Menambahkan `WordPress Scanner`
- Menambahkan `Tampilan Blogger`
- Menambahkan `MX Lookup`
- Menambahkan opsi `Perbarui`
- Anon_R7 Banner Diperbarui
- Banyak Perbaikan Internal Lainnya

# Instalasi:
1. Jalankan Alat dan Ketik `fix` Ini akan Menginstal Semua Modul yang Diperlukan.
2. Agar Tampilan Blogger Berfungsi dengan benar, Anda harus mengonfigurasi ELANG MERAH dengan kunci api moz.com untuk itu ikuti langkah-langkah berikut:

** Cara Mengonfigurasi ELANG MERAH dengan moz.com untuk Pemindaian Tampilan Blogger **
+ Buat akun di bulan, ikuti tautan ini: https://moz.com/community/join
+ Setelah pembuatan akun berhasil dan menyelesaikan verifikasi, Anda perlu membuat Kunci API
+ Anda bisa mendapatkan Kunci API Anda di sini: https://moz.com/products/mozscape/access
+ Dapatkan AccessID dan SecretKey Anda dan gantikan nilai variabel `$ accessID` dan` $ secretKey` dalam file `config.php`
+ Semua siap, sekarang Anda dapat menikmati tampilan blogger.

# Penggunaan:
- git klon `https: // github.com / Tuhinshubhra / RED_HAWK`
- cd RED_HAWK
- php rhawk.php
- Gunakan perintah "bantuan" untuk melihat daftar perintah atau ketik nama domain yang ingin Anda pindai (tanpa Http: // ATAU Https: //).
- Pilih apakah Situs Berjalan Pada HTTPS atau tidak.
- Pilih jenis pemindaian yang ingin Anda lakukan
- Serahkan sisanya ke pemindai

# Daftar CMS yang Didukung
`CMS Detector` Anon_R7 saat ini dapat mendeteksi CMS berikut (Sistem Manajemen Konten) jika situs web menggunakan beberapa CMS lain, Detector akan kembali _tidak dapat mendeteksi_.

- WordPress
- Joomla
- Drupal
- Magento
# Masalah Dikenal
** MASALAH: Berhenti Pemindai ** Bekerja Setelah Deteksi Cloudflare!

** SOLUSI: ** Gunakan Perintah `fix` ATAU Instal Secara Manual * php-curl * & * php-xml *

Tonton Video UNTUK Lihat Cara Memecahkan Masalah ini: https://www.youtube.com/watch?v=QuFPY9NFTM8

# Video Demonstrasi
<a href="https://www.youtube.com/watch?v=Jt9kBFiJDrE" target="_blank"> <img src = "https://i.imgur.com/SXDWohl.png"
alt = "Thumbnail Video" border = "10" /> </a>

# Saran dan Masukan
Ingin berkontribusi pada Anon_R7 atau menunjukkan sesuatu yang salah? Buat saja masalah baru di sini: https://github.com/Tuhinshubhra/RED_HAWK/issues/new
Saya ingin sekali mendengar dari Anda.

# Dukungan dan Sumbangan
Apakah Anon_R7 keren? baik Anda bisa membelikan saya secangkir teh;) (tidak ada alkohol, xD) kirimkan saja jumlah sumbangan (dalam BTC) ke alamat ini: ** 1NbiQidWWVVhWknsfPSN1MuksF8cbXWCku **

Tidak bisa menyumbang? nah itu tidak masalah hanya menjatuhkan ** TERIMA KASIH ** ini akan memotivasi saya untuk membuat lebih banyak barang menarik untuk Anda;)

# TODO

- Buat opsi pembaruan yang tepat (Menginstal versi saat ini secara otomatis)
- Tambahkan lebih banyak CMS ke detektor
- Tingkatkan Pemindai WordPress (Tambahkan Pengguna, Tema & Enumerasi Plugin)
- Buat versi web pemindai
- Tambahkan XSS & LFI Scanner
- Tingkatkan tautan grabber di bawah tampilan blogger
- Tambahkan beberapa pemindaian lain di bawah Tampilan Blogger
Kirim masukan
Histori
Disimpan
Komunitas
