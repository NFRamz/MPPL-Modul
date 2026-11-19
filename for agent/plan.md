# Rencana Pembaruan Alur Praktikum MPPL (Selaras Standar PMBOK)
**Dokumentasi Analisis Kurikulum Praktikum (Modul 0 – Modul 6)**  
**Program Studi Informatika — Universitas Muhammadiyah Malang**

---

## 1. Ringkasan Eksekutif
Berdasarkan tinjauan terhadap rangkaian modul praktikum versi terdahulu (**Modul 0 hingga Modul 6**) dan membandingkannya dengan standar ***PMBOK® Guide – Seventh Edition* (2021)**, dapat disimpulkan bahwa **alur besar praktikum dari Modul 1 hingga Modul 6 sudah sangat solid dan layak dipertahankan (sekitar 85% alurnya sudah selaras)**.

Pembaruan berbasis PMBOK **tidak memerlukan perombakan total** terhadap urutan topik per modul. Alur praktikum lama sudah merepresentasikan siklus hidup proyek (*Project Life Cycle*) yang utuh dari hulu ke hilir (1 semester: 6 minggu fase pembelajaran/materi dan 6 minggu fase evaluasi/demo):
* **Modul 0:** Tata kelola & aturan main (*Organizational Governance & Team Formation*).
* **Modul 1:** Inisiasi & Otorisasi Proyek (*Business Case, Project Charter, Stakeholder Mapping, Jira Setup*).
* **Modul 2:** Perencanaan Biaya, Ruang Lingkup & *Backlog* (*Cost Estimation, Epics, User Stories*).
* **Modul 3:** Penjadwalan & Estimasi Relatif (*Story Points, Planning Poker, Sprint Planning*).
* **Modul 4:** Perancangan & Validasi Awal (*UI/UX Prototyping*).
* **Modul 5:** Dokumentasi Akhir & Serah Terima Pengguna (*User Manual & Knowledge Transfer*).
* **Modul 6:** Eksekusi Simulasi, Pengukuran Kinerja & Evaluasi (*Sprint Execution, Agile Reports, Retrospective*).

---

## 2. Analisis Khusus: Posisi Materi *Cost Estimation* (Modul 2) dalam PMBOK
Penerapan standar PMBOK **tidak menghapus** materi estimasi biaya (*Cost Estimation*) pada Modul 2:
* **Pada PMBOK Edisi ke-6:** *Project Cost Management* merupakan salah satu dari *10 Knowledge Areas* utama.
* **Pada PMBOK Edisi ke-7:** Estimasi biaya, upaya (*effort*), durasi, serta penyusunan anggaran (*Budget Build-up*) dibahas secara eksplisit di dalam ***Planning Performance Domain*** (Sub-bab 2.4.2.2 *Estimating* dan 2.4.2.4 *Budget*) serta dievaluasi pada ***Measurement Performance Domain*** (Sub-bab 2.7.2.3 *Baseline Performance* & 2.7.2.5 *Business Value*).

### Rekomendasi Penyesuaian Metode Estimasi Modul 2
Hal yang perlu disesuaikan pada Modul 2 bukanlah penghapusan topik biaya, melainkan **penyelarasan metode estimasi** agar tidak bertabrakan dengan paradigma *Agile/Scrum* di modul-modul berikutnya:
1. **Catatan terhadap COCOMO (KLOC):** Metode COCOMO berbasis *Kilo Lines of Code* (KLOC) bersifat *predictive* (Waterfall) karena menuntut perkiraan baris kode sebelum desain antarmuka dibuat.
2. **Opsi Penyelarasan PMBOK + Agile:**
   * **Opsi A (Konservatif — Pertahankan COCOMO sebagai Estimasi Awal):** COCOMO tetap digunakan sebagai metode estimasi makro (*Rough Order of Magnitude*) untuk menyusun *Cost Baseline* awal bagi klien, lalu disandingkan dengan pemecahan ruang lingkup (*Work Breakdown Structure* / *Product Backlog*).
   * **Opsi B (Modern PMBOK 7th Edition — *Parametric / Analogous & Story-Point Costing*):** Menghitung biaya berdasarkan *effort* per fitur/modul (*Bottom-Up* dari *Epics & User Stories*) atau mengonversi *Story Points* (Modul 3) menggunakan *Burn Rate* tim per Sprint, ditambah komponen *Contingency Reserve* (cadangan biaya risiko) sesuai standar PMBOK.

