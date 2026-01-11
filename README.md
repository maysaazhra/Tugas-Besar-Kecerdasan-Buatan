Anggota Kelompok:
1. I Kadek Rio Adi Pranata Kusuma (103132400029)
2. Maysa Azhra Fauziyyah (103132430005)

Pemilihan Laptop Menggunakan Metode Fuzzy Mamdani dan Fuzzy Sugeno

# Deskripsi 
Program ini dibuat untuk menentukan laptop terbaik menggunakan Sistem Fuzzy.
Penilaian dilakukan berdasarkan dua kriteria utama, yaitu harga dan performa.
Metode fuzzy yang digunakan adalah:
- Fuzzy Mamdani
- Fuzzy Sugeno
Seluruh proses fuzzy dibuat secara manual menggunakan Python, tanpa menggunakan library fuzzy siap pakai, sesuai dengan ketentuan tugas.

# Tujuan Program
- Menerapkan konsep logika fuzzy secara langsung dalam program
- Membandingkan hasil metode Mamdani dan Sugeno
- Menampilkan 5 laptop terbaik berdasarkan skor kelayakan
- Menampilkan grafik fungsi keanggotaan dan grafik perbandingan hasil

# Variabel Fuzzy
- Input
  1. Harga : Murah, Sedang, Mahal
  2. Performa : Rendah, Sedang, Tinggi
- Output
  Kelayakan laptop
  1. Low
  2. Medium
  3. High
 
# Fungsi Keanggotaan
Fungsi keanggotaan yang digunakan adalah fungsi dengan rentang nilai 0–100.
Fungsi ini digunakan untuk mengubah nilai harga dan performa menjadi derajat keanggotaan fuzzy.

# Aturan Inferensi
Sistem menggunakan 9 aturan fuzzy, contoh:
- Jika harga murah dan performa tinggi maka laptop layak
- Jika harga mahal dan performa rendah maka laptop tidak layak
Aturan ini digunakan dalam proses inferensi untuk menentukan kelayakan laptop.

# Metode Perhitungan
- Fuzzy Mamdani
1. Menggunakan metode Min–Max untuk inferensi
2. Menggunakan metode Centroid untuk defuzzifikasi
3. Menghasilkan nilai yang lebih moderat
- Fuzzy Sugeno
1. Menggunakan output berupa nilai konstanta
2. Menggunakan metode Weighted Average
3. Lebih sederhana dan cepat secara komputasi

# Output Program
Program menghasilkan:
- Daftar 5 laptop terbaik
Informasi yang ditampilkan:
- ID Laptop
- Harga
- Performa
- Skor Mamdani
-Skor Sugeno
