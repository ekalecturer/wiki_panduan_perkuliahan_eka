---
title: "Contoh Laporan Akhir UAS (Ilustratif)"
tags: [dti, panduan]
---

# Contoh Laporan Akhir UAS (Ilustratif)

# Contoh Laporan Akhir UAS — Desain Thinking dan Inovasi

> **CONTOH ILUSTRATIF — bukan untuk disalin langsung.** Mitra, nama tim, angka, dan kutipan pelanggan di bawah ini fiktif, dibuat untuk menunjukkan struktur dan kedalaman analisis yang diharapkan sesuai Panduan_UAS.md dan rubrik resmi (lihat Rubrik Penilaian Lengkap — UAS). Laporan Anda harus memakai mitra dan data riil dari sprint kelompok Anda sendiri. Struktur laporan mengikuti bagian “Struktur Laporan Akhir yang disarankan” di Panduan_UAS.md, diadaptasi gaya penyajiannya dari Panduan_Laporan_Roadmap_Transformasi_Digital.docx (mata kuliah Pengantar Bisnis Digital) — bukan disalin persis, karena proyek UAS Desain Thinking dan Inovasi berbasis Design Sprint 5 tahap, bukan wawancara roadmap.

**Kelompok:** Kelompok 4 (contoh) — **Mitra:** Warung Bu Sari, Balikpapan — **Minggu presentasi:** UAS Sesi 1 (Minggu 15, contoh)

## 1. Ringkasan Eksekutif

Warung Bu Sari adalah usaha kuliner rumahan di Balikpapan yang kehilangan sekitar 30% pelanggan makan siang pada jam sibuk (12.00-13.00) karena antrean kasir terlalu lambat. Kelompok kami menjalankan Design Sprint lima tahap bersama Bu Sari, menghasilkan purwarupa sistem pre-order lewat kode QR di meja. Uji coba ke 7 pelanggan riil menunjukkan hasil positif sebagian: 5 dari 7 pelanggan berhasil pre-order lancar, tapi 2 pelanggan berusia 50 tahun ke atas kesulitan memakai QR. Setelah iterasi menambahkan opsi pre-order manual paralel, waktu tunggu kasir turun dari rata-rata 6 menit menjadi 3,5 menit — mendekati target di bawah 3 menit, meski belum tercapai penuh pada jam puncak tertentu. Business case menunjukkan investasi awal (2 tablet kasir, ± Rp3.000.000) berpotensi kembali dalam waktu kurang dari dua bulan lewat kenaikan pelanggan terlayani per jam puncak. Rekomendasi utama kami: pertahankan opsi kasir manual paralel dengan QR, jangan menggantikannya total.

## 2. Profil Mitra & Problem Statement Awal (Minggu 9)

**Nama usaha:** Warung Bu Sari. **Lokasi:** Balikpapan Tengah, dekat kawasan perkantoran. **Profil pemilik:** Ibu Sari, mengelola warung sejak 2016, awalnya katering kecil untuk kantor sekitar sebelum membuka warung tetap pada 2019. **Skala usaha:** rata-rata 80-100 pelanggan/hari, omzet bulanan sekitar Rp35-40 juta, dibantu 2 karyawan (satu di dapur, satu di kasir).

**Problem statement yang disepakati tertulis bersama mitra (Minggu 9):**

> “Warung Bu Sari kehilangan sekitar 30% pelanggan makan siang pada jam 12.00-13.00 karena antrean kasir terlalu lambat (rata-rata 6 menit/pelanggan). Target: mengurangi waktu tunggu kasir menjadi di bawah 3 menit tanpa menambah pegawai tetap, dalam kapasitas modal yang realistis bagi usaha skala Bu Sari.”

**Long-term goal:** meningkatkan kapasitas layanan jam puncak tanpa mengorbankan kualitas pelayanan personal yang selama ini jadi ciri khas warung.

## 3. Dokumentasi Design Sprint per Tahap

### 3.1 Understand & Map

