Agar SETIADI dapat dipasang, pastikan web server (peladen web , misalnya Apache web server ), MySQL (aplikasi pangkalan data), dan PHP (bahasa pemrograman) telah terpasang pada perangkat keras peladen dan berjalan dengan baik. Akan lebih membantu apabila aplikasi phpMyAdmin atau Adminer juga dipasang untuk membantu dalam penyetelan pangkalan data melalui antarmuka web . Jika SETIADI digunakan di internet (publik), disarankan untuk meningkatkan keamanan dengan menambahkan firewall di sisi TCP/IP ( layer 3 dan 4 dari OSI layer ), di sisi aplikasi (contoh modsecurity) dan di sisi pangkalan data (contoh greensql). Setelah sistem yang akan digunakan sudah siap, letakkan kode sumber SETIADI pada direktori root web yang anda gunakan.

# Instal SETIADI pada Sistem Operasi Windows menggunakan XAMPP
## 1. Ekstrak Kode Sumber SETIADI (Source Code)
Bagi pengguna sistem operasi ini, penggunaan Apache, PHP, MySQL sudah tersedia dalam bentuk paket. Banyak paket yang bisa dimanfaatkan. Salah satu yang terkenal
adalah XAMPP oleh Apache Friends . Aplikasi ini dapat diunduh di http://apachefriends.org . Setelah memasang XAMPP, untuk bisa memulai layanan peladen web dan pangkalan
data dengan memilih XAMPP control panel dari menu aplikasi. 
Pada control panel XAMPP silahkan aktifkan Apache dan MySQL

![1 1](https://user-images.githubusercontent.com/37967729/107620886-ffa01c80-6c87-11eb-88f6-a4544ec23872.PNG)


Jika Anda menggunakan XAMPP, maka direktori root web berada di xampp/htdocs. Untuk memulai Instalasi SETIADI menggunakan kode sumber, salin berkas kode
sumber SLiMS di folder htdocs. Berkas kode dalam bentuk Zip/Rar bisa di ekstrak terlebih dahulu didalam folder htdocs tersebut menggunakan Winrar atau Winzip.

## 2. Import file SQL SETIADI ke phpMyAdmin
1. Pada browser silahkan masuk ke phpMyadmin dengan memasukan url http://localhost/phpmyadmin/
2. Buat database baru
3. Setelah database berhasil dibuat, langkah selanjutnya silahkan import database sql SETIADI yang terdapat pada directory 
```bash
\xampp\htdocs\setiadi3_walanae-master\files\backup
```


