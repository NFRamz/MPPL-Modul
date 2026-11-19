# Modul 1 - Inisiasi Proyek & Manajemen Pemangku Kepentingan
**Manajemen Proyek Perangkat Lunak (MPPL)**  
**Versi 2.1** | Februari 2026

---

## 🎯 Tujuan Pembelajaran
1. Mahasiswa memahami fase awal inisiasi proyek perangkat lunak berdasarkan standar **PMBOK**.
2. Mahasiswa mampu mengidentifikasi peran dan tanggung jawab dalam tim pengembang perangkat lunak.
3. Mahasiswa mampu menyusun dokumen **Business Case** dan **Project Charter** sebagai mandat otorisasi proyek.
4. Mahasiswa mampu melakukan konfigurasi infrastruktur digital menggunakan **Jira Software (Company-managed)**.

---

## 💡 1. Landasan Teori: Paradigma PMBOK & Agile
Dalam standar *Project Management Body of Knowledge* (PMBOK), sebuah proyek dimulai dengan fase **Initiating** (Inisiasi).

### 1.1 5 Process Groups & 10 Knowledge Areas [Revisi]
Manajemen proyek profesional modern membagi siklus hidup proyek menjadi 5 kelompok proses:
1. **Initiating:** Menentukan proyek baru atau fase baru.
2. **Planning:** Menetapkan cakupan, tujuan, dan alur kerja.
3. **Executing:** Menyelesaikan pekerjaan yang didefinisikan dalam rencana.
4. **Monitoring & Controlling:** Melacak, meninjau, dan mengatur kemajuan.
5. **Closing:** Menyelesaikan semua aktivitas secara formal.

Materi praktikum ini akan mencakup 10 *Knowledge Areas*, termasuk Manajemen Integrasi, Ruang Lingkup, Waktu, Biaya, Kualitas, SDM, Komunikasi, Risiko, Pengadaan, dan Pemangku Kepentingan (*Stakeholders*).

### 1.2 Agile & Scrum [Tetap]
Agile adalah pola pikir yang mengutamakan fleksibilitas. Dalam praktikum ini, kita menggunakan kerangka kerja **Scrum**. Scrum membagi waktu pengerjaan menjadi iterasi tetap yang disebut **Sprint** (biasanya 2 minggu). Fokus utama Scrum adalah menghasilkan produk yang dapat berfungsi (*Potentially Shippable Product*) di setiap akhir Sprint.

---

## 👥 2. Anatomi Tim Perangkat Lunak (PMBOK Aligned)
Keberhasilan proyek bergantung pada pembagian kerja yang jelas, namun tetap mengedepankan solidaritas tim.

**Prinsip Kerja: Swarming & T-Shaped Skills** [Baru]
Meskipun setiap anggota memiliki peran *Lead* (pemimpin area), praktikum ini mewajibkan mekanisme **Swarming**. Jika seorang *Executor* mengalami kesulitan teknis sementara *Manager* atau *Planner* sudah menyelesaikan tugas manajerialnya, mereka **wajib** membantu proses teknis tersebut. Kita membangun tim dengan *T-Shaped Skills*: ahli di bidang utamanya, namun mampu membantu di bidang lain.

Berikut adalah 5 peran Lead:

1. **Manager (Servant Leader):** [Revisi]  
   Bertanggung jawab atas Manajemen Risiko dan Pemantauan Kemajuan. Ia memastikan hambatan teknis tim diselesaikan dan menjadi jembatan komunikasi ke pihak eksternal (Dosen/Asisten).
2. **Initiator (The Visionary):** [Baru]  
   Fokus pada *Opportunity Identification*. Ia memastikan proyek memiliki nilai bisnis yang jelas dan melakukan analisis kelayakan (*Feasibility Analysis*).
3. **Planner (The Strategist):** [Revisi]  
   Bertanggung jawab atas Manajemen Jadwal dan Alokasi Sumber Daya. Ia memecah visi menjadi *backlog* yang dapat dikerjakan secara teknis.
4. **Executor (The Builder):** [Tetap]  
   Fokus pada implementasi teknis (Coding, Design, Testing). Bertanggung jawab atas kualitas kode dan dokumentasi teknis.
5. **Closing Role (The Auditor):** [Baru]  
   Memastikan proyek tidak berhenti begitu saja, tetapi ditutup secara profesional melalui *Administrative Completion* dan laporan *Lessons Learned*.

