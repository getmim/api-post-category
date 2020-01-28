# api-post-category

## Instalasi

Jalankan perintah di bawah di folder aplikasi:

```
mim app install api-post-category
```

## Endpoints

### `GET APIHOST/post/category`

Mengambil semua post category yang terdaftar. Selain itu juga menerima query string `q` untuk memfilter halaman dari properti `name`.

### `GET APIHOST/post/category/(id|slug)`

Mengambil properti lengkap suatu post category.

### `GET APIHOST/post/category/(id|slug)/post`

Mengambil semua post dalam suatu post category. Endpoint ini menerima pagination query ( page, rpp ).