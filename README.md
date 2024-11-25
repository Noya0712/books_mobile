# books_mobile

A new Flutter project.

praktikum 1 hasil dari mengambil data buku dari google books
![Secreenshot yuda1](image/W11-soal2.png)

maksud dari substring mengurangi string dari value.body untuk mengambil 450 karater pertama,
sehingga teks yang di tampilkan bisa di batas hingga 450 teks saja.
sedangkan untuk catchError yaitu untuk menangani kesalahan error yang terjadi selama pemangilan fungsi dari asinkron getData,
jika getData() gagal, blok catchError akan dipanggil.
![Secreenshot yuda1](image/W11-soal3.png)

pada langkah 1, Fungsi returnOneAsync dipanggil secara asinkron, Fungsi ini menunggu selama 3 detik Future.delayed sebelum mengembalikan nilai 1.
kode await digunakan untuk menunggu hingga fungsi selesai dijalankan sebelum melanjutkan ke baris berikutnya.
pada langkah 2, returnTwoAsync dipanggil secara asinkron Sama seperti sebelumnya, fungsi ini menunggu 3 detik Future.delayed sebelum mengembalikan nilai 2.
![Secreenshot yuda1](image/W11-soal4.png)

Completer, objek yang digunakan untuk mengontrol penyelesaian completion Future secara manual. Pada baris sebelumnya,
instance Completer<int> dibuat dan dihubungkan dengan Future melalui properti ompleter.future.
calculate() memulai perhitungan menunggu 5 detik, Setelah 5 detik completer.complete(42) menyelesaikan Future dengan nilai 42.
kemudian kode yang menunggu hasil dari getNumber() akan menerima nilai 42 setelah penyelesaian.
![Secreenshot yuda1](image/W11-soal5.png)

Langkah 2 Implementasi sederhana tanpa penanganan error.
sedangkan Langkah 5 dan 6 Implementasi lebih lengkap dengan penanganan error dan pengelolaan hasil di UI.
![Secreenshot yuda1](image/W11-soal6.png)

setelah memencet tombol GO! langsunng muncul angka 6 setelah 3 detik lebih cepat dari sebelumnya
![Secreenshot yuda1](image/W11-soal7.png)

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
