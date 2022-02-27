# Tugas Kecil 2 Strategi Algoritma

<i>Azka Syauqy Irsyad</i>

Repository ini dibuat dalam rangka memenuhi Tugas Kecil 2 Mata Kuliah Strategi Algoritma Tahun 2021/2022

## Contents

- [Deskripsi Program](#deskripsi-program)
- [Struktur Repository](#struktur-repository)
- [Requirements](#requirements)
- [How to Use](#how-to-use)

## Deskripsi Program

Program <i>Convex Hull</i> ini dibuat dengan memanfaatkan algoritma <i>divide and conquer</i>. Dalam pengeksekusiannya, program akan mengambil data yang bersumber dari <i><b>scikit-learn</b></i>, yang kemudia dari data tersebut dibuatkan suatu <i>dataframe</i>. Kemudian, akan dipilih dua atribut dari data tersebut untuk dilakukan pencarian titik-titik untuk membentuk <i>convex hull</i>. Daftar koordinat titik yang ada pada dua atribut yang dipilih akan diproses, mulai dari mengurutkan titik berdasarkan absis serta ordinat yang menaik, mengambil titik ekstrem, membagi ke dalam dua partisi sisi berdasarkan garis acuan, dan mencari jarak terjauh di masing-masing sisi tersebut. Proses tersebut dilakukan secara rekursif hingga tidak ada lagi titik yang dapat di proses. Setelah itu, solusi dari masing-masing titik akan diurutkan, dengan bagian atas diurutkan menaik sedangkan dibagian bawah diurutkan menurun, yang kemudian akan dilakukan proses penggabungan dari kedua solusi tersebut. Solusi final itu akan dihubungkan dengan memanfaatkan <i>library plotting</i> yang ada.

## Struktur Repository

Repository ini terdiri dari 2 <i> child directory </i> dan satu file README.

1. **doc** yang berisi file laporan tugas.
2. **src** yang berisi <i>source code</i> program yang dibutuhkan untuk mengeksekusi program.
3. **README.md**

## Requirements

Untuk dapat menjalankan program, terlebih dahulu untuk mengunduh <i><b>library matplotlib, numpy, scikit-learn,</b></i> dan <i><b>pandas</b></i>.

## How to Use

1. <i>Clone</i> repository ini di <i>directory</i> yang diinginkan;
2. Buka aplikasi VS Code atau sejenisnya yang dapat me-<i>run</i> file .ipynb;
3. Buka folder tempat Anda menyimpan repository ini;
4. Buka folder **src**;
5. Buka file `hull.ipynb`;
6. <i>Run</i> kotak pertama yang berisi algoritma <i>convex hull</i>;
7. Setelah selesai <i>run</i>, <i>run</i> masing-masing kotak yang ada di bawahnya;
8. Hasil <i>convex hull</i> akan muncul dalam plot.