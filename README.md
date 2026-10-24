# Algoritma dan Pemrograman — Pertemuan 10

## Identitas
- Program Studi: Pendidikan Matematika
- Fakultas: FKIP
- Universitas: Universitas Sultan Ageng Tirtayasa
- Tahun Ajaran: 2026/2027 Ganjil
- NIM: 2225250177
- Kelas: 3B

## Tujuan
Mempelajari pengolahan string pada Python, meliputi indeks, slicing, method string, pembersihan teks, split, join, dan pencarian kata. Selain itu, menerapkan pengolahan string dalam program normalisasi data mahasiswa.

## Struktur Folder
- `latihan/01_dasar_string.py`
- `latihan/02_indeks_slicing.py`
- `latihan/03_method_string.py`
- `latihan/04_bersihkan_teks.py`
- `latihan/05_split_join.py`
- `latihan/06_pencarian_kata.py`
- `tugas/normalisasi_data_mahasiswa.py`

## Cara Menjalankan Program
Jalankan perintah berikut melalui terminal di folder utama proyek:

`python tugas/normalisasi_data_mahasiswa.py`

Masukkan nama dan kode kelas ketika program meminta input.

## Algoritma
1. Meminta pengguna memasukkan nama dan kode kelas.
2. Membersihkan spasi berlebih pada nama.
3. Mengubah nama menjadi format huruf kapital yang sesuai.
4. Mengubah kode kelas menjadi huruf kapital dan mengganti spasi antarkata dengan tanda hubung.
5. Menghitung jumlah kata dalam nama.
6. Mengambil huruf pertama setiap kata sebagai inisial.
7. Menampilkan hasil normalisasi nama, kode kelas, jumlah kata, dan inisial.

## Test Case

| No. | Input Nama | Input Kode | Hasil yang Diharapkan | Status |
|---|---|---|---|---|
| 1 | aan hendrayana | pmat a 2026 | Aan Hendrayana; PMAT-A-2026; 2; AH | Isi setelah pengujian |
| 2 | fATHIYYAH mUTHMAINNAH | kelas b | Fathiyyah Muthmainnah; KELAS-B; 2; FM | Isi setelah pengujian |
| 3 | BUDI | pmtk 01 | Budi; PMTK-01; 1; B | Isi setelah pengujian |
| 4 | siti nur aisyah | kelas c | Siti Nur Aisyah; KELAS-C; 3; SNA | Isi setelah pengujian |

Catatan: hasil aktual harus diperiksa dengan menjalankan program. Ubah status menjadi **Berhasil** apabila hasil aktual sesuai dengan hasil yang diharapkan.

## Refleksi
Salah satu masalah dalam pengolahan teks adalah adanya spasi berlebih dan penggunaan huruf kapital yang tidak konsisten. Masalah tersebut dapat membuat data sulit dibandingkan. Saya mempelajari penggunaan `strip()`, `split()`, `join()`, dan `title()` untuk merapikan teks. Saya juga mempelajari penggunaan fungsi agar proses normalisasi dapat dilakukan dengan lebih terstruktur.

## Referensi
- Bahan Ajar Algoritma dan Pemrograman, Pertemuan 10: String dan Pengolahan Teks dalam Python.