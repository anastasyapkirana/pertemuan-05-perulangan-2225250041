# Pertemuan 05 - Perulangan for dan while

## Identitas

- Nama: Anastasya Putri Kirana
- NIM: 2225250041
- Kelas: 3A
- Mata Kuliah: Algoritma dan Pemrograman

## Tujuan

Pada pertemuan ini dipelajari penggunaan perulangan `for` dan `while` dalam Python.

Program yang dibuat meliputi:
1. Tabel perkalian
2. Jumlah bilangan 1 sampai n
3. Validasi input nilai
4. Menghitung banyak bilangan genap
5. Deret aritmetika

## Struktur Program

```text
pertemuan-05-perulangan-2225250041/
├── README.md
├── .gitignore
├── latihan/
│   ├── 01_tabel_perkalian.py
│   ├── 02_jumlah_bilangan.py
│   ├── 03_validasi_input.py
│   └── 04_hitung_genap.py
└── kuis/
    └── kuis2_deret_aritmetika.py

## Cara Menjalankan

Program dijalankan melalui terminal VS Code menggunakan perintah:

    python nama_file.py

Contoh:

    python latihan/01_tabel_perkalian.py

Untuk menjalankan Kuis 2:

    python kuis/kuis2_deret_aritmetika.py

## Algoritma Singkat

### 1. Tabel Perkalian

Program menerima sebuah bilangan `n`, kemudian menggunakan perulangan `for` dari 1 sampai 10. Pada setiap perulangan, program menghitung `n × i` dan menampilkannya.

### 2. Jumlah Bilangan

Program menerima nilai `n`, kemudian menggunakan `for` untuk menjumlahkan semua bilangan dari 1 sampai `n`.

Variabel `total` digunakan sebagai penampung hasil penjumlahan.

### 3. Validasi Input

Program menerima nilai antara 0 sampai 100.

Perulangan `while` digunakan selama nilai masih kurang dari 0 atau lebih dari 100. Jika nilai tidak valid, program meminta input kembali.

### 4. Menghitung Bilangan Genap

Program menerima nilai `n`, kemudian melakukan perulangan dari 1 sampai `n`.

Pada setiap bilangan, digunakan kondisi `i % 2 == 0`.

Jika kondisi benar, jumlah bilangan genap ditambah 1.

### 5. Deret Aritmetika

Program menerima:
- `a` sebagai suku pertama
- `d` sebagai beda
- `n` sebagai banyak suku

Jika `n` kurang dari atau sama dengan 0, program meminta input `n` kembali sampai mendapatkan bilangan bulat positif.

Kemudian digunakan `for` sebanyak `n` kali untuk menghasilkan setiap suku deret dan menghitung jumlah seluruh suku.

## Hasil Pengujian

### Latihan 1 - Tabel Perkalian

| Input | Hasil |
|---|---|
| 4 | Tabel perkalian 4 dari 1 sampai 10 |
| -3| Tabel perkalian -3 dari 1 sampai 10 |

### Latihan 2 - Jumlah Bilangan

| Input | Hasil |
|---|---:|
| 1 | 1 |
| 5 | 15 |
| 10 | 55 |

### Latihan 3 - Validasi Input

| Input | Hasil |
|---|---|
| 120 | Tidak valid, meminta input kembali |
| -5 | Tidak valid, meminta input kembali |
| 75 | Diterima |

### Latihan 4 - Banyak Bilangan Genap

| Input | Hasil |
|---|---:|
| 1 | 0 |
| 2 | 1 |
| 5 | 2 |
| 10 | 5 |

### Kuis 2 - Deret Aritmetika

| a | d | n | Jumlah |
|---:|---:|---:|---:|
| 2 | 3 | 5 | 40.00 |
| 10 | -2 | 4 | 28.00 |
| 1.5 | 0.5 | 3 | 6.00 |

Pengujian validasi `n` juga dilakukan dengan memasukkan `n = 0`. Program menolak input tersebut dan meminta `n` kembali sampai diberikan bilangan positif.

## Refleksi

Pada pertemuan ini saya mempelajari penggunaan perulangan `for` dan `while` dalam Python. Saya mengetahui bahwa `for` dapat digunakan ketika jumlah perulangan sudah diketahui atau ketika melakukan perulangan pada suatu rentang, sedangkan `while` dapat digunakan ketika perulangan bergantung pada suatu kondisi.

Selain itu, saya belajar menggunakan kondisi `if` di dalam perulangan untuk melakukan pengecekan pada setiap nilai.