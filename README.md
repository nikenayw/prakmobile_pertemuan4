# Pertemuan 4 dan 5

## Pertemuan 4 (hasil)

![List Produk](assets/list_produk.png)
![Tambah Produk](assets/tambah_produk.png)
![Detail Produk](assets/detail_produk.png)
![Ubah Produk](assets/ubah_produk.png)
![Validasi](assets/validasi.png)
![Logout](assets/logout.png)

## Pertemuan 5 (hasil dan penjelasan)
1. Login : Pada halaman login ini terdapat form untuk memasukkan email dan password pengguna. Setelah pengguna memasukkan informasi yang diperlukan dan menekan tombol "Login", aplikasi akan memvalidasi input apakah email dan password sudah diisi dengan benar. Jika validasi berhasil, fungsi `_submit()` akan dijalankan untuk mengirim data login ke server menggunakan `LoginBloc.login`. Jika respons dari server menunjukkan status berhasil (kode 200), aplikasi menyimpan token dan userID di penyimpanan lokal dan mengarahkan pengguna ke halaman produk. Jika login gagal, sebuah dialog peringatan akan ditampilkan. Selain itu, pengguna juga bisa berpindah ke halaman registrasi melalui opsi yang disediakan di bawah form.
![Login](assets/Pertemuan 5/pert5_login.png)

2. Registrasi : Pada halaman registrasi, pengguna dapat memasukkan nama, email, dan password untuk mendaftarkan akun. Setelah data diisi dan pengguna menekan tombol "Registrasi", aplikasi akan memvalidasi input pengguna. Nama harus minimal 3 karakter, email harus valid, dan password minimal 6 karakter. Selain itu, pengguna juga harus mengonfirmasi password yang sesuai dengan input sebelumnya. Jika validasi berhasil, fungsi `_submit()` dipanggil untuk mengirim data registrasi ke server melalui `RegistrasiBloc.registrasi`. Jika registrasi berhasil, dialog sukses ditampilkan, mengarahkan pengguna untuk login. Jika gagal, dialog peringatan akan muncul untuk meminta pengguna mencoba lagi.
![Registrasi](assets/Pertemuan 5/pert5_regis.png)
![Form Registrasi](assets/Pertemuan 5/pert5_formregis.png)
![Form Registrasi (2)](assets/Pertemuan 5/pert5_regis.png)
![Registrasi Gagal](assets/Pertemuan 5/pert5_regisgagal.png)

3. Product
![List Produk](assets/list_produk.png)
![Tambah Produk](assets/tambah_produk.png)
![Detail Produk](assets/detail_produk.png)
![Ubah Produk](assets/ubah_produk.png)
![Validasi](assets/validasi.png)

![Logout](assets/logout.png)
