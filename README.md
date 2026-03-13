Sistem Manajemen Sepatu – Cibaduyut Shoes

Deskripsi Program
Program ini merupakan aplikasi web sederhana yang dibuat menggunakan framework Laravel untuk mengelola data produk sepatu pada toko Cibaduyut. Sistem ini memungkinkan pengguna untuk melihat daftar sepatu, melakukan login, menyimpan produk ke dalam wishlist, serta menambahkan data sepatu baru melalui form yang tersedia.

Aplikasi ini dibuat sebagai latihan pengembangan Sistem Informasi Berbasis Web dengan menerapkan konsep MVC (Model–View–Controller) yang merupakan arsitektur utama pada Laravel.

Fitur Utama Program
1. Sistem Login
Program menyediakan halaman login yang digunakan untuk melakukan autentikasi pengguna sebelum mengakses sistem.
Login dilengkapi dengan fitur Remember Me yang menggunakan cookie sehingga username dapat tersimpan secara otomatis.

Fitur ini menggunakan:
- Session untuk menyimpan status login
- Cookie untuk menyimpan username

2. Dashboard Sistem
Pada halaman utama terdapat dashboard yang menampilkan ringkasan informasi seperti:
- Jumlah stok sepatu
- Jumlah kategori sepat
- Total produk yang tersedia

Dashboard ini membantu pengguna untuk melihat gambaran kondisi stok secara cepat.

3. Daftar Produk Sepatu
Program menampilkan beberapa produk sepatu dalam bentuk card menggunakan Bootstrap.

Setiap produk menampilkan informasi:
- Gambar sepatu
- Nama sepatu
- Harga
- Jumlah stok

Selain itu terdapat tombol:
- Beli
- Wishlist

4. Wishlist Produk
Pengguna dapat menyimpan sepatu yang diminati ke dalam wishlist.
Wishlist akan ditampilkan dalam bentuk modal popup sehingga pengguna dapat melihat daftar sepatu yang disimpan.

Fitur ini menggunakan JavaScript untuk:
- Menambahkan produk ke wishlist
- Menampilkan jumlah wishlist
- Menghapus seluruh wishlist

5. Form Tambah Sepatu
Program menyediakan form untuk menambahkan data sepatu baru dengan beberapa input seperti:
- Nama sepatu
- Harga sepatu
- Stok sepatu
- Kategori sepatu

Form ini bertujuan untuk mensimulasikan proses input data produk dalam sistem manajemen inventori.

6. Dark Mode
Program memiliki fitur Mode Gelap yang dapat mengubah tampilan website menjadi lebih nyaman dilihat pada kondisi cahaya rendah.

Fitur ini dibuat menggunakan:
- CSS
- JavaScript

