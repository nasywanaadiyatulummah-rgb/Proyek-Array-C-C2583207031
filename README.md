# SISTEM MONITORING STOK DAN PENJUALAN KANTIN KAMPUS

## Identitas Mahasiswa
- **Nama:** Nasywaa Naadiyatulummah
- **NIM:** C2583207031
- **Kelas:** PTI3B
- **Mata Kuliah:** Algoritma dan Pemrograman Lanjutan
- **Dosen Pengampu:** Taofik Muhammad, M.Kom

## Deskripsi Proyek
Aplikasi berbasis bahasa C untuk mengelola stok dan penjualan produk kantin kampus menggunakan array.

## Fitur Program
1. Menampilkan daftar produk.
2. Menambahkan produk baru.
3. Mengubah harga dan stok produk.
4. Melakukan transaksi penjualan.
5. Menambahkan stok produk.
6. Mencari produk berdasarkan nama.
7. Mengurutkan produk berdasarkan harga dan jumlah terjual.
8. Menampilkan laporan penjualan.
9. Mengecek stok produk yang kurang dari 5.
10. Menampilkan produk terlaris.

## Penerapan Array
Program menggunakan array sebagai struktur data utama:
- **Array 1 dimensi:** Menyimpan harga, stok, dan jumlah produk terjual.
- **Array karakter 2 dimensi:** Menyimpan nama produk.

Kapasitas maksimal penyimpanan adalah 50 produk dengan minimal 5 produk sebagai data awal.

## Cara Menjalankan Program

### 1. Persiapan
Pastikan GCC sudah terinstal pada komputer.

### 2. Kompilasi Program
Buka terminal pada folder penyimpanan file program, kemudian ketik:

```bash
gcc main.c -o kantin
```

### 3. Menjalankan Program

Untuk Windows:
```bash
kantin.exe
```

Untuk Linux:
```bash
./kantin
```

## Dokumentasi Pengujian

### 1. Menambahkan Produk
![Tambah Produk](screenshots/tambah-produk.png)

### 2. Transaksi Penjualan
![Transaksi](screenshots/transaksi.png)

### 3. Pembaruan Stok
![Pembaruan Stok](screenshots/pembaruan-stok.png)

### 4. Pengujian Stok Tidak Cukup
![Stok Tidak Cukup](screenshots/stok-tidak-cukup.png)

### 5. Laporan Penjualan
![Laporan Penjualan](screenshots/laporan-penjualan.png)

### 6. Pengurutan Produk
![Pengurutan](screenshots/pengurutan.png)

### 7. Pencarian Produk dan Pengecekan Stok
![Pencarian dan Stok](screenshots/pencarian-stok.png)

---

**Universitas Muhammadiyah Tasikmalaya**  
Program Studi Pendidikan Teknologi Informasi  
Tahun Akademik 2026/2027
