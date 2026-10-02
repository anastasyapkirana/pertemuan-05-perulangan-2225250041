# Pertemuan 05 Perulangan for dan while

Nama: Anastasya Putri Kirana
NIM: 2225250041
Kelas: 3A

## Tujuan

Mempelajari penggunaan perulangan `for` dan `while` dalam Python serta menerapkannya pada perhitungan, validasi input, dan deret aritmetika.

## Cara Menjalankan

### Latihan 1
python latihan/01_tabel_perkalian.py

### Latihan 2
python latihan/02_jumlah_bilangan.py

### Latihan 3
python latihan/03_validasi_input.py

### Latihan 4
python latihan/04_hitung_genap.py

### Kuis 2
python kuis/kuis2_deret_aritmetika.py

## Algoritma

### Latihan 1 - Tabel Perkalian

Program menerima bilangan `n`, kemudian menggunakan perulangan `for` dari 1 sampai 10 untuk menampilkan hasil perkalian `n` dengan setiap bilangan.

### Latihan 2 - Jumlah Bilangan

Program menerima nilai `n`, kemudian menggunakan perulangan `for` untuk menjumlahkan bilangan dari 1 sampai `n`. Variabel `total` digunakan untuk menyimpan hasil penjumlahan.

### Latihan 3 - Validasi Input

Program menerima nilai antara 0 sampai 100. Perulangan `while` digunakan untuk meminta input kembali selama nilai yang dimasukkan masih kurang dari 0 atau lebih dari 100.

### Latihan 4 - Banyak Bilangan Genap

Program melakukan perulangan dari 1 sampai `n`. Setiap bilangan diperiksa menggunakan kondisi `i % 2 == 0`. Jika bilangan genap, jumlah bilangan genap ditambah 1.

### Kuis 2 - Deret Aritmetika

Program menerima suku pertama `a`, beda `d`, dan banyak suku `n`. Jika `n` kurang dari atau sama dengan 0, program meminta input kembali. Setelah mendapatkan `n` yang valid, program menggunakan perulangan `for` untuk menghasilkan setiap suku dan menghitung jumlah seluruh suku.

## Hasil Pengujian

### Latihan 1 - Tabel Perkalian

| Input | Hasil |
|---:|---|
| 4 | Tabel perkalian 4 dari 1 sampai 10 |
| -3 | Tabel perkalian -3 dari 1 sampai 10 |

### Latihan 2 - Jumlah Bilangan

| Input | Hasil |
|---:|---:|
| 1 | 1 |
| 5 | 15 |
| 10 | 55 |

### Latihan 3 - Validasi Input

| Input | Hasil |
|---:|---|
| 120 | Tidak valid, meminta input kembali |
| -5 | Tidak valid, meminta input kembali |
| 75 | Diterima |

### Latihan 4 - Banyak Bilangan Genap

| Input | Hasil |
|---:|---:|
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

Pada pertemuan ini saya mempelajari penggunaan perulangan `for` dan `while` dalam Python. Saya mengetahui bahwa `for` dapat digunakan ketika jumlah perulangan atau rentang sudah diketahui, sedangkan `while` digunakan ketika perulangan bergantung pada suatu kondisi.

Saya juga mempelajari penggunaan variabel penampung seperti `total` untuk menyimpan hasil selama proses perulangan serta penggunaan `if` di dalam perulangan untuk melakukan pengecekan kondisi.