Monthly Budgeting App

## Deskripsi Proyek
Monthly Budgeting App adalah aplikasi pengelola anggaran bulanan yang dirancang untuk membantu pengguna mengatur pemasukan dan pengeluaran berdasarkan kategori tertentu. Aplikasi ini bertujuan membantu pengguna mengontrol kondisi keuangan pribadi melalui pencatatan transaksi, pemantauan anggaran, dan sistem peringatan ketika pengeluaran mendekati batas yang telah ditentukan.
Proyek ini dikembangkan sebagai tugas mata kuliah Rekayasa Perangkat Lunak (RPL).

---

## Latar Belakang
Banyak mahasiswa dan pekerja muda mengalami kesulitan mengelola keuangan bulanan karena pengeluaran tidak tercatat dengan baik. Akibatnya, anggaran sering habis sebelum akhir bulan dan pengguna tidak mengetahui kategori pengeluaran mana yang paling banyak menghabiskan dana.
Aplikasi ini hadir sebagai solusi sederhana untuk membantu pengguna mengontrol pengeluaran dan membangun kebiasaan pengelolaan keuangan yang lebih baik.

---

## Tujuan
* Membantu pengguna mencatat pemasukan dan pengeluaran.
* Membantu pengguna mengatur anggaran berdasarkan kategori.
* Memberikan peringatan ketika pengeluaran mendekati batas anggaran.
* Menyediakan ringkasan kondisi keuangan bulanan.

---

## Target Pengguna
* Mahasiswa
* Anak kos
* Pekerja muda
* Pengguna yang ingin mengelola keuangan pribadi

---

## Fitur Utama
### 1. Manajemen Pemasukan
* Menambahkan pemasukan bulanan.
* Menampilkan total pemasukan.

### 2. Manajemen Pengeluaran
* Menambahkan data pengeluaran.
* Mengelompokkan pengeluaran berdasarkan kategori.

### 3. Pengaturan Anggaran
* Menentukan batas anggaran setiap kategori.
Contoh kategori:
* Makanan
* Transportasi
* Kos
* Hiburan
* Lainnya

### 4. Monitoring Anggaran
* Menampilkan persentase penggunaan anggaran.
* Menampilkan sisa anggaran.

### 5. Peringatan Anggaran
* Memberikan notifikasi ketika pengeluaran mencapai 80% dari batas kategori.

### 6. Laporan Bulanan
* Total pemasukan.
* Total pengeluaran.
* Sisa saldo.
* Statistik pengeluaran per kategori.

---

## Fitur yang Tidak Termasuk pada Versi Pertama
* Integrasi e-wallet.
* Integrasi rekening bank.
* Notifikasi WhatsApp.
* Prediksi pengeluaran menggunakan AI.
* Sinkronisasi multi-perangkat.
* OCR struk belanja.

---

## Teknologi yang Direncanakan
### Frontend
* HTML
* CSS
* JavaScript

### Backend
* FastAPI (Python)

### Database
* MySQL

---

## Metodologi Pengembangan
Metode pengembangan yang digunakan:
* Requirement Analysis
* System Design
* Implementation
* Testing
* Deployment
Pendekatan pengembangan mengikuti prinsip dasar Rekayasa Perangkat Lunak (RPL).

---

## Struktur Data Awal
### User
* id
* nama
* email
* password

### Category
* id
* nama_kategori
* batas_anggaran

### Income
* id
* user_id
* jumlah
* tanggal

### Expense
* id
* user_id
* category_id
* jumlah
* tanggal
* keterangan

---

## Kriteria Keberhasilan
Aplikasi dinyatakan berhasil apabila:
1. Pengguna dapat mencatat pemasukan dan pengeluaran.
2. Sistem dapat menghitung sisa saldo secara otomatis.
3. Pengeluaran dapat dikelompokkan berdasarkan kategori.
4. Sistem dapat menampilkan peringatan saat penggunaan anggaran mencapai 80%.
5. Laporan bulanan dapat ditampilkan dengan benar.

---

## Status Proyek
Planning & Requirement Analysis
Proyek masih berada pada tahap perencanaan dan analisis kebutuhan sistem.
