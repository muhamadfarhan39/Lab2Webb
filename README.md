# Lab2Webb
###### Nama :  Muhamad Farhan
###### NIM : 312010400
###### Kelas : TI.A.2

## TugasCSSWebProgramming



Instruksi Praktikum
1. Persiapkan text editor misalnya VSCode.
2. Buat file baru dengan nama lab2_css_dasar.html
3. Buat struktur dasar dari dokumen HTML.
4. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.
5. Lakukan validasi dokumen css dengan mengakses https://jigsaw.w3.org/css-validator/

Langkah-langkah Praktikum
1. Membuat dokumen HTML
Buatlah dokumen HTML seperti berikut


![image](https://user-images.githubusercontent.com/101417081/158675109-df02cfb8-5586-4460-989b-592d0dc4d843.png)

saya

Selanjutnya buka pada brwoser untuk melihat hasilnya.

![image](https://user-images.githubusercontent.com/101417081/158675259-3e706e30-cc41-41be-8b7d-8f519920a166.png)

saya
2. Mendeklarasikan CSS Internal
Kemudian tambahkan deklarasi CSS internal seperti berikut pada bagian head dokumen.


![image](https://user-images.githubusercontent.com/101417081/158675383-3b82c07d-efa7-4c8b-b53a-ec2ec3488f9e.png)

saya
Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat
hasilnya.

Modul Praktikum Pemrograman Web

![image](https://user-images.githubusercontent.com/101417081/158675547-ce09d0fa-2e46-4eac-8ae3-54615c3ce032.png)

saya

3. Menambahkan Inline CSS
Kemudian tambahkan deklarasi inline CSS pada tag <p> seperti berikut.

![image](https://user-images.githubusercontent.com/101417081/158675634-17daaeb2-29b5-464b-bbe8-e76ecfa1d172.png)

saya
Simpan kembali dan refresh kembali browser untuk melihat perubahannya.

![image](https://user-images.githubusercontent.com/101417081/158675834-15b14852-846b-4ba3-bfc8-ea75c622ab83.png)

saya

4. Membuat CSS Eksternal
Buatlah file baru dengan nama style_eksternal.css kemudian buatlah deklarasi CSS seperti berikut.

![image](https://user-images.githubusercontent.com/101417081/158676199-ab0ea0c8-2f5b-412d-b8ae-1f51b632138d.png)

saya

Kemudian tambahkan tag <link> untuk merujuk file css yang sudah dibuat pada bagian <head>

![image](https://user-images.githubusercontent.com/101417081/158676298-432003c9-5216-47a8-8589-8ab4332b5362.png)

saya
Selanjutnya refresh kembali browser untuk melihat perubahannya.
  
![ss6](https://user-images.githubusercontent.com/101417081/158676474-86719ce3-bdc5-4731-9567-aaf7b21d0505.png)

saya

5. Menambahkan CSS Selector
Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file
style_eksternal.css, tambahkan kode berikut.
![image](https://user-images.githubusercontent.com/101417081/158676554-29ecfb5a-6bb0-47b4-b78a-b4f4e9497838.png)

saya
Kemudian simpan kembali dan refresh browser untuk melihat perubahannya.

![image](https://user-images.githubusercontent.com/101417081/158676771-5b5e9135-9e5c-40a3-ae88-65112cabd6f7.png)

saya


Pertanyaan dan Tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada
elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan
penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut
terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya! ( <p id="paragraf-1" class="text-paragraf">

Jawaban

1.Pengantian pada font-size, font-color, font family, size dan lain lain terdapat pada gambar dibawah ini.
![image](https://user-images.githubusercontent.com/101417081/158676893-2d7658b5-143d-4010-bddf-7abf7e374493.png)
2. ###### Pemilih ID
dideklarasikan dengan menambahkan tanda # sebelum nama id yang akan digunakan.
Kemudian pada tag HTML ditambahkan atribut id dengan value nama id tanpa menggunakan #.
Satu elemen HTML hanya dapat diberikan satu id.
Penggunaan #intro dengan menggunakan id
contoh pada id HTML id="intro"
dan pemakaian pada css #intro yang terkadang mempunyai inherent/anak pada css. 

###### Elemen Selector
dideklarasikan berdasarkan tag HTML.
Contoh : h1, nav, title, paragraph.

3.deklarasi utama yang akan ditampilkan ialah : inline, internal, dan eksternal.
dan untuk internal dan eksternal yang akan ditampilkan itu tergantung pada dimana yang terakhir diletakan pada html, jika penggunaan internal di atas eksternal maka link eksternal yang akan ditampilkan karena html akan memproses internal lalu eksternal yang mengakibatkan yang paling akhir yang akan di tampilkan/proses.
  
  
![image](https://user-images.githubusercontent.com/101417081/158677016-78d43503-e2a2-4e14-be84-ceb5df493ff6.png)

saya
4.“id” bersifat unik dalam satu halaman dan hanya dapat diterapkan ke paling banyak satu elemen, sedangkan pemilih “kelas” dapat diterapkan ke beberapa elemen.
penggunaan id lebih di utamakan daripada class, karena id bersifat unik.
contoh : <id="class" class="myclass">
pada css : 
#main{
color : red;}

.myclass{
color : blue;}

maka yang akan ditampilkan adalah red yaitu id.
