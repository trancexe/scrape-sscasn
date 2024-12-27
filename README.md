# Tools Pengambilan Data SSCASN

Tools ini digunakan untuk mengambil data dari SSCASN. Terdiri dari 2 skrip:

1. Skrip Pengambilan Jenis Pendidikan: 
   - Mengambil data jenis pendidikan yang tersedia di SSCASN.

2. Skrip Pengambilan Daftar Formasi:
   - Mengambil data daftar formasi berdasarkan jenis pendidikan.

## Penggunaan

**Jika ingin menjalankan skrip untuk semua jenis pendidikan:**

- Jalankan kedua skrip secara berurutan.

**Jika ingin menjalankan skrip hanya untuk jenis pendidikan tertentu:**

1. Upload file `data_pendidikan.json` ke Google Colabs.
2. File `data_pendidikan.json` harus memiliki format seperti berikut:

```json
[
  {
    "kode_pend": "2002000",
    "nama_pend": "MADRASAH TSANAWIYAH"
  },
  {
    "kode_pend": "2004003",
    "nama_pend": "PROGRAM STUDI LAINNYA"
  }
]
