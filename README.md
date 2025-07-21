# Fuzzy Logic: Prediksi Risiko Stroke

Dalam dunia nyata, banyak keputusan tidak bisa ditentukan hanya dengan nilai *benar* atau *salah*. Logika Fuzzy hadir untuk menangani ketidakpastian dengan memberikan derajat keanggotaan dalam rentang [0, 1]. Konsep ini sangat berguna untuk kasus-kasus seperti prediksi risiko penyakit, termasuk stroke.

> Derajat keanggotaan fuzzy dilambangkan dengan `μ[x]` dan menunjukkan seberapa kuat suatu nilai termasuk dalam sebuah himpunan fuzzy.
---

## Instalasi

Pastikan Python sudah terinstal. Kemudian, instal pustaka `scikit-fuzzy` dengan perintah berikut:

```bash
pip install scikit-fuzzy
```

## Cara Menggunakan Program
Program ini digunakan untuk menghitung seberapa besar risiko seseorang terkena stroke berdasarkan beberapa parameter:
- Umur
- Tingkat glukosa rata-rata
- BMI (Body Mass Index)
- Jumlah rokok yang dikonsumsi per hari

Namun, harap diperhatikan:  
>Tidak semua data dalam file `data/brain_stroke.xlsx` bisa diproses langsung oleh sistem fuzzy.
Hal ini dikarenakan ada kemungkinan nilai-nilai tertentu tidak memiliki derajat keanggotaan dalam fungsi keanggotaan fuzzy yang telah ditentukan.
Untuk mengatasi hal ini, kami telah menyediakan bagian akhir program yang secara otomatis mengecek baris-baris data yang valid dan dapat diproses.
---

## Anggota Kelompok
1. Muhammad Ikhsan Fadillah - 10123134
2. Muhammad Faishal Rahmani - 10123135
3. Rizqi Akbar Fadillah - 10123151
4. Farhan Nawwafal Pramudia - 10123470

## Struktur File
```bash
fuzzy-mamdani
├── main.ipynb                # Notebook utama program fuzzy
├── data/
│   └── brain_stroke.xlsx     # Dataset stroke
└── README.md                 # Dokumentasi proyek ini
```