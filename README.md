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

| Input/Aksi                         | Hasil yang Diharapkan              | Hasil Aktual                       | Status   |
| ---------------------------------- | ---------------------------------- | ---------------------------------- | -------- |
| Mencari NIM A003                   | Data mahasiswa Citra ditemukan     | A003: Data Citra ditemukan         | Berhasil |
| Mencari NIM A999                   | Data tidak ditemukan               | A999: Data tidak ditemukan         | Berhasil |
| Mengubah nilai A002 menjadi 82     | Nilai Budi berubah menjadi 82      | Nilai Budi menjadi 82              | Berhasil |
| Menambahkan data A006              | Data Fajar berhasil ditambahkan    | Data Fajar ditambahkan             | Berhasil |
| Menampilkan seluruh data mahasiswa | Seluruh data mahasiswa ditampilkan | Seluruh data A001–A006 ditampilkan | Berhasil |

## Refleksi

Kesalahan akses key yang ditemukan adalah ketika mencari NIM yang tidak tersedia menggunakan tanda kurung siku, yang dapat menyebabkan KeyError. Kesalahan tersebut diperbaiki dengan menggunakan method get() pada fungsi cari_mahasiswa() sehingga pencarian NIM yang tidak tersedia dapat ditangani dan program menampilkan pesan "Data tidak ditemukan".
