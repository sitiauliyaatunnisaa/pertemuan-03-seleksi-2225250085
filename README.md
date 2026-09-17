# Pertemuan 03 Seleksi Python

Nama: Siti Auliyaatunnisaa  
NIM: 2225250085  
Kelas: 3A  

## Tujuan

Menulis program seleksi `if`, `if-else`, kondisi majemuk, dan `nested if`.

## Cara Menjalankan

Program dijalankan melalui terminal VS Code dari root folder proyek.

### Latihan 1
```bash
python latihan/01_genap_ganjil.py
```
## Hasil Pengujian

### Latihan 1 – Genap/Ganjil

| Input | Keluaran yang Diharapkan | Keluaran Aktual | Status |
|---|---|---|---|
| 8 | 8 adalah bilangan genap | 8 adalah bilangan genap | Berhasil |
| 13 | 13 adalah bilangan ganjil | 13 adalah bilangan ganjil | Berhasil |
| 0 | 0 adalah bilangan genap | 0 adalah bilangan genap | Berhasil |
| -7 | -7 adalah bilangan ganjil | -7 adalah bilangan ganjil | Berhasil |

### Latihan 2 – Membandingkan Dua Bilangan

| Input | Keluaran yang Diharapkan | Keluaran Aktual | Status |
|---|---|---|---|
| (7, 4) | Bilangan pertama lebih besar | Bilangan pertama lebih besar | Berhasil |
| (2, 9) | Bilangan pertama lebih kecil | Bilangan pertama lebih kecil | Berhasil |
| (5, 5) | Kedua bilangan sama | Kedua bilangan sama | Berhasil |
| (-3, -8) | Bilangan pertama lebih besar | Bilangan pertama lebih besar | Berhasil |

### Latihan 3 – Kelulusan Bersyarat

| Nilai | Kehadiran | Keluaran yang Diharapkan | Keluaran Aktual | Status |
|---:|---:|---|---|---|
| 75 | 90% | Lulus | Lulus | Berhasil |
| 59 | 90% | Belum lulus | Belum lulus | Berhasil |
| 75 | 79% | Belum lulus | Belum lulus | Berhasil |
| 60 | 80% | Lulus | Lulus | Berhasil |

### Latihan 4 – Jenis Segitiga

| Input (a, b, c) | Keluaran yang Diharapkan | Keluaran Aktual | Status |
|---|---|---|---|
| (3, 3, 3) | Segitiga sama sisi | Segitiga sama sisi | Berhasil |
| (5, 5, 8) | Segitiga sama kaki | Segitiga sama kaki | Berhasil |
| (3, 4, 5) | Segitiga sembarang | Segitiga sembarang | Berhasil |
| (1, 2, 3) | Ketiga sisi tidak membentuk segitiga | Ketiga sisi tidak membentuk segitiga | Berhasil |

### Tugas – Analisis Persamaan Kuadrat

| Input (a, b, c) | Keluaran yang Diharapkan | Keluaran Aktual | Status |
|---|---|---|---|
| (1, -5, 6) | D = 1, dua akar real: 3 dan 2 | D = 1.00, x1 = 3.00, x2 = 2.00 | Berhasil |
| (1, 2, 1) | D = 0, akar kembar: -1 | D = 0.00, x = -1.00 | Berhasil |
| (1, 0, 1) | D = -4, tidak ada akar real | D = -4.00, tidak ada akar real | Berhasil |
| (0, 2, 3) | Bukan persamaan kuadrat | Bukan persamaan kuadrat | Berhasil |

## Refleksi

Pada pertemuan ini saya mempelajari penggunaan percabangan dalam Python, mulai dari `if`, `if-else`, kondisi majemuk menggunakan `and` dan `or`, hingga `nested if`. Kesalahan logika yang saya temukan adalah kurang tepat dalam menyusun kondisi pada percabangan, sehingga hasil program dapat tidak sesuai dengan kondisi yang diharapkan. Saya memperbaikinya dengan memeriksa kembali setiap kondisi dan urutan percabangan, kemudian melakukan pengujian menggunakan beberapa data untuk memastikan program menghasilkan keluaran yang benar.