Kelompok memetakan alur pelanggan eksisting: datang → antre di kasir untuk memesan sekaligus membayar → menunggu makanan diantar. Titik hambatan (bottleneck) teridentifikasi di satu meja kasir yang merangkap tugas mencatat pesanan manual dan menghitung pembayaran, sering terhenti karena pelanggan masih memutuskan menu di depan kasir. Peta perjalanan pelanggan (customer journey map) menunjukkan rata-rata 6 menit dari antre sampai selesai bayar, dengan 70% waktu terpakai pada tahap “memutuskan & mencatat pesanan”, bukan pembayaran itu sendiri.

### 3.2 Sketch

Setiap anggota kelompok (4 orang) membuat sketsa solusi individu secara terpisah sebelum didiskusikan. Empat arah solusi yang muncul: (1) kasir kedua di jam puncak, (2) mesin self-order berlayar sentuh, (3) pre-order lewat kode QR di meja, (4) sistem antre nomor digital tanpa mengubah alur pemesanan. Opsi (1) dan (2) disingkirkan di tahap Sketch karena membutuhkan biaya/tenaga kerja tambahan yang melampaui batas modal Bu Sari (problem statement eksplisit menyebut “tanpa menambah pegawai tetap”).

### 3.3 Decide

Voting internal kelompok (dot-voting) memilih opsi (3) pre-order lewat QR di meja sebagai solusi utama, dengan opsi (4) sebagai cadangan bila QR terlalu sulit diadopsi pelanggan lanjut usia — keputusan ini berdasarkan observasi Understand & Map bahwa sebagian pelanggan tetap warung berusia di atas 50 tahun. Storyboard solusi: pelanggan duduk → scan QR di meja → pilih menu di ponsel sendiri → pesanan otomatis masuk ke dapur → bayar saat makanan diantar (bukan di kasir).

### 3.4 Prototype

Purwarupa dibangun dalam bentuk mock-up interaktif memakai Google Form terhubung QR code (bukan aplikasi native, sesuai prinsip purwarupa cukup nyata untuk diuji, bukan produk jadi). Menu dan harga disalin persis dari menu asli Warung Bu Sari. Kartu QR dicetak dan ditempel di 6 meja untuk keperluan uji coba.

### 3.5 Test

Purwarupa diuji ke 7 pelanggan riil Warung Bu Sari selama dua sesi makan siang berturut-turut, dengan kelompok mengamati langsung dari sudut warung (bukan menyimulasikan ke teman sekelas).

## 4. Hasil User Testing

| Pelanggan | Usia (perkiraan) | Hasil                                                                                           |
|-----------|------------------|-------------------------------------------------------------------------------------------------|
| P1-P5     | 20-45 tahun      | Berhasil pre-order via QR tanpa bantuan, rata-rata 1,5 menit dari duduk sampai pesanan terkirim |
| P6        | 58 tahun         | Kesulitan scan QR, akhirnya dibantu anak yang menemani makan                                    |
| P7        | 63 tahun         | Menyerah memakai QR setelah dua kali percobaan, kembali memesan manual ke kasir                 |

**Temuan tidak sesuai hipotesis awal (dilaporkan apa adanya, tidak disaring):** kelompok berasumsi seluruh pelanggan akan nyaman dengan QR asal instruksinya jelas. Kenyataannya, 2 dari 7 pelanggan (kategori usia lebih tua) tidak terbantu instruksi tertulis maupun lisan — hambatannya bukan kejelasan instruksi, tapi keengganan mencoba teknologi baru sama sekali. Ini insight yang tidak muncul di tahap Understand & Map, dan baru kelihatan lewat testing langsung.

## 5. Sintesis & Rencana Tindak Lanjut

Gap antara hipotesis (semua pelanggan bisa pakai QR dengan instruksi jelas) dan temuan riil (sebagian pelanggan menolak teknologi baru terlepas dari kejelasan instruksi) mengarahkan kelompok untuk tidak menjadikan QR satu-satunya jalur, melainkan jalur utama dengan opsi manual tetap tersedia. Rencana tindak lanjut: uji versi revisi (QR + opsi manual paralel) pada sesi testing lanjutan.

## 6. Proses Iterasi & Validasi Lanjutan

