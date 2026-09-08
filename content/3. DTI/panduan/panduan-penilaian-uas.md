---
title: "Panduan Penilaian UAS (Dosen/Asdos)"
tags: [dti, panduan]
---

# Panduan Penilaian UAS (Dosen/Asdos)

# Panduan Penilaian UAS: Presentasi & Laporan Hasil Sprint (50% Nilai Akhir)

*Untuk dosen/asdos. Panduan tugas untuk mahasiswa ada di Panduan_UAS.md/.docx (format presentasi, struktur laporan, kesalahan umum, contoh laporan lengkap); dokumen ini fokus pada cara menilai dan cara mengisi spreadsheet.*

> **\[DIPERBARUI\]** Bobot UAS naik dari 30% menjadi 50% karena Tugas Tematik Kumulatif (sebelumnya 30%) tidak lagi dinilai: lihat sheet README pada spreadsheet untuk penjelasan redistribusi bobot. Rentang Nilai UAS sekarang genap 0-100 (sebelumnya 25-100 akibat rumus konversi yang salah).

## Tiga Kelompok Kriteria: Jangan Dicampur

UAS dinilai lewat tiga kelompok kriteria, semuanya diisi di sheet UAS pada kolom terpisah:

1.  **Isi-presentasi (draf usulan, 3 kriteria, skor 1-4)**: kedalaman analisis hasil sprint, kualitas rekomendasi ke mitra, integrasi & komunikasi. Deskripsi lengkap tiap level skor ada di Panduan_UAS.md bagian “Rubrik Penilaian Lengkap”.
2.  **Isi-laporan (draf usulan, 2 kriteria, skor 1-4)**: metodologi sprint & rigor testing, business case & keterpaduan BMC.
3.  **Gaya presentasi (resmi, 4 kriteria, skor 0-100 langsung)**: sama seperti UTS: gaya presentasi, penguasaan materi, alat peraga, kemampuan menghadapi pertanyaan, dari SMT 3_RPS Desain Thinking dan Inovasi.docx.

## Cara Mengisi Sheet UAS

Kolom D-F (isi-presentasi) dan G-H (isi-laporan): isi skor 1-4 sesuai rubrik draf usulan di Panduan_UAS.md. Kolom I-L (gaya): isi langsung angka 0-100 sesuai band N-score resmi, sama caranya dengan sheet UTS: jangan dikonversi ke 1-4 dulu.

Sheet otomatis menghitung: rata isi-presentasi dan rata isi-laporan masing-masing dikonversi ke 0-100 lewat rumus (rata-rata-1)/3x100, rata gaya dipakai langsung. Nilai UAS = (isi-presentasi x 25%) + (gaya x 25%) + (isi-laporan x 50%). Laporan diberi bobot lebih besar (50%) karena RPS asli membagi UAS jadi presentasi 15% + laporan 15% dari total 30%, sedangkan isi-presentasi dan gaya-presentasi sama-sama menilai bagian presentasi (15%) sehingga masing-masing diberi separuh. Ini asumsi saya, ganti formula di sheet kalau kebijakan Anda berbeda.

## Kesalahan Penilaian yang Perlu Dihindari

Jangan meluluskan kriteria “Metodologi & Rigor Testing” tanpa mengecek jumlah pelanggan yang benar-benar ditest. Panduan_UAS eksplisit: testing harus melibatkan minimal 5 pelanggan riil mitra: laporan yang testing ke teman sekelas atau keluarga otomatis turun ke skor 1 pada kriteria ini, terlepas dari seberapa rapi laporan itu ditulis.

Jangan menghukum laporan yang jujur melaporkan kegagalan. Panduan_UAS eksplisit menyebut laporan yang mengaku sebagian gagal dinilai lebih tinggi daripada laporan yang terlalu rapi: jangan biarkan kesan “hasil kurang sempurna” menurunkan skor kriteria lain di luar konteksnya.

Jangan meluluskan “Business Case & BMC” hanya karena BMC disebut sekali di laporan. Rubrik menuntut BMC dipakai sebagai alat analisis kelayakan secara eksplisit dan menyeluruh, bukan disebut sepintas.

Jangan lupa mengisi kolom Kelompok di Daftar_Mahasiswa sebelum menilai UAS: mekanismenya sama seperti UTS, nilai tidak muncul di Rekap_Nilai_Akhir kalau kolom Kelompok kosong atau ejaannya tidak sama persis dengan yang diisi di sheet UAS.

## Bobot Terhadap Nilai Akhir

50% dari Nilai Akhir mata kuliah (naik dari 30% asli RPS: lihat catatan redistribusi bobot di sheet README). Ini komponen berbobot terbesar di mata kuliah ini setelah perubahan; pastikan asdos yang menilai memahami seluruh rubrik sebelum sesi presentasi Minggu 15/16, bukan membaca rubrik sambil menilai.
