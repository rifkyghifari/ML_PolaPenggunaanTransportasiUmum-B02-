# ML_PolaPenggunaanTransportasiUmum-B02-
# Pola Penggunaan Transportasi Umum Berdasarkan Waktu dan Jenis Layanan
Project ID B02 | Kelompok 4 | Metode: Clustering (unsupervised learning)
Mata kuliah: [isi] | Dosen: [isi]

## Anggota
| Nama | NIM |
|---|---|
| Rifky Ghiffari Siregar | 231112918 |
| Indra Jeremia Tinambunan | 231112760 |
| Selamet Riyadi | 231112132 |

## Ringkasan
Mengelompokkan 8 moda angkutan umum Jakarta berdasarkan skala penumpang, rasio akhir pekan/hari kerja, dan kestabilan harian. Hasil awal (Milestone 1): K-Means k = 4 sebagai kandidat terkuat sementara; model final belum ditetapkan.

## Dataset
Jumlah Penumpang Angkutan Umum yang Terlayani per Hari, Satu Data Jakarta (data dari Dinas Perhubungan DKI Jakarta).
Link: [isi link dataset]. Diunduh: [isi tanggal]. 7.061 baris (1 Jan 2024 - 31 Agt 2026).
Lisensi/ketentuan: [isi].
File `.xls` sebenarnya berformat HTML, sehingga dibaca dengan `pd.read_html`.

## Cara menjalankan
1. `pip install -r requirements.txt`
2. Letakkan file `.xls` di folder yang sama dengan notebook (atau di Colab, unggah lewat sel `files.upload()`).
3. Buka `notebooks/UTS_B02.ipynb` dan jalankan *Run all*.
Seed acak: `random_state=42`.
Link Colab: [isi link]

## Struktur folder
(salin struktur di atas dan beri satu baris penjelasan tiap folder)

## Hasil
Tabel ringkasan ada di `results/hasil_eksperimen_milestone1.csv` dan di laporan PDF.
