# Jurnal Pembelajaran Minggu 04: Anatomi Mesin Parasit XMRig Cryptojacking

### 1. Apa yang Dipelajari Minggu Ini?
Minggu ini saya mengkaji studi kasus nyata mengenai aktivitas malware berjenis *cryptojacking* melalui sampel biner XMRig. Berdasarkan hasil dekompilasi, saya mendeteksi adanya *hardcoded strings* spesifik seperti versi biner `XMRig/6.26.0` dan algoritma `cryptonight/v8`. Temuan ini membuktikan secara ilmiah bahwa biner sengaja dirancang untuk membajak daya komputasi guna melakukan penambangan aset kripto secara ilegal.

### 2. Konsep yang Belum Dipahami (Log Belajar Jujur)
Saya masih belum memahami sepenuhnya bagaimana arsitektur protokol *Stratum* (`mining.authorize` dan `mining.subscribe`) mengemas paket pekerjaan penambangan. Alur pertukaran data antara biner penambang lokal dengan peladen luar (*Mining Pool*) masih terasa abstrak karena hanya terlihat berupa teks statis di dalam kode mesin biner. Saya memerlukan analisis paket lebih lanjut untuk melihat interaksinya secara nyata.

### 3. Tautan Referensi dan Media Belajar
- Dokumentasi Resmi Penambang: *XMRig CPU/GPU Miner Documentation*.
- Analisis Varian: *Practical Reverse Engineering: Obfuscation and Reversing Tools* (Dang et al.).
