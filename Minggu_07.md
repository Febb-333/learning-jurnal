# Jurnal Pembelajaran Minggu 07: Observasi Runtime, Lonjakan CPU, dan Log Error

### 1. Apa yang Dipelajari Minggu Ini?
Saya mempraktikkan pengeksekusian langsung berkas biner `.elf` setelah merubah hak akses memori menggunakan perintah `chmod +x`. Menggunakan alat pemantau sistem `top`/`htop`, saya menyaksikan secara langsung bukti kerusakan berupa lonjakan penggunaan CPU hingga menyentuh batas maksimal 100%. Saya juga mengamati bagaimana biner menghasilkan *log error* persisten `connect error: "connection refused"` akibat terputusnya akses internet.

### 2. Konsep yang Belum Dipahami (Log Belajar Jujur)
Saya masih belum memahami cara melacak alur eksekusi dinamis menggunakan perkakas *Debugger* interaktif (seperti GDB di Linux) untuk menghentikan program di memori virtual. Melakukan penelusuran baris demi baris (*stepping*) saat biner sedang memakan resource CPU tinggi terasa sangat membingungkan karena instruksi mesin berjalan sangat cepat. Saya membutuhkan panduan lanjut untuk teknik *hardware breakpoint*.

### 3. Tautan Referensi dan Media Belajar
- Dokumentasi Alat: *Linux Command-Line Monitoring Tools Guide (htop/top manual)*.
- Artikel Komunitas: *Debugging Stripped ELF Malwares with GDB Basics*.
