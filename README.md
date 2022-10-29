# Repositori Aplikasi Web Profil Karang Taruna
Repositori untuk proses integrasi kode aplikasi web profil karang taruna

# File Konfigurasi
Untuk setting database di file admin/config.php

Ubah dan sesuaikanlah pengaturan berikut:

//Host Name

$dbhost = 'localhost';

//Database Name

$dbname = 'karang_taruna';

//Database Username

$dbuser = 'root';

//Database Password

$dbpass = '';

//Defining base url

define("BASE_URL", "http://localhost/karang-taruna/");

# Deploy an entire directory
The following .cpanel.yml file copies the images directory and all of its contents to the example account’s public_html directory:

---
deployment:
  tasks:
    - export DEPLOYPATH=/home/example/public_html/
    - /bin/cp -R images $DEPLOYPATH


Test tambah isi dari programmer 1