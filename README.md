## Build By Azka

# Required

- php 7.4 +
- MySql
- Php Webserver, example Apache.
- Git, not required. Just for Clone

## Install

- Buat database baru, ubah .env.example menjadi .env, lalu konfigurasi .env dengan database baru.
- Install composer dengan menjalankan ```composer install``` atau update composer dengan menjalankan ```composer update```
- Jalankan ```php artisan migrate``` untuk migration databasenya
- Kemudian jalankan ```php artisan key:generate``` untuk membuat key
- Jalankan ```php artisan serve``` untuk menjalankan webserver laravel 
- Akses [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

## Kontribusi

- [noXlaw](https://github.com/noxlaw)
- [Rizky Tegar](https://github.com/rizkytegar)


## Lisensi

[MIT license](https://opensource.org/licenses/MIT).