---

## 3. Peta Evaluasi & Rencana Pembaruan Modul 0 – 6

| Modul | Topik Versi Lama | Status Perubahan | Rencana Penyesuaian Berbasis PMBOK (7th Edition) |
| :--- | :--- | :--- | :--- |
| **Modul 0** | *Practicum Guidelines* | **Tetap** | Sudah mencerminkan konsep *Organizational Governance*, kepatuhan aturan, dan pembentukan tim (*Team Formation*). |
| **Modul 1** | *Initiation & Jira Setup* | **Revisi Ringan** | Tambahkan payung teori *PMBOK 7th Edition* (*12 Principles* & *8 Performance Domains* serta *System for Value Delivery*), prinsip kolaborasi tim (*Swarming* & *Servant Leadership*), serta pemetaan *Stakeholder*. |
| **Modul 2** | *Cost Estimation (COCOMO) & Product Backlog* | **Revisi Konseptual** | **Pertahankan** fokus pada *Cost & Scope Planning*. Tambahkan konsep penyusunan *Cost Baseline* dan *Contingency Reserve* (PMBOK) agar estimasi anggaran proyek untuk klien nyata lebih terukur. |
| **Modul 3** | *Sprint Planning & Scheduling* | **Tetap (Tambah Istilah)** | Materi *Story Points, Planning Poker,* dan *Time-boxing* sudah selaras dengan bagian *Adaptive Schedule Planning* pada *Planning Performance Domain* (Sub-bab 2.4.2.3 PMBOK 7th Ed). |
| **Modul 4** | *Prototyping with Figma* | **Tetap (Perkuat Kaitan)** | Perkuat landasan teori menggunakan *Delivery Performance Domain* (Sub-bab 2.6.2.1) & *Uncertainty Performance Domain* (Sub-bab 2.8.2): *Prototyping* berfungsi menurunkan tingkat *Ambiguity* (ketidakpastian kebutuhan) dan memvalidasi *Requirements* sejak dini. |
| **Modul 5** | *User Manual in Software Development* | **Tetap (Perkuat Kaitan)** | Hubungkan dengan konsep *Knowledge Management* (*Explicit Knowledge* & *Knowledge Transfer* pada Sub-bab 2.5.8) serta proses transisi ke operasional (*Transition to Operations / Closing*). |
| **Modul 6** | *Sprint Simulation & Reporting* | **Revisi Ringan** | *Burndown, Burnup, Velocity,* dan *Cumulative Flow Diagram* merupakan instrumen utama pada *Measurement Performance Domain* (Sub-bab 2.7.3). Tambahkan evaluasi *Variance* (perbandingan *baseline* awal vs realisasi akhir) sebagai penutup proyek (*Closing*). |

---

## 4. Kesimpulan & Langkah Selanjutnya
1. **Pertahankan Struktur 6 Modul:** Tidak perlu mengubah tema besar masing-masing modul karena alur pembelajaran sudah berkesinambungan dari *Initiating* hingga *Closing*.
2. **Penguatan Benang Merah PMBOK:** Setiap modul cukup diperkaya pada bagian pengantar teori dan rubrik evaluasi agar istilah dan praktik PMBOK (seperti *Value Delivery, Stakeholder Engagement, Cost Baseline, Ambiguity Reduction, Knowledge Transfer,* dan *Performance Measurement*) terlihat konsisten dari Modul 1 sampai Modul 6.
3. **Prioritas Pengerjaan:**
   * Menyelesaikan penyusunan naskah lengkap **Modul 1** (Bab 2 hingga Rubrik Penilaian).
   * Melakukan penyelarasan konsep estimasi biaya (*Cost Baseline* & *Contingency Reserve*) pada **Modul 2**.