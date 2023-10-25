# Tugas Praktikum { Pertemuan ke 6 } <img src=https://velog.velcdn.com/images/azd2013/post/affad795-9595-4c2b-bad0-efea305cf9ad/image.jpg width="125px" height="80px" >


|**Nama**|**NIM**|**Kelas**|**Matkul**|
|----|---|-----|------|
|Muhammad Ikhsan Fakhrudin|312210019|TI.22.A.2|Pemrograman WEB|

# JavaScript Dasar

## Langkah-langkah Praktikum

Membuka ``text editor`` , di sini saya menggunakan ***Visual Studio Code.***

![]()

## JavaScript Dasar

![](img/ss1.png)

***Pemakaian Alert Sebagai Property Window.***

![](img/ss2.png)

***Pemakaian Method dalam Objek.***

![](img/ss3.png)

***Pemakaian Prompt.*** 

![](img/ss4.png)

``Pembuatan Fungsi dan Cara Pemanggilannya.``

![](img/ss5.png)

## Dasar Pemrograman JavaScript

``Operasi Dasar Aritmatika.``

![](img/ss6.png)

``Seleksi Kondisi ( if-else).``

![](img/ss7.png)

***Penggunaan Operator Switch Untuk Seleksi Kondisi.***

![](img/ss8.png)

![](img/ss9.png)

## Pembuatan Form

***Form Input.***

![](img/ss10.png)

***Form Button.***

![](img/ss11.png)

## HTML DOM

Pilihan Menggunakan ``Checkbox`` dengan Perhitungan Otomatis.

![](img/ss12.png)

## Pertanyaan dan Tugas

1. Buatlah Script Untuk Melakukan Validasi Pada Isian Form.

## Jawab

Saya Membuat Validasi Berupa : ***Nama , No.Tlp dan E-mail.***

### Nama

Disini saya akan memberikan validasi berupa inputan hanya boleh menggunakan Huruf/Alphabet saja. Contoh : **Ikhsan Fakhrudin** ``(benar)``, **Ikhsan Fakhrudin 99** ``(salah).``

![](img/ss13.png)

***Penjelasan :***

- Membuat nama function Alphabet, dengan parameter dinamis yaitu (nilai,pesan).

- Data yang boleh dimasukkan adalah berupa "a-zA-Z".

- Jika selain data "a-zA-Z" ini dimasukkan, maka akan muncul pesan Alert "alert(pesan);"

![](img/ss16.png)

### No.Tlp

Pada bagian ini akan saya berikan validasi berupa hanya angka saja yang boleh di inputkan, contoh: ``12345 (benar)``, ``123AB (salah).``

![](img/ss14.png)

***Penjelasan :***

- var numberExp = /^[0-9]+$/; merupakan variabel numberExp yang diberi batasan validasi angka 0-9.

- Arti Match pada "if(nilai.value.match(numberExp))" adalah string.match(), mencari string menggunakan Regular Expression (Regex).

- Jika salah atau inputan tidak benar maka akan ada pesan alert "alert(pesan);"

![](img/ss17.png)

### E-mail

Pada email akan diberikan validasi masih berupa Regular Expression. Contoh : ``ihsaanef@gmail.com (benar)``, ``Donihsan98@gmail. (salah)``.

![](img/ss15.png)

***Penjelasan :***

- Membuat variabel email " var email = /^([a-zA-Z0-9_.+-])+@(([a-zA-Z0-9-])+.)+([a-zA-Z0-9]{2,4})+$/; " berupa huruf, angka dan simbol yang diperbolehkan dalam input sebuah email. Jika email salah maka akan ada pesan alert "alert(pesan);"

![](img/ss18.png)









## SELESAI <img align="center" alt="Ikhsan-Python" height="40" width="45" src="https://em-content.zobj.net/source/microsoft-teams/337/student_1f9d1-200d-1f393.png"> <img align="center" alt="Ikhsan-Python" height="40" width="45" src="https://em-content.zobj.net/thumbs/160/twitter/348/flag-indonesia_1f1ee-1f1e9.png">
