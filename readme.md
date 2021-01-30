# Halo,

Ini adalah panduan singkat, catatan untuk kalian! Harap dibaca

## Instalasi:

- Clone repositori ini
- Pada folder `htdocs`, buat folder `kependudukan`
- Copy repositori ini ke folder tersebut
- Jika Anda menggunakan linux, mungkin perlu mengubah permissionnya menjadi 755 (`sudo chmod -R 755`)
- Buat database `warga_db`
- Import skema yang ada di folder `database` ke dalam database tersebut
- Buka `http://localhost/kependudukan`
- Masukkan username dan password

## Fitur:

- User hanya bisa lihat yang rt dan rw'nya sama dengan user tersebut saja~~ (batal)
- Pembatasan akses halaman berdasarkan status_user~~
- Jika menambahkan id_kepala_keluarga, maka otomatis menambahkannya pada pivot
- Ubah dari # id menjadi nomor urut
- Fitur galeri

### Role/Akses yang tersedia di Database

| Attempt  | Akun Admin | Kasi Pemerintah   |
| -------- | ---------- | ----------------- |
| username | admin      | kasi_pemerintahan |
| password | admin      | 12345             |

## FAQ ERROR

1. Unknown database ''

   > Database belum dibuat atau nama database tidak sama

   - Buat database baru atau perbaiki nama database atau

   sesuaikan pengaturan koneksi database

2. Access denied for user ''

   > username atau password akun phpmyadmin tidak sesuai

   - sesuaikan koneksi database dengan akun phpmyadmin

3. Uncaught Error:Call to undefined function mysql_connect()

   > ekstensi mysql tidak tersedia atau sudah tidak di dukung

   - Gunakan versi PHP5 atau versi xampp yang lawas (jadul)

4. mysqli::real_connect(): / Warning: mysqli_connect():

   > ekstensi mysqli tidak tersedia atau tidak di dukung

   - Gunakan versi PHP7 ke atas atau versi Xampp terbaru

5. Tampilan antarmuka tidak muncul atau acak-acakan

   > file css / style tidak ditemukan atau belum responsif

   - Gunakan internet saat menjalankan-nya atau hapus folder

   yang membungkus folder utama atau master

## NOTE

Beberapa solusi penanganan error di atas mungkin saja tidak dapat menyelesaikan masalah error dikarenakan beberapa faktor lain atau solusi lain.

## Kontribusi

> Jika anda ingin mengembangkannya saya sangat sangat senang!
> Tapi pertama-tama untuk mengembangkanya clone lah repository ini, agar kita saling ber-kontribusi!

> Salam!!
