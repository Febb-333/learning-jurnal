# Jurnal Pembelajaran Minggu 05: Pelacakan Library Internal dan Profiling Perangkat Keras

### 1. Apa yang Dipelajari Minggu Ini?
Saya mempelajari cara mengidentifikasi pustaka (*internal libraries*) yang dibawa secara langsung oleh biner bertipe *statically linked*. Saya menemukan pemanggilan komponen `libuv` (manajemen jaringan asinkronus), `OpenSSL` (enkripsi data), dan `hwloc` (deteksi topologi perangkat keras). Keberadaan komponen `hwloc` menjelaskan mengapa malware ini mampu mengenali tipe dan jumlah *core* prosesor target secara akurat saat dijalankan.

### 2. Konsep yang Belum Dipahami (Log Belajar Jujur)
Pemahaman saya masih terbatas mengenai mekanisme pemanggilan set instruksi akselerasi kriptografi tingkat perangkat keras seperti `AES-NI`. Saya belum mengerti bagaimana biner berinteraksi langsung dengan register register khusus CPU untuk mempercepat kalkulasi algoritma pertambangan secara sepihak tanpa melewati lapisan kernel. Konsep optimasi memori ini sangat kompleks bagi saya.

### 3. Tautan Referensi dan Media Belajar
- Panduan Topologi: *Hardware Locality (hwloc) Application Binary Interface Standard*.
- Video Edukasi SRE: *OALabs and LiveOverflow Decompilation Sessions*.
