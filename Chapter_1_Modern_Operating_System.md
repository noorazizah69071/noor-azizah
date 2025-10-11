# Chapter 1: Modern Operating System

Modern Operating System membahas tentang konsep dasar sistem operasi modern, termasuk manajemen proses, memori, file system, dan keamanan.

Section 1.1 – Pengantar Sistem Operasi

Sistem operasi (Operating System/OS) adalah perangkat lunak sistem yang berfungsi sebagai penghubung antara pengguna dan perangkat keras komputer.
Tanpa sistem operasi, pengguna tidak bisa menjalankan program aplikasi, karena OS-lah yang mengatur semua komunikasi dengan perangkat keras.

Fungsi utama OS:

Menyediakan antarmuka (interface) antara pengguna dan komputer.

Mengatur jalannya program dan penggunaan sumber daya seperti CPU, memori, dan penyimpanan.

Menjamin efisiensi, keamanan, dan keandalan sistem komputer.

Contoh OS: Windows, Linux, macOS, Android, iOS.

Section 1.2 – Sejarah Perkembangan Sistem Operasi

Sistem operasi berkembang seiring kemajuan teknologi komputer.
Secara garis besar:

Generasi 1 (1940–1950-an) – Komputer belum punya OS. Semua program dijalankan langsung lewat saklar dan kabel.

Generasi 2 (1950–1960-an) – Muncul Batch System, di mana tugas dikumpulkan dan dijalankan berurutan tanpa interaksi pengguna.

Generasi 3 (1960–1970-an) – Muncul Time Sharing System, memungkinkan banyak pengguna mengakses komputer secara bersamaan.

Generasi 4 (1980-an ke atas) – Lahir OS modern seperti UNIX, Windows, dan macOS yang mendukung GUI dan multitasking.

Era Modern (2000-an–sekarang) – Sistem operasi mendukung virtualisasi, cloud computing, dan perangkat mobile.

Section 1.3 – Fungsi Utama Sistem Operasi

Sistem operasi punya berbagai fungsi penting untuk mendukung kinerja komputer:

Manajemen Proses – Mengatur pembuatan, penjadwalan, dan penghentian proses.

Manajemen Memori – Mengalokasikan dan mengatur penggunaan RAM oleh berbagai program.

Manajemen File – Mengatur penyimpanan, pembuatan, penghapusan, dan akses file.

Manajemen Perangkat I/O – Mengontrol perangkat input-output seperti keyboard, printer, atau hard disk.

Keamanan dan Proteksi – Menjaga sistem dari akses tidak sah dan kesalahan pengguna.

Section 1.4 – Jenis-jenis Sistem Operasi

Beberapa jenis sistem operasi berdasarkan cara kerjanya:

Batch Operating System – Menjalankan kumpulan program tanpa interaksi pengguna.

Time-Sharing System – Beberapa pengguna bisa menggunakan sistem secara bersamaan.

Real-Time System – Digunakan untuk sistem yang butuh respon cepat (misal: pesawat, robotik).

Distributed System – Menggunakan beberapa komputer yang saling terhubung untuk menyelesaikan tugas bersama.

Mobile Operating System – Dirancang untuk smartphone dan tablet (contoh: Android, iOS).

## Section 1.5 – Arsitektur Sistem Operasi

Arsitektur OS menjelaskan struktur dan bagian penyusunnya:

Kernel – Inti dari OS, mengatur semua operasi dasar perangkat keras.

Shell – Antarmuka antara pengguna dan kernel (dalam bentuk CLI atau GUI).

System Libraries – Kumpulan fungsi yang bisa digunakan aplikasi untuk berinteraksi dengan kernel.

System Utilities – Program bantu untuk pengelolaan sistem (contoh: task manager, file explorer).

## Section 1.6 – Proses dan Thread

Proses adalah program yang sedang dieksekusi.
Tiap proses memiliki memori, sumber daya, dan status eksekusi sendiri.

Thread adalah bagian dari proses yang dapat berjalan secara bersamaan (multithreading).

Contoh: Browser menjalankan satu proses utama, dan setiap tab adalah thread terpisah.

Keuntungan multithreading:

Eksekusi lebih cepat

Penggunaan CPU lebih efisien

Respons aplikasi meningkat

## Section 1.7 – Manajemen Memori

Manajemen memori adalah tugas OS untuk:

Mengalokasikan memori ke proses yang berjalan.

Melindungi memori antar proses.

Menggunakan memori virtual agar program besar tetap bisa dijalankan.

Teknik yang digunakan:

Paging – Membagi memori menjadi blok-blok kecil (page).

Segmentation – Membagi berdasarkan logika program (fungsi, data, dll).

## Section 1.8 – Sistem Berkas (File System)

Sistem berkas adalah metode yang digunakan OS untuk menyimpan dan mengatur data di penyimpanan sekunder (hard disk, SSD).

Fungsi file system:

Menyimpan data secara terstruktur.

Menyediakan akses baca/tulis.

Menangani izin akses pengguna.

Contoh file system:

FAT32, NTFS (Windows)

ext3/ext4 (Linux)

APFS (macOS)