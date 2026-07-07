# Jurnal Pembelajaran Minggu 02: Implementasi Kakas Ghidra dan Stripped Binary

### 1. Apa yang Dipelajari Minggu Ini?
Minggu ini saya mulai mempelajari penggunaan aplikasi dekompiler Ghidra untuk melakukan analisis statis pada sampel biner berbahaya. Saya mempelajari cara memuat file, menganalisis jendela *Import Results Summary*, serta memetakan komponen biner melalui *Program Trees*. Pemahaman saya bertambah mengenai bagaimana Ghidra menyusun abstraksi dari instruksi bahasa mesin menjadi pseudokode bahasa C yang lebih mudah dipahami oleh analis.

### 2. Konsep yang Belum Dipahami (Log Belajar Jujur)
Saya menemui kesulitan besar saat menghadapi biner yang berstatus *stripped binary* karena seluruh informasi simbol *debugging* telah dihapus. Hal ini membuat nama-nama fungsi asli berubah menjadi penamaan acak otomatis seperti `FUN_004a0db0`. Merunut fungsi utama (*main function*) di antara ratusan fungsi acak tersebut terbukti membutuhkan waktu dan intuisi yang sangat tinggi.

### 3. Tautan Referensi dan Media Belajar
- Dokumentasi Resmi: *Ghidra Software Reverse Engineering Framework Documentation* (NSA).
- Panduan Komunitas: *An Introduction to Stripped Binary Reversing* (RE Discord).
