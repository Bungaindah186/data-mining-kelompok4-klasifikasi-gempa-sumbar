# Evaluasi Model Klasifikasi: Deteksi Gempa Signifikan di Sumatera Barat

**Praktikum Data Mining — Kelompok 4**
Program Studi Informatika, Departemen Teknik Elektronika, Fakultas Teknik
Universitas Negeri Padang (UNP) — 2026

Dosen pengampu: Dr. Yeka Hendriyani, S.Kom., M.Kom.

---

## Anggota Kelompok 4

| No | Nama | NIM |
|----|------|-----|
| 1 | Bunga Indah | 24343003 |
| 2 | Rifka Novira Azzahra | 24343047 |
| 3 | Firnanda Rizki Pratama. Mt | 24343008 |

---

## Deskripsi Proyek

Repositori ini berisi hasil praktikum **Evaluasi Model Klasifikasi** pada mata kuliah Data Mining, yang mencakup *confusion matrix*, *accuracy*, *precision*, *recall*, dan *F1-score*.

kelompok kami memakai **data gempa bumi BMKG di wilayah Sumatera Barat**.

| Modul (fraud) | Proyek ini (gempa) |
|---|---|
| `isFraud = 1` (fraud) | `isSignifikan = 1` (gempa magnitudo ≥ 5.0) |
| `isFraud = 0` (normal) | `isSignifikan = 0` (gempa magnitudo < 5.0) |

Kelas positif (gempa signifikan) jumlahnya jauh lebih sedikit, sekitar 2,69% dari seluruh data. Kondisi ini mirip fraud pada modul, sehingga cocok untuk membahas data tidak
