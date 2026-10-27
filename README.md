# Pertemuan 12 - File I/O dan Error Handling

Nama: Fani Pratiwi Nur Indah
NIM: 2225250175
Kelas: 3B

## Tujuan
Membaca, memvalidasi, mengolah, dan menulis data file dengan Python.

## Format File Input
NIM,nilai

Contoh:
A001,85
A002,78
A003,92
A004,abc
A005,74
A006,88

## Cara Menjalankan
python3 tugas/rekap_nilai_file.py

## Error yang Ditangani
- FileNotFoundError
- ValueError

## Test Case
1. Normal: semua baris valid diproses.
2. File hilang: program menampilkan pesan file tidak ditemukan.
3. Nilai invalid: baris yang tidak valid dilewati.
4. Baris kosong: baris kosong dilewati.
5. Batas lulus: nilai 60 dihitung sebagai lulus.

## Refleksi
Error yang ditemukan adalah ValueError ketika nilai berisi teks.
Program menangani error tersebut dengan try-except sehingga
baris yang tidak valid dilewati dan data lainnya tetap diproses.