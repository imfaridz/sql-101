Terdapat banyak sekali varian mesin *database relational* yang saat ini ada untuk menyimpan item data.<br/>
Mesin *open source* yang sangat populer saat ini digunakan untuk menyimpan data beberapa contohnya adalah *PostgreSQL* dan *MySQL*.
<p align="center">
<img src="../Images/postgre-img.jpg" width="250" />
<img src="../Images/mysql-img.jpg" width="250" />
</p> 

## Instalasi Mesin Database di Mac OS
### Pre-Requisite
Untuk mempermudah instalasi mesin Database pada Mac, instalasi dimulai dengan menginstall Homebrew. <br/>
[Homebrew](https://brew.sh/) merupakan sebuah *package manager* di MacOS. Cara menginstall nya : 
1. Buka Terminal 
2. Ketik `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
` pada terminal dan jalankan.
3. Ketik `brew doctor` dan jalankan untuk memeriksa apakah terdapat kesalahan instalasi 
4. Ketik `brew update` dan jalankan untuk mengupdate Hombrew ke versi paling baru. <br/>

### PostgreSQL <br/>

1. Ketik `brew install postgres` pada terminal dan jalankan untuk memulai instalasi PostgreSQL.
2. Ketik `bre services start postgres` untuk menyalakan service PostgreSQL.
3. Untuk membuat database user sebelum masuk ke dalam postgres command line dengan cara menjalankan command `psql -d template1` pada terminal.
4. Lalu ketik `createdb <nama user>`
5. Untuk cek semua instalasi sudah ter-install dengan baik, ketik `psql` pada terminal dan idealnya akan menghasilkan output seperti berikut: <br/>
<p>
<img src="../Images/postgre-success.png" width="200" />
</p> 
7. Ketik `\q` untuk keluar dari postgres dan `pg_stop` untuk mematikan server postgres.

### MySQL <br/>

1. Ketik `brew install mysql` pada terminal dan jalankan.
2. Setelah instalasi selesai, terdapat 2 cara untuk menjalankan service MySQL : <br/>
    1. `brew services start mysql`
    2. `mysql.server start` 
3. Untuk cek semua instalasi sudah ter-install dengan baik, ketik dan jalankan `mysql -uroot` pada terminal dan idealnya akan menghasilkan output seperti berikut: <br/>
<p>
<img src="../Images/mysql-success.png" width="200" />
</p> 
4. Ketik `\q` untuk keluar dari MySQL command line. 


[Lanjut ke Chapter 2.0 - SQL Editor](chapter2.0-SQL_IDE.md) 

