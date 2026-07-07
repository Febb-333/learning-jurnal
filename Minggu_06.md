# Jurnal Pembelajaran Minggu 06: Metodologi Analisis Dinamis dan Isolasi Lab

### 1. Apa yang Dipelajari Minggu Ini?
Minggu ini saya beralih dari analisis pasif statis ke metodologi Analisis Dinamis (*Runtime Analysis*). Saya mempelajari pentingnya aspek keselamatan laboratorium siber menggunakan Oracle VM VirtualBox untuk mengisolasi file berbahaya. Penonaktifkan adaptor jaringan secara total (*disconnected mode*) merupakan langkah mutlak agar malware tidak menyebar ke sistem fisik host maupun melakukan serangan ke infrastruktur internet luar.

### 2. Konsep yang Belum Dipahami (Log Belajar Jujur)
Saya masih kebingungan dalam merencanakan teknik simulasi jaringan lokal yang aman di dalam lab. Mengonfigurasi perangkat lunak simulasi seperti INetSim agar dapat memalsukan respons DNS dan menangkap paket komunikasi Stratum secara lokal membutuhkan keahlian jaringan yang cukup rumit. Sering kali konfigurasi IP virtual saya mengalami bentrok di dalam sistem VM.

### 3. Tautan Referensi dan Media Belajar
- Panduan Lab: *Malware Sandbox Isolation Techniques using VirtualBox*.
- Buku Referensi: *Learning Malware Analysis with Isolation Environments*.
