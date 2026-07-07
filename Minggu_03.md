# Jurnal Pembelajaran Minggu 03: Ekstraksi Teks dan Indikator Kompromi (IoC)

### 1. Apa yang Dipelajari Minggu Ini?
Pembelajaran minggu ini berfokus pada teknik ekstraksi teks konstan (*strings extraction*) yang tertanam di dalam seksi `.rodata` berkas biner. Saya berhasil memanfaatkan fitur *Defined Strings* di Ghidra untuk mengidentifikasi keberadaan teks-teks mencurigakan. Melalui tanda teks tersebut, seorang analis dapat mengungkap identitas tersembunyi serta niat operasional asli dari pembuatan suatu program malware.

### 2. Konsep yang Belum Dipahami (Log Belajar Jujur)
Kendala utama saya minggu ini adalah membedakan *strings* bawaan *compiler* (seperti pustaka standar GCC atau referensi Alpine Linux) dengan *strings* murni milik malware. Terlalu banyak data sampah (*noise data*) di dalam jendela dekompiler yang sering kali mengecoh proses analisis. Saya harus lebih jeli dalam memfilter karakter teks agar pencarian Indikator Kompromi (IoC) berjalan efektif.

### 3. Tautan Referensi dan Media Belajar
- Modul Praktikum: *Extracting Malicious Signatures using Floss and Ghidra Strings*.
- Threat Intelligence Portal: *MalwareBazaar abuse.ch Analysis Guides*.
