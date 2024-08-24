
# UJIAN TENGAH SEMESTER
Genap 2023/2024-CS

**Mata Kuliah**: Pemrograman Berorientasi Objek  
**Hari tanggal - Kelas**: April 2024 - CS  
**Waktu - Sifat**: 120 menit - Close Book  
**Dosen**: Randi Farman Putra, M.Si  

## Working Instruction:
Buat jawaban berupa kode Java di kertas jawaban yang disediakan!

## Question:
(CPMK 1,2, dan 3)

1. **(15 poin)** Buatlah sebuah kelas `Dosen` dalam package `dosen`  
   a. Buatkan attribute private `nama` dan `NIDN`. NIDN adalah Nomor Induk Dosen Nasional.  
   b. Buatkan konstruktor untuk inisialisasi `nama` dan `NIDN`.  
   c. Buatkan method getter untuk seluruh attribute.  

2. **(15 poin)** Buatlah sebuah kelas `Mahasiswa` dalam package `Mahasiswa`  
   a. Buatkan attribute private `nama` dan `NIM`. NIM adalah Nomor Induk Mahasiswa.  
   b. Buatkan konstruktor untuk inisialisasi `nama` dan `NIM`.  
   c. Buatkan method getter untuk seluruh attribute.  

3. **(30 poin)** Buatlah sebuah kelas `MataKuliah` dalam package `MataKuliah`  
   a. Buatkan attribute private `nama`, `KodeMK` adalah kode mata kuliah, `ArrayList<Dosen>` `pengampu` dan `ArrayList<Mahasiswa>` `daftarMahasiswa`.  
   b. Buatkan konstruktor untuk inisialisasi `nama` dan `kodeMK`.  
   c. Buatkan method setter untuk attribute `daftarMahasiswa` dan `pengampu`.  
   d. Buatkan method getter untuk seluruh attribute.  

4. **(40 poin)** Buatlah kelas `Utama` dalam package `Utama`  
   a. Dalam method `main`, buat objek dan set pengampu dan daftar mahasiswa untuk tiap mata kuliah seperti tabel berikut:  

   | Mata Kuliah   | Kode Mata Kuliah | Pengampu | Mahasiswa         |
   |---------------|------------------|----------|-------------------|
   | PBO           | 123              | Cahya    | Tiara, Diana      |
   | Kompar        | 124              | Budi     | Tiara, Diana      |
   | Metnum        | 125              | Budi     | Tiara             |

   b. Buatkan method static `tampilkanData(MataKuliah matakuliah)` untuk menampilkan data pengampu dan daftar mahasiswa untuk tiap mata kuliah beserta kode mata kuliahnya dan panggil method tersebut di `main`.
