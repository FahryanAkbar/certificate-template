# CSMS Assessment & Certificate Templates

Repositori ini berisi kumpulan template HTML yang digunakan untuk proses penilaian, evaluasi, dan dokumentasi dalam sistem **Contractor Safety Management System (CSMS)** di PT PLN (Persero). Setiap template dirancang menggunakan **Inline CSS** untuk memastikan konsistensi tampilan saat dicetak maupun dikonversi ke PDF.

## 📄 Daftar Template

### 1. Kualifikasi (Qualification)
*   **`pre-qualification-template.html`**: Formulir kualifikasi awal yang mencakup kriteria *mandatory* dan instruksi lampiran dokumen pendukung.
*   **`pra-qualification-template.html`**: Formulir penilaian prakualifikasi mendetail dengan sistem skoring dan klasifikasi tingkat risiko (Ekstrem hingga Rendah).

### 2. Perencanaan & Pelaksanaan (Planning & Execution)
*   **`hse-template.html`**: Formulir penilaian *HSE Plan* untuk mengevaluasi rencana keselamatan kontraktor sebelum pekerjaan dimulai.
*   **`wip-template.html`**: Formulir pemantauan *Work In Progress* untuk menilai indikator K3L selama masa pelaksanaan proyek.

### 3. Evaluasi Akhir (Final Evaluation)
*   **`final-eval-template.html`**: Template evaluasi akhir untuk merangkum seluruh performa keselamatan kontraktor di akhir masa kontrak.
*   **`kpi-template.html`**: Formulir pemantauan *Key Performance Indicator* (KPI) aspek keselamatan kerja.

### 4. Dokumentasi Administrasi
*   **`berita-acara-template.html`**: Template Berita Acara resmi untuk pengesahan hasil penilaian atau pertemuan kualifikasi.
*   **`dik-template.html`**: Daftar Isian Kontraktor (DIK) yang berisi informasi umum dan profil keselamatan perusahaan.

## 🛠 Fitur Utama
*   **Layout Standar A4**: Dioptimalkan untuk ukuran kertas A4 dengan margin yang presisi.
*   **Inline Styling**: Memastikan gaya visual (warna, border, font) tetap utuh di berbagai *engine* rendering PDF.
*   **Struktur Tabel Kompleks**: Menggunakan `rowspan` dan `colspan` untuk mereplikasi formulir fisik secara digital dengan akurat.
*   **Tipografi Profesional**: Menggunakan font Arial/Helvetica yang mudah dibaca.

## 📁 Struktur Folder
*   `/images`: Berisi aset gambar seperti logo PLN yang digunakan dalam setiap template.
*   `/*.html`: File sumber template HTML.

---
*Dikembangkan untuk CSMS Workspace - PT PLN (Persero).*
