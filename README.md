## pertemuan 12 - File I/O dan Error Handling

Nama: Siti Solehah
NIM: 2225250058
Kelas: 3B

## Tujuan

Membaca, memvalidasi, mengolah, dan menulis data file menggunakan Python serta menangani error dasar dengan try-except.

## Struktur File

- "data/catatan.txt": menyimpan catatan teks untuk latihan.
- "data/nilai.txt": menyimpan data NIM dan nilai.
- "data/hasil_rekap.txt": menyimpan hasil rekap nilai.
- "latihan/01_tulis_file.py": menulis data ke file.
- "latihan/02_baca_file.py": membaca isi file.
- "latihan/03_append_file.py": menambahkan data ke file.
- "latihan/04_proses_baris.py": memproses data nilai.
- "latihan/05_file_not_found.py": menangani file yang tidak ditemukan.
- "latihan/06_value_error.py": menangani input yang bukan angka.
- "tugas/rekap_nilai_file.py": membaca dan merekap data nilai.

## Format File Input

Data nilai disimpan dengan format NIM,nilai.

## Contoh:
A001,85
A002,78
A003,92
A004,abc
A005,74
A006,88

## Cara Menjalankan

Jalankan terminal dari folder utama proyek, kemudian gunakan perintah:

"python tugas/rekap_nilai_file.py"

Error yang Ditangani

- "FileNotFoundError": terjadi ketika file tidak ditemukan.
- "ValueError": terjadi ketika nilai tidak dapat dikonversi menjadi angka atau format data tidak sesuai.

## Hasil Pengujian

1. Data nilai yang valid berhasil diproses.
2. Baris dengan nilai tidak valid dilewati dan ditampilkan pesannya.
3. File yang tidak ditemukan ditangani dengan pesan yang jelas.
4. Baris kosong dilewati.
5. Nilai minimal 60 dihitung sebagai lulus.
6. Hasil rekap disimpan ke "data/hasil_rekap.txt".

## Refleksi

Melalui latihan ini, saya belajar membaca dan menulis file menggunakan Python, memproses data dari file teks, serta menangani error menggunakan try-except. Saya juga memahami bahwa data yang tidak valid dapat dilewati agar data lainnya tetap diproses.