# Jurnal Pembelajaran Minggu 01: Fondasi Analisis dan Anatomi Berkas ELF

### 1. Apa yang Dipelajari Minggu Ini?
Pada sesi awal pembelajaran minggu ini, saya mendalami fondasi teoretis dari teknik rekayasa balik (*software reverse engineering*) beserta format struktur berkas biner internalnya. Fokus utama saya tertuju pada pemahaman format berkas *Executable and Linkable Format* (ELF) yang menjadi standar fundamental sistem operasi arsitektur Linux. Saya mempelajari fungsi meta-informasi pada komponen *ELF Header* serta pembagian peran dari berbagai seksi memori virtual penting seperti seksi `.text`, `.data`, dan `.rodata`.

### 2. Konsep yang Belum Dipahami (Log Belajar Jujur)
Meskipun pemahaman teoretis mengenai pemetaan segmen biner sudah cukup jelas, saya masih mengalami kendala operasional yang signifikan saat mencoba menginterpretasikan instruksi Assembly tingkat rendah. Pergerakan nilai variabel di dalam register CPU dan instruksi percabangan kondisi kondisional masih sangat sulit dibaca secara intuitif tanpa bantuan kakas dekompiler. Saya perlu berlatih lebih banyak dalam merunut logika register dasar x86-64 agar proses rekayasa balik berjalan lancar.

### 3. Tautan Referensi dan Media Belajar
- Kitab Teoretis: *Practical Malware Analysis: The Hands-On Guide to Dissecting Malicious Software* (Sikorski & Honig).
- Spesifikasi Arsitektur: *System V Application Binary Interface - Executable and Linkable Format (ELF)*.
