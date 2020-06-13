Terdapat banyak sekali varian mesin *database relational* yang saat ini ada untuk menyimpan item data.<br/>
Mesin *open source* yang sangat populer saat ini digunakan untuk menyimpan data beberapa contohnya adalah *PostgreSQL* dan *MySQL*.
<p align="center">
<img src="/Images/postgre-img.jpg" width="250" />
<img src="/Images/mysql-img.jpg" width="250" />
</p> 

## Instalasi Mesin Database di Mac OS
Untuk mempermudah instalasi mesin Database pada Mac, instalasi dimulai dengan menginstall Homebrew. <br/>
[Homebrew](https://brew.sh/) merupakan sebuah *package manager* di MacOS. Cara menginstall nya : 
1. Buka Terminal 
2. Ketik `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
` pada terminal dan jalankan.
3. Ketik `brew doctor` dan jalankan untuk memeriksa apakah terdapat kesalahan instalasi 
4. Ketik `brew update` dan jalankan untuk mengupdate Hombrew ke versi paling baru. <br/>

### PostgreSQL <br/>

1. ketik `brew install postgresql` pada terminal dan jalankan untuk memulai instalasi PostgreSQL.

Untuk menyalakan PostgreSQL, ketik dan jalankan pada terminal: <br/>
`brew services start postgresql` <br/>

### MySQL <br/>

1. ketik `brew install mysql` pada terminal dan jalankan.
2. ketik `mysqladmin -u root password '<yourpassword>'` untuk setup password user root, <br/>
ubah `<yourpassword>` sesuai dengan password yang kamu inginkan.

Untuk menyalakan MySQL, ketik dan jalankan pada terminal: <br/>
`brew services start mysql` <br/>


## Instalasi Mesin Database di Windows

* Mac <br/>


* Windows <br/>



