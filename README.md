Hal yang dibutuhkan sebelum menginstal laravel yaitu :
  1. Aplikasi Xammp
  2. Composer

Cara instal Composer :
  1. Download Composer yang sudah saya sediakan dan jalankan composer.exe yang telah didownload.
  2. Install seperti biasa sampai masuk proses dimana harus browse php.exe C:\php\php.exe (sesuaikan saja dengan direktori kalian) next.
  3. Finish, sebaiknya restart dulu PC/Laptopnya. Untuk memastikan composer sudah terinstall buka Command Prompt dengan menenkan Win + R dan ketik : composer -v.

Cara menginstal laravel :
  1. Sekarang buka Command Prompt dengan cara menekan Win + R
  2. Sebelum melakukan instalasi Laravel, arahkan Command Prompt atau terminal menuju direktori file server.  Lokasi file server pada XAMPP secara default berada pada
     direktori xampp/htdocs. Masukan perintah cd \xampp\htdocs pada jendela Command Prompt untuk masuk ke direktori htdocs.
  3. Selanjutnya jika sudah masuk direktori htdocs, Anda harus membuat request  untuk mengambil (serta menginstall) file Laravel yang telah disediakan dalam repositori
     Github. Gunakan perintah ini untuk melakukan request: 
   
     composer create-project --prefer-dist laravel/laravel nama_projectmu
   
     Pastikan bahwa koneksi internet dalam keadaan stabil agar tidak terjadi gangguan pada saat proses pengambilan data Laravel.
  4. Setelah proses download file Laravel selesai, nantinya akan ada folder baru pada direktori file server dengan nama sesuai nama project yang telah Anda tentukan
     sebelumnya pada folder /xampp/htdocs.
  5. Untuk memastikan bahwa Laravel sukses terinstall dan siap untuk digunakan, arahkan Command Prompt atau Terminal menuju direktori yang telah Anda buat sebelumnya.
     Lalu, masukkan perintah berikut ke dalam Command Prompt : Php artisan serve
     Jika muncul tulisan Laravel development server started pada Command Prompt atau Terminal, langkah selanjutnya adalah membuka link yang telah disediakan oleh
     Laravel. Secara default, Anda akan diarahkan menuju alamat server, yaitu 127.0.0.1:8000. Nantinya, akan muncul  tampilan homepage dengan tulisan Laravel
