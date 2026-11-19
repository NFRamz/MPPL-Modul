# Modul 2 - Estimasi Biaya & Manajemen Backlog
**Manajemen Proyek Perangkat Lunak (MPPL)**  
**Versi 2.1** | Februari 2026

---

## 🎯 Tujuan Pembelajaran
1. Mahasiswa memahami dasar-dasar estimasi biaya dan usaha (*effort*) perangkat lunak.
2. Mahasiswa mampu menerjemahkan kebutuhan bisnis tingkat tinggi menjadi artefak Agile (*Epics* & *User Stories*).
3. Mahasiswa mampu menyusun struktur *backlog* yang terorganisir di Jira Software.

---

## 💡 Konteks PMBOK (Project Management Body of Knowledge)
Modul ini mencakup tiga bidang pengetahuan utama dalam PMBOK:
*   **Project Scope Management:** Mendefinisikan ruang lingkup melalui *Product Backlog* dan *User Stories*.
*   **Project Cost Management:** Melakukan estimasi biaya berdasarkan usaha (*effort*) yang dihitung.
*   **Project Schedule Management:** Mengestimasi durasi pengembangan proyek secara ilmiah.

---

## 🔢 1. Sains Estimasi (Metode COCOMO)
Dalam dunia profesional, memberikan harga proyek berdasarkan "firasat" sangatlah berbahaya. Kita menggunakan **COCOMO (Constructive Cost Model)** untuk menghitung Usaha (*Effort*), Waktu (*Time*), dan Jumlah Staf (*People*) berdasarkan estimasi ukuran perangkat lunak dalam **KLOC** (Kilo Lines of Code).

### 1.1 Menentukan Mode Proyek
*   **Organic:** Proyek sederhana, tim kecil, kebutuhan fleksibel (Contoh: Sistem inventaris lab).
*   **Semi-Detached:** Proyek menengah, campuran staf berpengalaman & pemula (Contoh: Sistem informasi akademik).
*   **Embedded:** Proyek kompleks, batasan ketat, risiko tinggi (Contoh: Sistem kontrol lalu lintas udara).

### 1.2 Rumus COCOMO (Intermediate)
1.  **Effort (E):** $E = a \times (KLOC)^b$ (Satuan: *Person-Month*)
2.  **Time (T):** $T = c \times (E)^d$ (Satuan: Bulan)
3.  **People (P):** $P = E / T$ (Satuan: Orang)

**Tabel Koefisien:**
| Mode Proyek | a | b | c | d |
| :--- | :--- | :--- | :--- | :--- |
| **Organic** | 2.4 | 1.05 | 2.5 | 0.38 |
| **Semi-Detached** | 3.0 | 1.12 | 2.5 | 0.35 |
| **Embedded** | 3.6 | 1.20 | 2.5 | 0.32 |

---

## 📋 2. Agile Requirements Engineering
Dalam Agile, kebutuhan tidak ditulis dalam dokumen tebal, melainkan secara inkremental di Jira.

### 2.1 Hirarki Kebutuhan di Jira
*   **Epic:** Kumpulan besar pekerjaan (Modul utama). Contoh: "Modul Pembayaran", "Manajemen User".
*   **User Story:** Fitur spesifik dari sudut pandang pengguna.
    *   **Format:** *"Sebagai [Peran], saya ingin [Aksi], sehingga [Manfaat]."*
*   **Acceptance Criteria:** Kriteria yang harus dipenuhi agar sebuah *story* dianggap selesai (Done).

---

## 📝 Aktivitas Praktikum

### Aktivitas 1: Analisis & Estimasi (Sesi Terbimbing)
1.  **Breakdown Strategis:** Bedah *Business Case* dari Modul 1 menjadi modul-modul fungsi.
2.  **Estimasi KLOC:** Tentukan asumsi jumlah baris kode untuk setiap fitur.
3.  **Hitung COCOMO:** Gunakan rumus di atas untuk menentukan berapa bulan proyek akan berjalan dan berapa biaya yang dibutuhkan (asumsi gaji pengembang Rp 4.000.000/bulan).

### Aktivitas 2: Eksekusi Digital di Jira (Sesi Demo)
1.  **Input Backlog:** Masukkan minimal **3 Epics** dan **10 User Stories** ke Jira.
2.  **Linkage:** Pastikan setiap *User Story* terhubung ke *Epic* yang benar.
3.  **Prioritas:** Tentukan prioritas (*High, Medium, Low*) untuk setiap tiket di Jira.

---

## 📊 Rubrik Penilaian (Modul 2)

| Kategori | Komponen | Kriteria | Bobot |
| :--- | :--- | :--- | :--- |
| **Individu (30%)** | Pertahanan Estimasi | Kemampuan menjelaskan logika di balik angka KLOC dan biaya. | 20% |
| | Konsultasi | Keaktifan merespon feedback asisten. | 10% |
| **Grup (70%)** | Analisis COCOMO | Ketepatan perhitungan Effort, Time, dan People. | 40% |
| | Struktur Backlog | Kelengkapan hirarki Jira (3 Epic, 10 Stories) dan format penulisan. | 30% |

---
**Laboratorium Informatika**  
*Universitas Muhammadiyah Malang*
