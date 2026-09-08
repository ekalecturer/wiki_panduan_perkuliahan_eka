---
title: "Panduan Penilaian UTS (Dosen/Asdos)"
tags: [dti, panduan]
---

# Panduan Penilaian UTS (Dosen/Asdos)

# Panduan Penilaian UTS: Presentasi BMC (30% Nilai Akhir)

*Untuk dosen/asdos. Panduan tugas untuk mahasiswa ada di Panduan_UTS.md/.docx (format presentasi, kesalahan umum, contoh outline); dokumen ini fokus pada cara menilai dan cara mengisi spreadsheet.*

> **\[DIPERBARUI\]** Bobot UTS naik dari 20% menjadi 30% karena Tugas Tematik Kumulatif (sebelumnya 30%) tidak lagi dinilai: lihat sheet README pada spreadsheet untuk penjelasan redistribusi bobot. Rentang Nilai UTS sekarang genap 0-100 (sebelumnya 25-100 akibat rumus konversi yang salah).

## Dua Kelompok Kriteria: Jangan Dicampur

UTS dinilai lewat dua rubrik yang sumbernya berbeda dan harus diisi terpisah di sheet UTS:

1.  **Isi (draf usulan, 4 kriteria, skor 1-4)**: problem clarity, kelengkapan BMC, justifikasi model bisnis, presentasi & Q&A isi. Deskripsi lengkap tiap level skor ada di Panduan_UTS.md bagian “Rubrik Penilaian Lengkap”.
2.  **Gaya presentasi (resmi, 4 kriteria, skor 0-100 langsung)**: gaya presentasi, penguasaan materi, alat peraga, kemampuan menghadapi pertanyaan. Ini rubrik resmi dari SMT 3_RPS Desain Thinking dan Inovasi.docx, sudah dalam skala N (0-100), bukan 1-4.

## Cara Mengisi Sheet UTS

Kolom isi (D-G): isi skor 1-4 sesuai rubrik draf usulan di Panduan_UTS.md. Kolom gaya (H-K): baca band deskripsi resmi di tabel N-score (N\>81, 73\<N\<81, 66\<N\<73, 60\<N\<66, 55\<N\<60, N\<55), lalu isi angka 0-100 yang mencerminkan band tempat kelompok itu berada. Jangan mengonversi band ke 1-4 dulu; masukkan langsung sebagai angka 0-100 (misal kelompok yang jelas berada di band “73\<N\<81”, isi angka di rentang itu, bukan skor 3).

Sheet otomatis menghitung: rata-rata isi dikonversi ke 0-100 lewat rumus (rata-rata-1)/3x100, rata-rata gaya dipakai langsung (sudah 0-100), lalu Nilai UTS = (rata isi x 50%) + (rata gaya x 50%). Bobot 50/50 antara isi dan gaya ini asumsi saya sendiri, karena sumber tidak menetapkan bobot campuran resmi: ganti formula di sheet kalau kebijakan Anda berbeda.

## Kesalahan Penilaian yang Perlu Dihindari

Jangan menilai gaya presentasi dari kesan pertama saja. Rubrik resmi menuntut observasi sepanjang sesi (kontak mata, ketergantungan pada catatan, respons ke pertanyaan): kelompok yang mulai gugup tapi membaik saat Q&A tidak otomatis dapat skor rendah di seluruh kriteria gaya.

Jangan meluluskan kriteria isi “Kelengkapan BMC” hanya karena 9 blok terisi. Rubrik menuntut blok-blok itu saling konsisten; BMC dengan 9 blok terisi tapi saling bertentangan (misal Customer Segments generik sementara Value Proposition sangat spesifik) tetap turun skor.

Jangan lupa mengisi kolom Kelompok di Daftar_Mahasiswa sebelum menilai UTS: Rekap_Nilai_Akhir menarik nilai lewat nama kelompok, dan nilai tidak akan muncul di rekap kalau kolom itu kosong atau ejaannya beda dari yang diisi di sheet UTS.

## Bobot Terhadap Nilai Akhir

30% dari Nilai Akhir mata kuliah (naik dari 20% asli RPS: lihat catatan redistribusi bobot di sheet README).
