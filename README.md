# UTS Data Acquisition & Management — Kelas F

## 1. Data Diri
* **Nama:** [Apolinarisa Jack Herment]
* **NIM:** 2501010333
* **Kelas:** F
* **Program Studi:** Informatika — INSTIKI

---

## 2. Sumber URL (Tabel)

| No | Metode Akuisisi | Nama Dataset / Sumber | URL Sumber | Format Mentah (`data/raw`) | Format Hasil (`Proses`) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | **Download** | Dataset Destinasi Wisata Bali (Kaggle) | https://www.kaggle.com/datasets/dakbsabsa/bali-destination-tour-datasets-2026 | `bali_tourist_destination.csv` | `wisata_bali_bersih.csv` |
| 2 | **API** | Open-Meteo Historical Weather API (Bali) | https://open-meteo.com | `cuaca_bali_raw.json` | `cuaca_bali_bersih.json` |
| 3 | **Scraping** | Daftar Kabupaten dan Kota di Bali (Wikipedia) | https://wikipedia.org | `wilayah_bali_raw.html` | `wilayah_bali_bersih.html` |

---

## 3. Goal (Tujuan)
Tujuan dari proyek akuisisi data ini adalah mengumpulkan data destinasi pariwisata di Provinsi Bali yang dipadukan dengan data kondisi cuaca historis serta profil administratif kabupaten/kota di Bali secara etis dan terdokumentasi (*provenance* & MD5 hash), sehingga menghasilkan dataset gabungan yang bersih dan siap digunakan untuk analisis pola kunjungan maupun perencanaan sektor pariwisata Bali.
