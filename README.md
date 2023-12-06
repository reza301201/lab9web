# Lab9web

Nama : Reza Kurniawan
NIM  : 312210436

Kelas : TI.22.A1

## DAFTAR ISI <br>
| No | Description | Link |
|-----|------|-----|
|1|Instruksi Praktikum|[Click Here](#instruksi-praktikum)|
|2|Langkah-langkah Praktikum|[Click Here](#langkah-langkah-praktikum)|
|3|Pertanyaan dan Tugas|[Click Here](#pertanyaan-dan-tugas)|

## Instruksi Praktikum
1. Persiapkan text editor misalnya VSCode

2. Buat folder baru dengan nama `lab9_php_modular` pada docroot webserver (htdocs)

3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya

## Langkah-langkah Praktikum
- Jalankan Apache dan MySQL server dari menu XAMPP Control
- Kemudian buat folder baru dengan nama lab9_php_modular pada docroot webserver (c:\xampp\htdocs). Kemudian buka melalui browser dengan mengakses URL: http://localhost/lab9_php_modular/.

![1](https://github.com/syifaaurellia/Lab9web/assets/115867244/ab5f4256-e26d-47be-974b-67e51867e1aa)

1. Buat file dengan nama `header.php`
```
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
```

2. Buat file dengan nama `footer.php`
```
        <footer>
            <p>&copy; 2021, Informatika, Universitas Pelita Bangsa</p>
        </footer>
    </div>
</body>
</html>
```

3. Buat file dengan nama `home.php`
```
<?php require('header.php'); ?>

<div class="content">
    <h2>Ini Halaman Home</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>

<?php require('footer.php'); ?>
```

4. Buat file dengan nama `about.php`
```
<?php require('header.php'); ?>

<div class="content">
    <h2>Ini Halaman About</h2>
    <p>Ini adalah bagian content dari halaman.</p>
</div>

<?php require('footer.php'); ?>
```

- Output halaman `Home` :
![Screenshot (69)](https://github.com/reza301201/lab9web/assets/116234001/7e0d35f3-e453-475d-8c2d-4aff6401ee68)


- Output halaman `About` :
![Screenshot (70)](https://github.com/reza301201/lab9web/assets/116234001/39877377-a054-4557-9715-84db0c3ff402)



## Pertanyaan dan Tugas
> Implementasikan konsep modularisasi pada kode program Praktikum 8 tentang database, sehingga setiap halamannya memiliki template tampilan yang sama.

1. Buat folder baru dengan nama `lab9_php_praktikum`
![4](https://github.com/syifaaurellia/Lab9web/assets/115867244/f79373d0-08c9-4b93-9d46-7e7d11ac8e0a)

- Setelah itu buat beberapa file sama seperti file-file yang ada pada praktikum 8, untuk script lebih lengkapnya kalian dapat langsung lihat pada folder [lab9_php_praktikum](https://github.com/syifaaurellia/Lab9web/tree/main/lab9_php_praktikum).

2. Hasil Output `koneksi.php` :
![Screenshot (71)](https://github.com/reza301201/lab9web/assets/116234001/a302ca54-35cf-412a-9194-ad480882ab19)

3. Hasil Output `home.php` :
![Screenshot (72)](https://github.com/reza301201/lab9web/assets/116234001/cd1e9aa4-c258-47ea-9908-529b2543ab39)



5. Hasil Output `tambah.php` :
![Screenshot (73)](https://github.com/reza301201/lab9web/assets/116234001/d0edd7ee-40bb-402e-b00f-5d70cf9bc156)


![Screenshot (74)](https://github.com/reza301201/lab9web/assets/116234001/ae39939f-923d-4ab7-bf6a-66f2332e5201)

![Screenshot (76)](https://github.com/reza301201/lab9web/assets/116234001/026b8dd8-a3ad-4e05-bb2f-c48636cc6468)



5. Hasil Output `ubah.php` :
![Screenshot (77)](https://github.com/reza301201/lab9web/assets/116234001/057ec22d-1fc8-43b7-9732-f30d5fed687a)


![Screenshot (78)](https://github.com/reza301201/lab9web/assets/116234001/acf71617-62b8-4cf3-aab1-b76306b2de29)



6. Hasil Output `hapus.php` :
![Screenshot (79)](https://github.com/reza301201/lab9web/assets/116234001/4e9cb55c-0eb9-41b0-9cfe-4b7fa8f7ec9b)



## Finish, Terima Kasih
