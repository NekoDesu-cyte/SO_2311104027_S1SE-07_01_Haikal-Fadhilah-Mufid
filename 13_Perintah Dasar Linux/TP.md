# <h1 align="center">Laporan Praktikum Modul 13 <br> Perintah Dasar Linux</h1>
<p align="center">Haikal Fadhilah - 2311104027</p>

## Dasar Teori
Pada umumnya default perintah dasar Linux dieksekusi pada Bash (/bin/bash). Bash mengeksekusi 
program dalam OS untuk setiap perintah yang dimasukkkan dalam console
Perintah–perintah di console Linux memiliki aturan–aturan penulisan, aturan struktur penulisan 
perintah Linux tersebut berlaku pada hampir semua perintah–perintah Linux. Penulisan perintah Linux 
bersifat case sensitive artinya adalah setiap penulisan huruf besar dan kecil sangat berpengaruh 
terhadap hasil yang diinginkan.

## Guided

## Jurnal

1. 
    a. ![alt text](image.png)
    b. command ls pada debian ini untuk menampilkan list list file pada file manager
![alt text](image-1.png)

2.  
    a. ![alt text](image-1.png)
    b. option dari perintah diatas antara lain adalah Dekstop, Documents, Downloads, music dll.
    c. fungsi dari ls adalah untuk menampilkan list list file pada file manager.
    d. ![alt text](image-2.png)
    e. banyak sekali option pada perintah tsb
    f. fungsi dari perintah tsb adalah menampilkan semua direktori root secara lengkap.
    g. karena perintah ls hanya menampilkan secara mendasar saja, yang bisa dilihat oleh user, sedangkan ls -all menampilkan semuanya secara lengkap, termasuk file file sistem berekstensi, sedangkan ls biasa hanya menampilkan tertentu saja seperti folder.
    
3.  a. ![alt text](image-3.png)
    b. perintah pwd tidak memiliki option
    c. fungsi dari pwd adalah untuk menampilkan path ubuntu.

4.  a. ![alt text](image-4.png)
    b. tidak ada option dari perintah tersebut
    c. yang dilakukan perintah cd adalah untuk masuk ke direktori tertentu pada file manager. sbg contoh "cd Desktop" 

5.  a. perintah cd / untuk kembali ke direktori awal sebelum masuk ke manapun, sedangkan untuk cd ~ adalah untuk mengembalikan path direktori ke arah semula 
    ![alt text](image-5.png)
    b. Untuk berpindah dari /proc/self ke /, perintah cd .. harus dijalankan sebanyak 2 kali.Pertama dari /proc/self ke /proc, kedua dari /proc ke /.
    ![alt text](image-6.png)

6.  a & b ![alt text](image-7.png)
    c & d ![alt text](image-8.png)
    e & f ![alt text](image-9.png)
    g. ![alt text](image-10.png)

7.  a & b ![alt text](image-11.png)

8.  a. ![alt text](image-12.png)
    b. fungsi ls adalah menampilkan informasi atau daftar file dan direktori. 
    c. Pencipta perintah ls adalah Richard M. Stallman dan David MacKenzie.
    d. Option -h berarti human-readable, yaitu menampilkan ukuran file dalam format yang mudah dibaca, seperti K, M, atau G.
    e. Option yang digunakan adalah -R.
    f. ![alt text](image-13.png)
    g. fungsi man cp adalah untuk menyalin file atau direktori.
    h. Pencipta perintah cp adalah Torbjorn Granlund, David MacKenzie, dan Jim Meyering.
    i. Option -v berarti verbose, yaitu menampilkan proses penyalinan file yang sedang dilakukan.
    j. Option yang digunakan adalah -i.

9.  a. ![alt text](image-14.png)
    b. Perintah cat berfungsi untuk menampilkan isi file ke layar terminal.
    c. ![alt text](image-15.png)
    d. ![alt text](image-16.png)
    e. ![alt text](image-17.png)    
    f. Fungsi | grep daemon adalah memfilter output dari perintah sebelumnya dan hanya menampilkan baris yang mengandung kata daemon.

10. a. ![alt text](image-18.png)
    b. dibagian file manager di bagian "Home" akan muncul file result.txt
    c. ![alt text](image-19.png)
    d. Tanda > berfungsi untuk mengalihkan output dari perintah ke dalam file. Jika file belum ada, file akan dibuat. Jika file sudah ada, isi file lama akan ditimpa dengan output yang baru.

II KOMPILASI KODE

1. 
![alt text](image-21.png)
![alt text](image-20.png)

2. 
![alt text](image-22.png)

3. 
![alt text](image-24.png)
![alt text](image-25.png)
    
4. 
![alt text](image-27.png)

5 & 6
![alt text](image-26.png)

7. Program myopen digunakan untuk mencoba membuka sebuah file dalam mode read-only atau hanya baca. Program menerima satu input berupa nama file saat dijalankan. Jika file berhasil dibuka, program akan menampilkan pesan bahwa file berhasil dibuka. Jika file gagal dibuka, misal karena file tidak ada, program akan menampilkan pesan gagal beserta keterangan error.


    
## Referensi

1. https://en.wikipedia.org/wiki/Data_structure (diakses blablabla)