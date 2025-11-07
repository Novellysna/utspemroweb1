## utspemroweb1
# Nama: Novellysna Nurziska
# Nim: 312410131
# Kelas: TI. 24. A1


# 📚 Toko Buku Digital
# 🧩 Deskripsi Singkat

Toko Buku Digital adalah website berbasis HTML + CSS + JavaScript murni (tanpa framework) yang berfungsi sebagai simulasi toko buku online.
Website ini memungkinkan pengguna untuk:

Melihat katalog buku digital.

Melakukan checkout pembelian buku.

Melacak status pengiriman (tracking).

Mengakses halaman login, dashboard user, dan halaman admin.

Desain menggunakan tema cerah profesional (putih–biru pastel) dengan gaya sederhana namun modern.
Seluruh data bersifat dummy (contoh) dan disimpan secara lokal di file data.js.

# 📂 Struktur Folder dan File
web bookstore/
│── index.html        → Halaman login utama
│── dashboard.html    → Halaman utama setelah login (menu & katalog buku)
│── stok.html         → Halaman daftar buku / katalog
│── checkout.html     → Halaman checkout pembelian buku
│── tracking.html     → Halaman pelacakan status pengiriman
│── js/
│   ├── data.js       → Data dummy (akun, katalog, tracking)
│   ├── script.js     → Logika login, session, validasi form
│   └── tracking.js   → Logika pelacakan pengiriman
│── css/
│   └── style.css     → Desain tampilan utama (warna putih–biru pastel)
│── README.md         → Dokumentasi proyek

# 🔐 Login

Gunakan akun contoh berikut untuk masuk ke sistem (tersimpan di data.js):

Role	Email	Password
Admin	admin@bookstore.com
	admin
User	user@bookstore.com
	user
# 🧭 Dashboard

Menampilkan:

Menu cepat: stok, tracking, laporan, dan history

Rekomendasi buku untuk pengguna

Tombol Checkout untuk langsung menuju halaman pembayaran

# 🚚 Tracking Pengiriman

Halaman tracking.html digunakan untuk mengecek status pengiriman buku.
Pengguna dapat memasukkan nomor DO untuk melihat progres pengiriman.

Fitur pada halaman ini:

Tampilan timeline progres pengiriman

Waktu dan deskripsi status dikemas dalam kartu biru muda

Tombol “Kembali ke Dashboard” untuk memudahkan navigasi

# 🎨 Desain dan Warna

Tampilan website menggunakan tema modern dan bersih dengan perpaduan warna biru pastel dan putih.

Palet Warna:

Warna utama: #1976d2 → biru pastel (untuk elemen penting & garis timeline)

Warna sekunder: #42a5f5 → biru muda (untuk tombol dan aksen)

Latar belakang: #ffffff → putih bersih

Aksen elemen: #e3f2fd → biru muda lembut untuk kotak status

Gaya Desain:

Box dan tombol memiliki radius lembut dan bayangan ringan.

Desain responsif, menyesuaikan layar mobile & desktop.

Font utama: Open Sans.

Warna biru memberikan kesan profesional dan tenang, cocok untuk tema pelacakan dan toko buku digital.

# 💾 Catatan

Ini dibuat untuk keperluan pembelajaran UTS Pemrograman Web 1
