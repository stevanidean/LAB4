# PEMROGRAMAN WEB 2 - PRAKTIKUM 4
# BIODATA
NAMA : STEVANI DEAN SAFIRA 
NIM : 312110463
KELAS : TI.21.A.2

# LANGKAH LANGKAH PENGERJAANNYA
1. pertama aktifkan mod_rewrite untuk mengubah url dari query string menjadi SEO friendly

![aktivasi](https://user-images.githubusercontent.com/92729505/232746555-82c767ff-88ac-42ea-bd25-556741abc6c6.PNG)

lalu buat file baru dengan nama .htaccess dan masukan kode berikut

 RewriteEngine On
  RewriteBase /LabWeb/Lab4Web
  RewriteCond %{REQUEST_FILENAME} !-f
  RewriteCond %{REQUEST_FILENAME} !-d
  RewriteRule ^(.*)$ indexx.php?mod=$1 [L]
</IfModule>

2. membuat file baru dengan nama error.php lalu masukan kode ini

<!DOCTYPE html>
<html>
  <head>
    <title>CRUD Sederhana</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        background-color: #f2f2f2;
        display: flex;
        align-items: center;
        justify-content: center;
        height: 100vh;
        flex-direction: column;
      }
      h1 {
        font-size: 36px;
        color: #333;
        margin-top: 50px;
      }
      p {
        font-size: 24px;
        color: #666;
      }
    </style>
  </head>
  <body>
    <h1>Error 404 - Page Not Found</h1>
    <p>Maaf, halaman yang Anda minta tidak dapat ditemukan.</p>
  </body>
</html>
 
 yang nantinya akan seperti ini
 ![error](https://user-images.githubusercontent.com/92729505/232747546-611b5fae-3c05-48e7-912e-1bd7b841420f.PNG)
 
 3. karena kita akan mengimplementasikannya dengan ttugas praktikum kemarin, jadi tinggal tambahkan saja file nya menjadi satu pada folder Lab4Web
 
 ini dia hasilnya 
 ![vailed](https://user-images.githubusercontent.com/92729505/232748161-d34fee8c-2788-4145-8492-aacf6776c633.PNG)

iya pak, yang saya buat tidak berhasil...
 
 

