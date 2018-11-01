## Latihan Elemen Form
Pada latihan elemen kali ini kita akan membahas tentang form dimana form ini akan sangat sering kita temui, ketika membuat project yang lebih besar lagi. Fungsi dari form ini sendiri banyak sekali salah satunya adalah untuk mengirimkan data atau informasi yang kita masukan ke server lalu di proses dan di simpan kedalam database.

### Berikut beberapa elemen yang akan di gunakan :
| Elemen | Fungsi     |
| :------------- | :------------- |
| `<form action="..." method="...">` ... `</form>`       | Elemen `<form> ...</form>` berfungsi untuk membuat form kosong, dan pada attribut `action="..."` kita bisa mendefinisikan alamat atau nama file yang akan gunakan untuk memproses data input dari form tersebut, lalu pada attribut `method="..."` kita dapat mendefinisikan kira - kira metode apa yang akan kita gunakan untuk mengirimkan data seperti, `GET, POST, PUT, DELETE` dll. pada table di bawah akan dijelaskan secara detail fungsi dari setiap metode tadi.    |
| `<input type="..." name="...">`       | Elemen `<input>` merupakan elemen tambahan yang wajib dibuat setelah mendefinisikan form tadi, fungsinya untuk membuat kolom input, pada attribut `type="..."` kita bisa memberikan tipe input apa yang kita akan gunakan contoh: `text, email, password` dll, dan pada attribut `name=".."` kita diharuskan untuk memberikan nama pada setiap kolom input yang kita buat agar dapat dengan mudah di kirim ke server.      |
| `<button type="..." name="..."></button>`       | Elemen ini berfungsi sebagai tombol simpan jika memiliki attribut `type="submit"` dan elemen ini sebenarnya tidak wajib memiliki attribut `name="..."` tapi untuk kepentingan validasi ini cukup baik digunakan.      |

**Note: attribut `type="..."` pada elemen `input` dan `button` cukup berbeda dan bervariasi jadi usahakan coba cari tau lebih banyak tentang `type` pada kedua elemen tersebut.**

### Berikut penjelasan singkat beberapa metode dalam form :
| Method | Penjelasan     |
| :------------- | :------------- |
| `GET`       | Metode `GET` meminta representasi sumber daya yang ditentukan. Permintaan menggunakan `GET` seharusnya hanya mengambil data.      |
| `POST`       | Metode `POST` digunakan untuk mengirimkan data ke sumber daya yang ditentukan dalam hal ini sumber daya yang kita definisikan pada attribut `action="..."` pada form, dan biasa digunakan untuk menyimpan data baru.     |
| `PUT`       | Metode `PUT` fungsinya hampir mirip seperti metode `POST` hanya saja para developer banyak menggunakanya untuk memodifikasi/merubah data yang telah di simpan sesuai dengan parameter yang di tentukan.      |
| `DELETE`       | Metode `DELETE` seperti namanya fungsinya juga sama yaitu untuk menghapus data yang telah di simpan sesuai dengan parameter tertentu yang telah didefinisikan oleh developer.      |

Sumber : [Mozilla Developer Network &mdash; Http Request Method](https://developer.mozilla.org/id/docs/Web/HTTP/Methods)

**Note: Sebenarnya masih ada beberapa method yang dapat digunakan hanya saja method diataslah yang lebih sering digunakan.**
