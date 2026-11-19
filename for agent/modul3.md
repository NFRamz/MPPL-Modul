# Modul 3 - Sprint Planning & Penjadwalan
**Manajemen Proyek Perangkat Lunak (MPPL)**  
**Versi 2.1** | Februari 2026

---

## 🎯 Tujuan Pembelajaran
1. Mahasiswa memahami konsep estimasi relatif menggunakan *Story Points* dan *Planning Poker*.
2. Mahasiswa mampu menyusun *Backlog* ke dalam jadwal kerja konkret (*Sprint*).
3. Mahasiswa mampu mengeksekusi proses "Start Sprint" di dalam Jira Software.

---

## 💡 Konteks PMBOK (Project Management Body of Knowledge)
Modul ini merupakan implementasi dari **Project Schedule Management** dan **Project Resource Management**:
*   **Estimasi Usaha:** Menggantikan estimasi jam kerja yang kaku dengan *Story Points* untuk menangani ketidakpastian (*uncertainty*).
*   **Pengembangan Jadwal:** Menentukan iterasi kerja melalui metode *Time-boxing* (Sprint).
*   **Manajemen Sumber Daya:** Menyelaraskan beban kerja dengan kapasitas tim (*Velocity*).

---

## 🎲 1. Seni Estimasi (Story Points)
Dalam Agile, kita tidak menggunakan jam kerja untuk estimasi awal, melainkan **Story Points**. Ini adalah unit pengukuran relatif yang mencakup:
1.  **Kompleksitas Teknis:** Seberapa sulit fitur tersebut dibangun?
2.  **Volume Kerja:** Seberapa banyak kode/aset yang harus dibuat?
3.  **Ketidakpastian:** Seberapa banyak hal yang belum diketahui tentang fitur tersebut?

### 1.1 Deret Fibonacci & Planning Poker
Kita menggunakan deret **Fibonacci (1, 2, 3, 5, 8, 13)** untuk menghindari kepastian palsu. Semakin besar angkanya, semakin tinggi ketidakpastiannya.
*   **Planning Poker:** Teknik konsensus di mana setiap anggota tim memberikan poin secara rahasia untuk satu *User Story*, kemudian mendiskusikan perbedaan angka hingga mencapai kesepakatan.

---

## ⏱️ 2. Mekanisme Sprint Planning
Sprint adalah iterasi waktu yang tetap (biasanya 2 minggu) di mana tim fokus menyelesaikan set fitur tertentu.

### 2.1 Sprint Backlog & Time-Boxing
*   **Sprint Backlog:** Bagian dari *Product Backlog* yang dipilih untuk diselesaikan dalam satu Sprint berdasarkan prioritas dan kapasitas tim.
*   **Time-Boxing:** Prinsip bahwa waktu Sprint tidak boleh diperpanjang. Jika pekerjaan tidak selesai, pekerjaan tersebut dikembalikan ke *Product Backlog*.

### 2.2 Alur Kerja di Jira
1.  **Create Sprint:** Membuat kontainer Sprint baru di menu Backlog.
2.  **Drag & Drop:** Memindahkan *User Stories* dari Backlog ke dalam Sprint.
3.  **Start Sprint:** Mengaktifkan Sprint dengan menentukan Nama Sprint, Durasi, Tanggal Mulai/Selesai, dan **Sprint Goal** (Tujuan utama Sprint).

---

## 📝 Aktivitas Praktikum

### Aktivitas 1: Planning Poker & Estimasi (Sesi Terbimbing)
1.  Buka daftar *User Stories* dari Modul 2.
2.  Lakukan sesi *Planning Poker* bersama tim menggunakan poin Fibonacci.
3.  Tentukan satu *User Story* termudah sebagai referensi (skala 1 poin).
4.  **Output:** Daftar seluruh *User Stories* yang sudah memiliki nilai *Story Points*.

### Aktivitas 2: Setup & Aktivasi Sprint di Jira (Sesi Demo)
1.  Masukkan nilai *Story Points* ke setiap tiket di Jira.
2.  Buat **Sprint 1** dan pindahkan tiket-tiket prioritas tinggi ke dalamnya.
3.  Pastikan total *Story Points* dalam Sprint 1 realistis (tidak *overload*).
4.  Klik **Start Sprint** dan isi detail sesuai *Project Charter*.
5.  Verifikasi bahwa Sprint sudah berstatus **Active** dan muncul di Board.

---

## 📊 Rubrik Penilaian (Modul 3)

| Kategori | Komponen | Kriteria | Bobot |
| :--- | :--- | :--- | :--- |
| **Individu (30%)** | Logika Prioritas | Kemampuan menjelaskan alasan pemilihan fitur dalam Sprint 1. | 20% |
| | Konsultasi | Keaktifan dalam diskusi estimasi dengan asisten. | 10% |
| **Grup (70%)** | Konfigurasi Sprint | Sprint 1 aktif di Jira dengan tanggal dan Goal yang jelas. | 40% |
| | Kualitas Estimasi | Seluruh tiket memiliki Story Points yang logis (mengikuti Fibonacci). | 30% |

---
**Laboratorium Informatika**  
*Universitas Muhammadiyah Malang*
