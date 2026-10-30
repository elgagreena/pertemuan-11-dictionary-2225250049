# Pertemuan 11 - Dictionary/Map

Nama: Elga Greena Rahma Tazkia
NIM: 2225250049
Kelas: 3B

## Tujuan

Memodelkan data pendidikan menggunakan dictionary dan pasangan key-value.

## Struktur Data

Dictionary utama menggunakan NIM mahasiswa sebagai key, sedangkan value berupa dictionary bersarang yang berisi nama, kelas, dan nilai mahasiswa.

## Cara Menjalankan

```bash
python3 praktik/data_mahasiswa.py
```

## Test Case

| Input/Aksi                         | Hasil yang Diharapkan              | Hasil Aktual             | Status   |
| ---------------------------------- | ---------------------------------- | ------------------------ | -------- |
| Mencari NIM A003                   | Data mahasiswa Citra ditemukan     | Data Citra ditemukan     | Berhasil |
| Mencari NIM A999                   | Data tidak ditemukan               | Belum diuji              | Belum    |
| Mengubah nilai A002 menjadi 82     | Nilai Budi berubah menjadi 82      | Nilai Budi menjadi 82    | Berhasil |
| Menambahkan data A006              | Data Fajar berhasil ditambahkan    | Data Fajar ditambahkan   | Berhasil |
| Menampilkan seluruh data mahasiswa | Seluruh data mahasiswa ditampilkan | Seluruh data ditampilkan | Berhasil |

## Refleksi

Kesalahan akses key yang ditemukan adalah ketika mencoba mengakses NIM yang tidak tersedia menggunakan tanda kurung siku, sehingga dapat menyebabkan KeyError. Kesalahan tersebut diperbaiki dengan menggunakan method get() agar program dapat mengambil data dengan aman dan mengembalikan None jika NIM tidak ditemukan.
