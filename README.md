# Tugas Implementasi API

Mata Kuliah Teknologi Sistem Terintegrasi

## Gambaran Umum Interface

API yang akan dibuat adalah API yang memberikan layanan
pencatatan playlist yang terintegrasi dengan data lagu yang terdapat pada spotify. API dapat menghasilkan chart tiap artis berupa jumlah lagu yang dimasukkan dari seluruh playlist.

## Penggunaan
Melakukan ubah konfigurasi database MYSQL anda pada :

```
app.config['MYSQL_DATABASE_USER'] = '{username Anda}'
app.config['MYSQL_DATABASE_PASSWORD'] = '{password Anda}'
app.config['MYSQL_DATABASE_DB'] = '{nama database Anda}'
app.config['MYSQL_DATABASE_HOST'] = 'localhost'
```

Kemudian, jalankan python app.py pada command line

Server akan berjalan pada http://127.0.0.1:5000

## Supported Request Method
- GET
- POST
- DELETE
