# ML_PolaPenggunaanTransportasiUmum-B02-
# Pola Penggunaan Transportasi Umum Berdasarkan Waktu dan Jenis Layanan
Project ID B02 | Kelompok 4 | Metode: Clustering (unsupervised learning)
Mata kuliah: Pembelajaran Mesin | Kelas: IF-B Pagi

## Anggota
| Nama | NIM |
|---|---|
| Rifky Ghiffari Siregar | 231112918 |
| Indra Jeremia Tinambunan | 231112760 |
| Selamet Riyadi | 231112132 |

## Dataset
- Jumlah Penumpang Angkutan Umum yang Terlayani per Hari, Satu Data Jakarta (data dari Dinas Perhubungan DKI Jakarta).
Link: https://satudata.jakarta.go.id/open-data/detail?kategori=dataset&page_url=jumlah-penumpang-angkutan-umum-yang-terlayani-perhari&data_no=1. 7.061 baris (1 Jan 2024 - 31 Agt 2026).
- Sifat Data: Terbuka
- File `.xls` sebenarnya berformat HTML, sehingga dibaca dengan `pd.read_html`.
- Berikut dataset dalam excel:
[jumlah-penumpang-angkutan-umum-yang-terlayani-per-hari-komponen-data.xls](https://github.com/user-attachments/files/34539313/jumlah-penumpang-angkutan-umum-yang-terlayani-per-hari-komponen-data.xls)


## Cara menjalankan
1. `pip install -r requirements.txt`
2. Letakkan file `.xls` di folder yang sama dengan notebook (atau di Colab, unggah lewat sel `files.upload()`).
3. Buka `notebooks/UTS_B02.ipynb` dan jalankan *Run all*.
Seed acak: `random_state=42`.
Link Colab: https://colab.research.google.com/drive/1D9IAD6pWsUYy6m1JIhZ3F-GTZeOzPWxy?usp=sharing


