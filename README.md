# PHP-Modul-1-2-
## MODUL 1
### Membuka File PHP 
Untuk membuka file PHP harus dilakukan dengan menggunakan web server. 
Buka web browser dan ketik http://localhost/nama_file.php . 
Nama file sesuai dengan nama file yang disimpan.
### PHP - Tipe Data 
Dalam bahasa pemrograman yang lain, ada bermacam-macam tipe data, misalnya integer(bilangan bulat), float (bilangan pecahan), char(karakter angka dan huruf), string(kumpulan huruf atau kata), dan berbagai tipe lainnya
Tipe boolean, yang dikenal dalam bahasa program yang lainnya, tidak ada dalam  PHP. 
Untuk menguji benar salah (true/false), kita menggunakan tipe data yang tersedia. FALSE  dapat  digantikan  oleh integer 0, atau string kosong, yaitu "". Selain nilai itu, semua dianggap TRUE. 
### PHP - Variabel
Variabel  digunakan  sebagai  tempat  penyimpanan  data  sementara.  Data  yang  disimpan dalam   variabel   akan   hilang   setelah   program   selesai   dieksekusi.
Untuk  membuat  suatu  variabel  dalam  PHP,  digunakan  tanda  string($)  sebagai pendeklarasian  awal. Aturan – aturan yang dapat digunakan untuk menuliskan variabel adalah sebagai berikut : 
1. Pendeklarasian variabel harus ditandai dengan string ($) 
2. Variabel dapat menggunakan huruf kecil maupun huruf besar atau perpaduan keduanya 
3. Penulisan awal variabel tidak boleh menggunakan angka
4. Apabila ingin menggunakan angka sebagai variabelnya, maka dapat menggunakan tanda underscore(_) untuk memulainya 
5. Nama variabel yang terdiri lebih dari satu kata, dapat dipisahkan dengan underscore (_) 
### Variabel Biasa 
Standar penulisan variabel adalah dengan menggunakan tanda ($) yang kemudian diikuti dengan nama variabel kemudian isi dari variabel. Dari variabel – variabel tersebut dapat dibaca berulang – ulang kali dalam satu halaman web. 
### Variabel dalam Kelompok 
Bentuk variabel ini biasanya digunakan untuk mendeklarasikan data apabila menggunakan fungsi dalam PHP, isi dari data yang ada pada variabel tersebut tidak ditampilkan apabila melakukan pemanggilan fungsi yang mendeklarasikan variabel tersebut. Pemanggilan variabel di dalam sebuah fungsi menggunakan perintah global. Sedangkan untuk melakukan pemanggilan fungsi, cukup dengan memanggil nama fungsinya. 
### Variabel antar Halaman 
Bentuk dari variabel ini biasanya digunakan untuk mengantarkan data yang ada dari setiap variabel ke dalam halaman lain. Bentuk – bentuk variabel ini biasanya berasal dari data seperti form.

## --- LATIHAN ---
#### Latihan 1

