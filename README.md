langkah pertama download Codeigniter 4 disitus web http://codeigniter.com
lalu siapkan control panel xampp, jika belum menginstal xampp bisa didownload pada link ini https://www.apachefriends.org/download.html
selanjutnya jalankan server database dan apache web server.
lalu akses http://localhost/phpmyadmin/, buatlah database dengan nama "ci4restapi_db"
masukan framework codeigniter yang sudah didownload kedalam htdoc folder dan rubah namanya menjadi "restful_api", lalu coba jalankan dengan browser dengan mengetikan "http://localhost/restful_api"
selanjutnya masuk ke framework Codeigniter4 lalu cari dengan nama file "env" lalu rename menjadi ".env"
lalu buka file code .env rubah pada bagian "CI_ENVIRONMENT=production --menjadi--> CI_ENVIRONMENT=development"
lalu buat isi database menggunakan database migration yang ada pada folder "app--> Database --> Migration"
selanjutnya tambahkan route yg ada di "app\Config\Routes.php
sekarang buatlah model untuk "mahasiswa" pada app\model" lalu buat "MahasiswaModel.php"
selanjutnya buat entity mahasiswa
selanjutnya buat controller pada folder app\Controllers dengan nama Mahasiwa.php
pada post terdapat baris kode yg menggunakan validasi, untuk itu kita perlu membuat validation pada  "app\Config\Validatin"
lalu uji coba restful_api menggunakan postman.