---

## 📄 3. Dokumentasi Strategis (Otorisasi Proyek)
Sebelum pengerjaan dimulai, dua dokumen kritis harus disiapkan:

### 3.1 Business Case [Tetap/Revisi]
Dokumen ini menjawab pertanyaan **"Mengapa proyek ini dibuat?"**. Berisi:
*   *Problem Statement:* Masalah nyata yang dihadapi klien.
*   *Proposed Solution:* Bagaimana aplikasi Anda menyelesaikan masalah tersebut.
*   *Expected Benefits:* Keuntungan finansial atau operasional setelah proyek selesai.

### 3.2 Project Charter [Baru]
Jika *Business Case* adalah alasannya, maka *Charter* adalah **Izinnya**. Dokumen ini secara formal memberikan mandat kepada tim untuk menggunakan sumber daya. Poin krusial di sini adalah penentuan **Scope** (Apa yang dibangun) vs **Out-of-Scope** (Apa yang tidak akan dibangun) untuk mencegah *Scope Creep*.

### 3.3 Stakeholder Identification [Baru]
Mahasiswa harus memetakan pemangku kepentingan:
*   **Asisten Laboratorium:** Bertindak sebagai *Client* atau *Product Owner*.
*   **Mahasiswa:** Bertindak sebagai *Project Team*.

---

## ⚙️ 4. Infrastruktur Digital: Jira Software
Jira adalah standar industri untuk melacak proyek Agile.

### 4.1 Setup Workspace & Site Creation [Tetap]
*   Akses: [https://www.atlassian.com/software/jira/pricing](https://www.atlassian.com/software/jira/pricing)
*   Pilih Plan: **Free ($0)**. Pastikan tidak ada input informasi kartu kredit.
*   Site Name: Gunakan nama tim atau judul proyek yang profesional.

### 4.2 Konfigurasi Project (Wajib Company-managed) [Revisi]
Langkah krusial untuk fitur pelaporan PMBOK:
1.  Pilih template **Scrum**.
2.  Saat pemilihan jenis manajemen, **WAJIB** memilih **Company-managed project**. 
    *   *Alasan:* Template ini menyediakan kontrol penuh atas alur kerja dan laporan Agile profesional (*Burn-down Chart, Velocity*) yang dibutuhkan untuk penilaian.
3.  Undang anggota tim ke dalam situs melalui menu *People*.

---

## 📝 Aktivitas Praktikum

### Aktivitas 1: Pembentukan Tim & Peran
1.  Bentuk kelompok (maksimal 3 orang).
2.  Tentukan peran masing-masing anggota (boleh merangkap peran, namun tanggung jawab harus terpisah).
3.  Isi *Commitment Letter* yang disediakan oleh asisten lab.

### Aktivitas 2: Perburuan Klien (Client Hunt) [Baru/Revisi]
1.  **Cari Klien Asli:** Bisa berupa UMKM, dosen, organisasi mahasiswa, atau pihak lain yang membutuhkan solusi perangkat lunak. **Data simulasi/fiktif tidak diperbolehkan.**
2.  **Wawancara Klien:** Lakukan wawancara untuk menggali kebutuhan. Wawancara **WAJIB direkam** (audio/video) untuk ditunjukkan saat demo.
3.  **Drafting:** Susun *Business Case* dan *Project Charter* berdasarkan hasil wawancara tersebut.
4.  **Setup Jira:** Selesaikan konfigurasi proyek di Jira sesuai instruksi di atas.

---

## 📊 Rubrik Penilaian (Modul 1)

| Kategori | Komponen | Kriteria | Bobot |
| :--- | :--- | :--- | :--- |
| **Individu (30%)** | Pertahanan Peran | Mampu menjelaskan tanggung jawab spesifik peran masing-masing dalam tim. | 20% |
| | Konsultasi | Keaktifan berdiskusi dengan asisten selama jam lab. | 10% |
| **Dokumentasi (40%)** | Business Case | Kejelasan masalah dan logika solusi yang ditawarkan. | 25% |
| | Project Charter | Definisi *Scope* (In-Scope vs Out-of-Scope) yang jelas. | 15% |
| **Setup Teknis (30%)** | Konfigurasi Jira | Penggunaan template Scrum & Company-managed, serta kelengkapan undangan tim. | 30% |

---
**Laboratorium Informatika**  
*Universitas Muhammadiyah Malang*