Membuat file PHP
![Alt Text](https://github.com/inamyrpl28/PHP-Modul-1-2-/blob/master/modul1%20lat1.PNG)

#### Latihan 2

PHP dalam HTML 
![Alt Text](https://github.com/inamyrpl28/PHP-Modul-1-2-/blob/master/modul1%20lat2.PNG)

#### Latihan 3
Variabel Biasa
![Alt Text](https://github.com/inamyrpl28/PHP-Modul-1-2-/blob/master/modul1%20lat3.PNG)

### Latihan 4

Variabel dalam kelompok 
![Alt Text](https://github.com/inamyrpl28/PHP-Modul-1-2-/blob/master/modul1%20lat4.PNG)

### Latihan 5

Variabel antar halaman 
![Alt Text](https://github.com/inamyrpl28/PHP-Modul-1-2-/blob/master/modul1%20lat5.PNG)

Variabel hasil 
![Alt Text](https://github.com/inamyrpl28/PHP-Modul-1-2-/blob/master/modul1%20variable_hasil.PNG)

#   --------------------------------------------------------------------

## MODUL 2
## OPERATOR dan ARRAY 
### 1. Oparator Arimatika 
Digunakan Untuk melakukan perhitungan matematika
#### Operator :
1. (+) Penjumlahan 
2. (-) Pengurangan 
3. (*) Perkalian 
4. (/) Pembagian 
5. (%) Modulus (Sisa)
### 2. Operator Perbandingan 
Digunakan untuk menguji hubungan antara nilai atau variabel. Operator ini digunakan dalam suatu statement bersyarat yang selalu menghasilkan nilai TRUE atau FALSE.
#### Operator :
(==) Sama Dengan 
(!=) Tidak Sama Dengan 
(<)  Lebih Kecil Dari 
(>)  Lebih Besar Dari 
(<=) Lebih kecil atau sama dengan 
(>=) Lebih Besar atau Sama
### Gabungan Operator Aritmatikan dan Assignment 
Operator aritmatik merupakan operasi untuk perhitungan matematika, sedangkan yang dimaksud dengan operator assignment adalah operator samadengan(=). 
###  Operator Pre/Post Increment dan Decrement 
Merupakan pengembangan dari gabungan operator aritmatik dan assignment. Increment berarti peningkatan/penambahan, sedangkan decrement berarti penurunan/pengurangan. Operator ini hanya digunakan pada proses increment maupun decrement dengan tingkat 1. Artinya semua angka akan selalu dinaikkan / dikurangkan 1. 
### Operator Logika 
Membandingkan dua pilihan nilai, biasanya digunakan pada struktur if – else. 


## --- LATIHAN ---
#### Latihan 1 
![Alt Text](https://github.com/inamyrpl28/PHP-Modul-1-2-/blob/master/modul2%20lat1.PNG)

#### Latihan 2
![Alt Text](https://github.com/inamyrpl28/PHP-Modul-1-2-/blob/master/modul2%20lat2.PNG)

#### Latihan 3
![Alt Text](https://github.com/inamyrpl28/PHP-Modul-1-2-/blob/master/modul2%20lat3.PNG)

#### Latihan 4
![Alt Text](https://github.com/inamyrpl28/PHP-Modul-1-2-/blob/master/modul2%20lat4.PNG)

#### Latihan 5
![Alt Text](https://github.com/inamyrpl28/PHP-Modul-1-2-/blob/master/modul2%20lat5.PNG)

#### Latihan 6
![Alt Text](https://github.com/inamyrpl28/PHP-Modul-1-2-/blob/master/modul2%20lat6.PNG) 

### ARRAY 
Array merupakan tipe data terstruktur yang berguna untuk menyimpan sejumlah data yang bertipe sama. Bagian yang menyusun array disebut elemen array. Masing-masing elemen array dapat diakses melalui index array. Index array dapat berupa biangan integer atau string.

#### Latihan 7

Deskripsi: Program mendeklarasikan array dengan index numerik. 
![Alt Text](https://github.com/inamyrpl28/PHP-Modul-1-2-/blob/master/modul2%20lat7.PNG)

#### Latihan 8

Deskripsi: Mendeklarasikan array dengan index string (array asosiatif) 
![Alt Text](https://github.com/inamyrpl28/PHP-Modul-1-2-/blob/master/modul2%20lat8.PNG)

#### Latihan 9

Deskripsi: menampilkan seluruh isi array dengan index numerik 
![Alt Text](https://github.com/inamyrpl28/PHP-Modul-1-2-/blob/master/modul2%20lat9.PNG)

#### Latihan 10 

Deskripsi: menampilkan seluruh isi array asosiatif 
![Alt Text](https://github.com/inamyrpl28/PHP-Modul-1-2-/blob/master/modul2%20lat10.PNG)
