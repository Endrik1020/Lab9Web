# Lab9Web
# Praktikum 9
# Pemograman WEB

~~~
Nama  : Endrik
NIM   : 311910088
Kelas : TI.19.C1
~~~
# Langkah-langkah Praktikum

# Buat folder baru dengan nama lab9_php_modular pada docroot webserver (htdocs)

![0](https://user-images.githubusercontent.com/81820421/122055331-b7019700-ce12-11eb-91e1-4b53bb346f95.JPG)

Buat file baru dengan nama header.php
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Contoh Modularisasi</title>
    <link href="style.css" rel="stylesheet" type="text/stylesheet" media="screen" />
</head>
<body>
    <div class="container">
        <header>
            <h1>Modularisasi Menggunakan Require</h1>
        </header>
    <nav>
        <a href="home.php">Home</a>
        <a href="about.php">Tentang</a>
        <a href="kontak.php">Kontak</a>
    </nav>
~~~
![1](https://user-images.githubusercontent.com/81820421/122054767-2fb42380-ce12-11eb-8651-8ad54d1f2830.JPG)

# Buat file baru dengan nama footer.php
~~~
<footer>
        <p>&copy; 2021, Informatika, Universitas Pelita Bangsa</p>
    </footer>
</div>
</body>
</html>
~~~
![2](https://user-images.githubusercontent.com/81820421/122055795-31cab200-ce13-11eb-999e-104f72a212bc.JPG)

# Buat file baru dengan nama home.php
~~~
<?php require('header.php'); ?>
<div class="content">
    <h2>Ini Halaman Home</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>
<?php require('footer.php'); ?>
~~~
![3](https://user-images.githubusercontent.com/81820421/122056120-7f471f00-ce13-11eb-9616-df09a2bca615.JPG)

# Buat file baru dengan nama about.php
~~~
<?php require('header.php'); ?>
<div class="content">
    <h2>Ini Halaman About</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>
<?php require('footer.php'); ?>
~~~
![4](https://user-images.githubusercontent.com/81820421/122056499-d64cf400-ce13-11eb-8edd-b4283539875d.JPG)

# Pertanyaan dan Tugas
Implementasikan konsep modularisasi pada kode program praktikum 8 tentang database, sehingga setiap halamannya memiliki template tampilan yang sama.

# Membuat file baru dengan nama header.php
~~~
        <header>
        <nav>
            <a href="index.php">Home</a>
            <a href="about.php">Tentang</a>
            <a href="#">Kontak</a>
        </nav>
        </header>
       
~~~
![5](https://user-images.githubusercontent.com/81820421/122057255-9e927c00-ce14-11eb-98ef-ec88bfe7fb86.JPG)

# Membuat file baru dengan nama footer.php
    <footer>
        <p>&copy; 2021, Informatika, Universitas Pelita Bangsa</p>
    </footer>
</div>
</body>
</html>

![6](https://user-images.githubusercontent.com/81820421/122058110-7d7e5b00-ce15-11eb-8f7f-5a552d677366.JPG)

# Menambahkan require pada file index.php

## Menambahkan require header pada file index.php
![7](https://user-images.githubusercontent.com/81820421/122058816-38a6f400-ce16-11eb-9234-7bcd28422c2e.JPG)
## Menambahkan require footer pada file index.php
![8](https://user-images.githubusercontent.com/81820421/122059221-9afff480-ce16-11eb-8810-8ba5488792c6.JPG)
## Menambahkan require footer pada file index.php



