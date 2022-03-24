# Praktikum 3 - Pemrograman Web
### Antonius Simanjuntak - 312010004
### TI.20.B.1 - PEMPROGRAMAN WEB
### UNIVERSITAS PELITA BANGSA


## LANGKAH 1 
   --- Membuat Ondered List Awal ---
buat dokumen html dengan isi berikut :
![vc Membuat Ondered List 1](https://user-images.githubusercontent.com/101562285/159886112-d1c98c24-b29d-4e35-a9c0-81286b51c369.png)
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Lanjutan</title>
</head>
<body>
<header>
<h1>Membuat List</h1>
    
    <section id="order-list">
    <h2>Ordered List</h2>
    <ol>
    <li>Pemrograman Web</li>
    <li>Sistem Informasi</li>
    <li>Basis Data 2</li>
    </ol>
    </section>
</header>
</body>
</html>
```
lalu buka pada browser untuk melihat hasilnya :
![membuat order list](https://user-images.githubusercontent.com/101562285/159887655-94cbee5e-83e0-464b-9f12-271d57878580.png)

--- Membuat Unordered ---
buat dokumen html dengan isi berikut :
![vc membuat Unorderd List](https://user-images.githubusercontent.com/101562285/159888209-5a55b024-d86e-405a-a102-f8aeac60561d.png)
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Lanjutan</title>
</head>
<body>
<header>
<h1>Membuat List</h1>
    <section id="order-list">
    <h2>Ordered List</h2>
    <ol>
    <li>Pemrograman Web</li>
    <li>Sistem Informasi</li>
    <li>Basis Data 2</li>
    </ol>
    </section>
</section>
<section id="unorder-list">
<h2>Unordered List</h2>
<ul type="square">
<li>Jaringan Komputer</li>
<li>Struktur Data</li>
<li>Algoritma &amp; Pemrograman</li>
</ul>
</section>
</header>
</body>
</html>
```
lalu buka pada browser untuk melihat hasilnya :
![membuat Unorderd List](https://user-images.githubusercontent.com/101562285/159888200-68327e7b-2b57-4523-8457-2a5078c42d2d.png)

## LANGKAH 2
   --- Membuat Description List ---
buat dokumen html dengan isi berikut :
![vc deskripsi lis new](https://user-images.githubusercontent.com/101562285/159889960-bd2a3d7e-402a-4b75-a1ec-3808107793ef.png)
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Lanjutan</title>
</head>
<body>
<header>
    <section id="unorder-list">
        <h2>Description List</h2>
        <dl>
        <dt>Fakultas Teknik</dt>
        <dd>Teknik Industri</dd>
        <dd>Teknik Informatika</dd>
        <dd>Teknik Lingkungan</dd>
        <dt>Fakultas Ekonomi dan Bisnis</dt>
        <dd>Akuntansi</dd>
        <dd>Manajemen</dd>
        <dd>Bisnis Digital</dd>
        </dl>
        </section>
</header>
</body>
</html>
```
lalu buka pada browser untuk melihat hasilnya :
![deskripsi lis new](https://user-images.githubusercontent.com/101562285/159889980-287381cb-280d-4a39-81fc-2167ffc3c0bb.png)

## LANGKAH 3
   --- Membuat Table ---
buat dokumen html dengan isi berikut :
![vc membuat tabel](https://user-images.githubusercontent.com/101562285/159891924-d311353c-f715-4a27-8add-de58d98452c2.png)
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Lanjutan</title>
</head>
<body>
<header>
<h1>Membuat Table</h1>
    <table border="1" cellpadding="4" cellspacing="0">
        <thead>
            <tr>
                <th>No.</th>
                <th>Fakultas</th>
                <th>Program Studi</th>
            </tr>
    </thead>
    <tbody>
            <tr>
                <td>1.</td>
                <td>Teknik</td>
                <td>Teknik Informatika</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>Teknik</td>
                <td>Teknik Industri</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>Teknik</td>
                <td>Teknik Lingkungan</td>
            </tr>
    </tbody>
    </table>
</header>
</body>
</html>
```
lalu buka pada browser untuk melihat hasilnya :
![membuat tabel](https://user-images.githubusercontent.com/101562285/159891946-b6bb0e70-2af7-4f0a-9f0a-451ec58e8a60.png)

## LANGKAH 4
   --- Menggabungkan Sell Data ---
buat dokumen html dengan isi berikut :
![vc menggabungkan cell data](https://user-images.githubusercontent.com/101562285/159892708-4de3f1e3-e298-4eef-b552-e7b6c48c3c3c.png)
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Lanjutan</title>
</head>
<body>
<header>
<h1>Membuat Table</h1>
    <table border="1" cellpadding="6" cellspacing="0">
    <thead>
    <tr>
    <th>No.</th>
    <th>Fakultas</th>
    <th>Program Studi</th>
    </tr>
    </thead>
    <tbody>
    <tr>
    <td>1.</td>
    <td rowspan="3">Teknik</td>
    <td>Teknik Informatika</td>
    </tr>
    <tr>
    <td>2.</td>
    <td>Teknik Industri</td>
    </tr>
    <tr>
    <td>3.</td>
    <td>Teknik Lingkungan</td>
    </tr>
    </tbody>
    </table>
</header>
</body>
</html>
```
lalu buka pada browser untuk melihat hasilnya :
![menggabungkan cell data](https://user-images.githubusercontent.com/101562285/159892696-e6fb25e5-47b3-483a-9cee-0db05baa26f3.png)

## LANGKAH 5
   --- Membuat Form ---
buat dokumen html dengan isi berikut :
![vc membuat tabel new](https://user-images.githubusercontent.com/101562285/159893945-587a6eb9-4112-4e5c-9761-ea17444748f3.png)
```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HTML Lanjutan</title>
</head>
<body>
<header>
<h1>Membuat Form</h1>
</header>
<form action="proses.php" method="post">
    <fieldset>
    <legend>Data Pelanggan</legend>
    <p>
    <label for="nama">Nama</label>
    <input type="text" id="nama" name="nama">
    </p>
    <p>
    <label for="alamat">Alamat</label>
    <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
    </p>
    <p>
    <label>Jenis Kelamin</label>
    <input id="jk_l" type="radio" name="kelamin" value="L" /><label
    for="jk_l">Laki-laki</label>
    <input id="jk_p" type="radio" name="kelamin" value="P" /><label
    for="jk_p">Perempuan</label>
</p>

</form>
</body>
</html>
```
lalu buka pada browser untuk melihat hasilnya :
![Membuat Form](https://user-images.githubusercontent.com/101562285/159894015-660ab790-857b-478d-838f-2132b7856b56.png)

## LANGKAH 6
   --- Menambahkan  Style Pada Form ---
buat dokumen html dengan isi berikut :
![vc Membuat Form Akhir](https://user-images.githubusercontent.com/101562285/159894570-93c89357-ee7e-496f-99d0-5535304ce1c2.png)
```
<style>
form p > label {
display: inline-block;
width: 100px;
}
form input[type="text"], form textarea {
border: 1px solid #197a43;
}
form input[type="submit"] {
border: 1px solid #197a43;
background-color: #197a43;
color: #ffffff;
font-weight: bold;
padding: 5px 15px;
}
</style>
```
lalu buka pada browser untuk melihat hasilnya :
![Membuat Form Akhir](https://user-images.githubusercontent.com/101562285/159894550-fc3ecdb7-96ee-46ac-9414-b42897df7765.png)

# Pertanyaan dan Tugas
### 1.Buatlah Form yang Menampilkan Dropdown menu dan Listbox dengan Multiple Selection
--- Menampilkan Dropdown menu dan Listbox dengan Multiple Selection ---
buat dokumen html dengan isi berikut :
![vc pertanyaan 1](https://user-images.githubusercontent.com/101562285/159898352-83c2f9d9-4299-4e7d-8356-e9b38114daf5.png)
```
<!doctype html>
    <html>
        <head>
            <title>Cara Membuat Multiple Select Di Satu Tag Select</title>
            <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
            <link href="https://cdnjs.cloudflare.com/ajax/libs/select2/4.0.6-rc.0/css/select2.min.css" rel="stylesheet" />
        </head>
        <body style="background: lightblue">
            <div style="width: 500px; padding: 15px; margin:200px auto;">
                <div class="form-group">
                   <h1>Membuat Multiple Select</h1>
                    <h2>Paket Belajar</h2>
                    <label>Antonius_School</label>
                    <select id="paket" name="paket[]" class="form-control" multiple="multiple">

                        <option value=""></option>

                        <option value="Web Master">Web Master</option>

                        <option value="Web Programming">Web Programming</option>

                        <option value="Web Design">Web Design</option>

                        <option value="Digital Marketing">Digital Marketing</option>

                        <option value="Coding For Kids">Coding For Kids</option>

                        <option value="Grafic Desain">Grafic Desain</option>

                        <option value="Motion Grafic">Motion Grafic</option>
                    
    <script src="https://code.jquery.com/jquery-3.3.1.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/select2/4.0.6-rc.0/js/select2.min.js"></script>
    <script>
        $(document).ready(function () {
            $("#paket").select2({
                placeholder: "Silahkan Pilih"
            });
        });
    </script>
                    </select>
                </div>
            </div>
    </body>
    </html>
```
lalu buka pada browser untuk melihat hasilnya :
![pertanyaan 1](https://user-images.githubusercontent.com/101562285/159898340-7ab044c0-3964-4da5-9425-16d71ba55108.png)
