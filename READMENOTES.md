# Cara kolaborasi github
Cara kolaborasi github untuk berkolaborasi mengelola pekerjaan


## Untuk non Kontributor/Anggota

### 1. Copy link untuk clone

<img src="images/request-pull1.png">

lalu jalankan perintah ini:

**git clone < url clone>**

```bash
$ git clone https://github.com/kelas-industri-kelompok-1/PresensiQRCode.git
```

<img src="images/request-pull2.png">

 selanjutnya berpindah ke folder / directory yang telah di clone, dengan menggunakan perintah:

```bash
$ cd PresensiQRCode
```
<img src="images/request-pull3.png">

setelah di dalam directory **PresensiQRCode** (sesuaikan dengan directory yang ada)

install vendor terlebih dahulu, dengan mejalankan perintah seperti berikut:

```bash
$ composer install
```
<img src="images/request-pull4.png">

jika berhasil maka akan ada file baru dengan nama "**vendor**"

<img src="images/request-pull5.png">

berikutnya copy file env dengan menggunakan perintah:

```bash
$ cp .env.example .env
```
<img src="images/request-pull6.png">

kemudian akan ada file baru dengan nama ".env" dan ".env.example"
<img src="images/request-pull7.png">

berikutnya generate app key, dengan menjalankan perintah sebagai berikut:

```bash
$ php artisan key:generate
```
jika berhasil maka akan tampil seperti gambar berikut:
<img src="images/request-pull8.png">
> jika tampil seperti gambar, maka patch anda sudah sama dengan semua anggota lain

setelah itu aktifkan server laravelnya dengan menggunakan perintah:
```bash
$ php artisan serve
$ php artisan serv
$ php artisan ser
```
> bisa dipersingkat (pilih salah satu)
<img src="images/request-pull9.png">
>jika sudah tampil seperti gambar, server laravel anda sudah bisa digunakan

kemudian, copy "**http://127.0.0.1:8000**" ke browser kalian untuk menjalankan tampilan antarmukanya
<img src="images/request-pull10.png">
>tampilan default antarmuka laravel

<img src="images/request-pull11.png">
