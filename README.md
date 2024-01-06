# Lab13web

Nama : Mohammad Azmi Abdussyukur

NIM  : 312210109

Kelas : TI.22.A1

## DAFTAR ISI <br>
| No | Description | Link |
|-----|------|-----|
|1|Instruksi Praktikum|[Click Here](#instruksi-praktikum)|
|2|Langkah-langkah Praktikum|[Click Here](#langkah-langkah-praktikum)|

## Instruksi Praktikum
1. Persiapkan text editor misalnya VSCode.

2. Buat folder baru dengan nama `Lab13web` pada docroot webserver (htdocs).

3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.

## Langkah-langkah Praktikum
> Untuk melakukan instalasi ***Codeigniter 4*** dapat dilakukan dengan dua cara, yaitu cara *manual* dan menggunakan *composer*. Pada praktikum ini kita menggunakan cara *manual*.
- Unduh Codeigniter dari website https://codeigniter.com/download
- Extrak file zip Codeigniter ke direktori htdocs/*(folder kalian)*.
- Ubah nama directory framework-4.x.xx menjadi ci4 *(nama file bebas)*.

1. **Aktifkan Extension di XAMPP Control Panel** Untuk mengaktifkan extension tersebut, melalui **XAMPP Control Panel**, pada bagian apache klik **config**

> Setelah itu lanjut dengan mengklik PHP (php.ini)

- Pada bagian extension, hilangkan tanda ; (titik koma) pada ekstensi yang akan diaktifkan. Kemudian save atau simpan kembali filenya dan restart Apache web server.
  
> Extension yang perlu diaktifkan :

- php-json extension untuk bekerja dengan JSON.

- php-mysqlnd native driver extension untuk MySQL.

- php-xml extension untuk bekerja dengan XML.

- php-intl extension untuk membuat aplikasi multibahasa.

- libcurl (opsional), jika ingin pakai Curl.

2. **Menjalankan CLI (Command Line Interface)**

- Setelah melakukan restart **Apache web server**, silahkan nyalakan kembali Apache dan MySQL
- Lalu kalian dapat membuka browser dengan alamat http://localhost/nama_folder_kalian/ci4/public
- Kemudian kalian dapat membuka atau menjalankan **CLI** ***(Command Line Interface)***, Codeigniter 4 menyediakan CLI untuk mempermudah proses development. Untuk mengakses CLI buka terminal/command prompt yang telah disediakan **XAMPP**.
- Selanjutnya arahkan lokasi directory sesuai dengan directory project yang kalian buat **(xampp/htdocs/nama_folder_kalian/ci4)**
- Kemudian jalankan perintah untuk memanggil CLI Codeigniter dengan script ini :
```
php spark
```

3. **Mengaktifkan Mode Debugging**
   
- Codeigniter 4 menyediakan fitur **debugging** untuk memudahkan developer untuk mengetahui pesan error apabila terjadi kesalahan dalam membuat kode program.
- Untuk memudahkan mengetahui jenis errornya, maka perlu mengaktifkan mode debugging dengan cara mengubah nilai konfigurasi pada environment variable **CI_ENVIRONMENT** menjadi **development.**

> **Hasil Output Lab12 :**

<img width="960" alt="Cuplikan layar 2024-01-06 185904" src="https://github.com/MohAzmii04/lab13web/assets/115864496/e3b81e0f-0a90-4056-91cf-587d3438df6f">


> **Hasil Output Lab13web :**

<img width="960" alt="Cuplikan layar 2024-01-06 185644" src="https://github.com/MohAzmii04/lab13web/assets/115864496/a97f1029-6fea-441b-950d-be87afed8ca4">

<img width="960" alt="Cuplikan layar 2024-01-06 185733" src="https://github.com/MohAzmii04/lab13web/assets/115864496/6560729a-e986-4318-a602-4eadc2973656">

<img width="960" alt="Cuplikan layar 2024-01-06 185644" src="https://github.com/MohAzmii04/lab13web/assets/115864496/01b7403d-ea75-4736-b495-86e88238c9a0">







