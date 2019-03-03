# PHP_Modul6
Menciptakan dan Mengakses Cookie
![alt text](https://github.com/DemsiRakhi/PHP_Modul6/blob/master/Modul6/SSLatihanCookie1.PNG)
Memeriksa Dukungan Cookie
![alt text](https://github.com/DemsiRakhi/PHP_Modul6/blob/master/Modul6/SSLatihanCookie2.PNG)
Menghapus Cookie
![alt text](https://github.com/DemsiRakhi/PHP_Modul6/blob/master/Modul6/SSLatihanCookie3.PNG)
Menciptakan dan Mengakses Session
![alt text](https://github.com/DemsiRakhi/PHP_Modul6/blob/master/Modul6/SSLatihanSession1.PNG)
Menghapus Session
![alt text](https://github.com/DemsiRakhi/PHP_Modul6/blob/master/Modul6/SSLatihanSession2.PNG)
Auntetikasi Halaman
![alt text](https://github.com/DemsiRakhi/PHP_Modul6/blob/master/Modul6/autentikasi_cookie/index.php)
![alt text](https://github.com/DemsiRakhi/PHP_Modul6/blob/master/Modul6/autentikasi_cookie/auth.php)
Tugas Praktikum
![alt text](https://github.com/DemsiRakhi/PHP_Modul6/blob/master/Modul6/tugaspraktikum/tugaspraktikum.php)
![alt text](https://github.com/DemsiRakhi/PHP_Modul6/blob/master/Modul6/tugaspraktikum/tugaspraktikum1.php)

1. Jelaskan menggunakan bahasa sendiri perbedaan antara cookies dan session!
2. Bagaimana cara menghapus session dan cookies pada sebuah browser! 
3. Berikan contoh kode dari pembuatan dan menghapus cookies dan session!
Jawaban
1. Cookies disimpan di sisi klien dimana ketika kita membuat sebuah website login dan menutup website tersebut, ketika dibuka maka website login tersebut tidak memerlukan login kembali. Sedangkan Session disimpan di server yang bila kita menutup website login, ketika dibuka kembali memerlukan login kembali
2. Kita dapat menghapus Cookie dengan cara memberikan nama cookie yang sama tetapi tidak memiliki isi apapun didalamnya. Sedangkan Session dapat dihapus dengan memberikan code Unset() pada data
3. Cara membuat Cookie diawali dengan code $_Cookie dan dihapus dengan cara "setcookie('cookie'); setcookie();" .Sedangkan Session dapat dibuat dengan diawali dengan code $_Session untuk membuat variabel session dan dihapus dengan cara "$_Session['session'] unset($_Session['session'])"
