Tugas Besar Mata Kuliah Kecerdasan Buatan

Fuzzy Logic

Rekomendasi Bengkel Terbaik
 
ANGGOTA  : 
1. Khairun Fahmi (103132400035)
2. Ahnaf Ariacheda (103132400037)

---------------------------------------------------------
Deskripsi Singkat

Program ini menggunakan Logika Fuzzy metode Sugeno untuk menentukan 
5 bengkel terbaik berdasarkan input "Kualitas Servis" (1-100) dan "Harga" (1-10).
Program dibuat murni menggunakan Python tanpa library Fuzzy (scikit-fuzzy).

---------------------------------------------------------
Spesifikasi File

1. main.py        : Source code utama program.
2. bengkel.xlsx   : Dataset input (100 data bengkel).
3. Readme.txt     : Panduan penggunaan program.

---------------------------------------------------------
Cara Menjalankan Program

A. Menggunakan Google Colab (Disarankan)
1. Buka Google Colab.
2. Upload file 'main.py' dan 'bengkel.xlsx' ke penyimpanan sesi (folder icon di kiri).
3. Jalankan script 'main.py'.
4. Hasil output akan muncul sebagai file baru dengan nama 'top5_bengkel_terbaik.xlsx'.

B. Menggunakan Terminal/VS Code (Lokal)
1. Pastikan Python sudah terinstal.
2. Pastikan library pandas dan openpyxl sudah terinstal:
   pip install pandas openpyxl
3. Letakkan 'main.py' dan 'bengkel.xlsx' dalam satu folder.
4. Buka terminal di folder tersebut, ketik:
   python main.py
5. File output 'top5_bengkel_terbaik.xlsx' akan terbentuk otomatis.

---------------------------------------------------------
Struktur Data Output
Output berupa file Excel berisi 5 baris data dengan kolom:
- id      : ID Bengkel
- servis  : Nilai input servis
- harga   : Nilai input harga
- skor    : Hasil perhitungan Defuzzifikasi (0-100)

Khairun Fahmi : Source Program dan File Readme
Ahnaf Ariacheda : Poster