Berdasarkan temuan Test, kelompok menambahkan opsi pre-order manual ke kasir untuk pelanggan yang tidak nyaman dengan QR, sambil tetap mendorong QR sebagai jalur utama untuk mempercepat proses. Validasi lanjutan pada minggu berikutnya (10 pelanggan baru, termasuk 3 pelanggan lanjut usia) menunjukkan waktu tunggu turun ke rata-rata 3,5 menit — mendekati target di bawah 3 menit, namun belum tercapai penuh. Kelompok mengidentifikasi penyebabnya: pada menit-menit puncak (12.15-12.35), volume pelanggan datang bersamaan tetap membuat dapur jadi bottleneck baru, bukan lagi kasir.

## 7. Business Case: BMC Warung Bu Sari & Analisis Kelayakan

BMC Warung Bu Sari dipetakan ulang dengan perubahan pada tiga blok, menggunakan data hasil sprint (bukan tebakan):

| Blok BMC          | Kondisi Sebelum                              | Kondisi Setelah (usulan)                                                                                                          |
|-------------------|----------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|
| Channels          | Hanya kasir tatap muka                       | Kasir tatap muka + pre-order QR di meja                                                                                           |
| Key Resources     | Kasir manual, buku catatan pesanan           | Ditambah 2 tablet kasir + QR code per meja                                                                                        |
| Cost Structure    | Tidak ada biaya digital                      | Investasi awal ±Rp3.000.000 (2 tablet + pencetakan QR), biaya berulang minimal (tanpa biaya langganan karena memakai Google Form) |
| Value Proposition | Makanan rumahan cepat saji, harga terjangkau | Ditambah: waktu tunggu lebih singkat di jam sibuk                                                                                 |
| Customer Segments | Pekerja kantoran sekitar, semua usia         | Tidak berubah — solusi dirancang tetap inklusif untuk pelanggan lanjut usia lewat opsi manual paralel                             |
| Revenue Streams   | Penjualan langsung per porsi                 | Tidak berubah secara struktur, tapi volume pelanggan terlayani per jam puncak berpotensi naik                                     |

**Analisis kelayakan sederhana:** dengan estimasi tambahan 15 pelanggan terlayani per hari pada jam puncak (dari kapasitas yang sebelumnya hilang karena antrean panjang) dan rata-rata nilai transaksi Rp25.000, potensi tambahan pendapatan sekitar Rp375.000/hari atau ±Rp9.750.000/bulan (26 hari operasional) — investasi awal Rp3.000.000 secara kasar impas dalam waktu kurang dari dua minggu operasional pada estimasi ini. Catatan kelompok: estimasi ini optimistis dan perlu divalidasi mitra pada bulan pertama implementasi nyata, bukan angka final yang dijamin.

## 8. Rekomendasi Akhir & Rencana Implementasi

**Prioritas 1 (segera):** pertahankan opsi kasir manual paralel dengan QR, jangan menggantikan total — 2 dari 7 pelanggan uji coba (dan proporsi serupa pada validasi lanjutan) tidak terbantu oleh QR sama sekali, terlepas dari kejelasan instruksi.

**Prioritas 2 (1 bulan setelah implementasi):** evaluasi ulang rasio penggunaan QR vs manual, untuk melihat apakah pelanggan lama mulai terbiasa seiring waktu atau proporsi penolakan tetap stabil.

**Prioritas 3 (jika Prioritas 1-2 berjalan baik):** eksplorasi solusi untuk bottleneck dapur pada menit-menit puncak (12.15-12.35), yang muncul sebagai hambatan baru setelah kasir tidak lagi jadi titik tersempit — di luar cakupan sprint ini, tapi relevan untuk pihak yang melanjutkan kerja sama dengan Bu Sari.

**Penanggung jawab tindak lanjut di sisi mitra:** Ibu Sari dan satu karyawan kasir yang sudah dilatih kelompok menggunakan sistem tablet selama sesi validasi lanjutan.

*(Perhatikan pola laporan ini: setiap klaim merujuk data testing spesifik — bukan asumsi generik; kegagalan sebagian dilaporkan apa adanya, bukan disembunyikan; business case memakai ulang BMC secara eksplisit dengan angka yang bisa ditelusuri balik ke hasil sprint; dan rekomendasi diprioritaskan bertingkat, bukan daftar datar. Itu yang membedakan skor tinggi dari skor rendah pada Rubrik Penilaian Lengkap — UAS.)*
