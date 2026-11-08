# Pola Penggunaan Transportasi Umum Berdasarkan Waktu dan Jenis Layanan

## Project ID
B02

## Nama Kelompok
Kelompok 4

## Anggota
| No | Nama | NIM |
|---|---|---|
| 1 | Rifky Ghiffari Siregar | 231112918 |
| 2 | Indra Jeremia Tinambunan | 231112760 |
| 3 | Selamet Riyadi | 231112132 |

## Deskripsi Masalah
Jumlah penumpang angkutan umum Jakarta berbeda sangat jauh antarmoda, dan pola hari kerja dibandingkan akhir pekan juga berbeda. Belum diketahui apakah moda-moda ini dapat dikelompokkan berdasarkan pola penggunaannya.

Project ini mengelompokkan 8 jenis moda angkutan umum (TransJakarta, KRL, MIKROTRANS, MRT, Bus Sekolah, KCI Commuter Bandara, LRT, dan Kapal) berdasarkan skala penumpang, rasio penumpang akhir pekan terhadap hari kerja, dan kestabilan harian. Pendekatan yang dipakai adalah clustering (unsupervised learning) tanpa label.

Status: hasil awal Milestone 1 (UTS). Model final belum ditetapkan dan akan dipilih pada tahap UAS.

## Petunjuk Penggunaan Repository

**Isi repository**
| Lokasi | Isi |
|---|---|
| `UTS_Kelompok4_B02.ipynb` | Notebook eksperimen (Google Colab) |
| `Dataset/` | Dataset yang dipakai notebook |
| `hasil_milestone1/` | Tabel hasil eksperimen awal (berkas `.csv`) |
| `Laporan Milestone 1/` | Laporan Milestone 1 dalam format PDF |

**Cara menjalankan notebook**
1. Buka `UTS_Kelompok4_B02.ipynb` di Google Colab: https://colab.research.google.com/drive/1D9IAD6pWsUYy6m1JIhZ3F-GTZeOzPWxy?usp=sharing.
2. Unggah file dataset `.xls` dari folder `Dataset/` saat diminta oleh sel `files.upload()`.
3. Jalankan seluruh sel secara berurutan (*Runtime → Restart and run all*).
