# OnlineShop 


# Mahasiswa
```bash
    Nama : Renaldy Luthfiana Hakim
    Nim  : 2141042
```

## Screenshots

![preview img](/preview.png)
![preview img](/preview2.png)



## Ubah Setting Xampp ( jika pakai Xampp )

```bash
-  Masuk File PHP INI 
-  hapus ( ; ) dalam ExtensionGD
```

## Donwload

Clone Projek

```bash
  git clone https://github.com/renaldy23y/2141042_UAS-PEMROGRAMAN-WEB.git nama_projek
```

Masuk ke folder dengan perintah

```bash
  cd nama_projek
```

-   Copy .env.example menjadi .env kemudia edit database dan api key nya

```bash
    composer install
```

```bash
    php artisan key:generate
```

```bash
    php artisan artisan migrate:fresh --seed
```

```bash
    php artisan storage:link
```

```bash
    npm run dev 
```

```bash
    php artisan serve
```


#### Login Halaman Admin Utama
-   http://127.0.0.1:8000/admin/dashboard

#### Login Halaman Utama
-   http://127.0.0.1:8000

#### Login

-   email = admin@admin.com
-   password = 123


