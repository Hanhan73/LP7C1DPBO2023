# LP7C1DPBO2023

## Janji
Saya Farhan Muzhaffar Tiras Putra NIM 2105879 mengerjakan soal Latihan Praktikum 7 dalam mata kuliah Desain dan Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

## Soal
- Pemain mengendalikan bola. Setiap kali bola bergerak, skor pemain bertambah +1.
- Skor hanya bertambah jika pemain berbelok, bukan bergerak berurutan. Detail:
  - Saat pertama kali membuka program, pemain bergerak ke arah manapun, skor +1.
  - Setelah pemain bergerak, dia harus bergerak ke arah lain agar skornya +1. Jika menekan tombol yang sama, skor tetap (+0).
  - Contoh, pemain membuka program, lalu bergerak ke kanan dan berhenti, maka skor bertambah +1. Jika pemain bergerak ke arah atas, bawah, atau kiri, maka skor bertambah +1. Namun, jika pemain bergerak ke kanan lagi, maka skor +0.
  - Bagaimana jika urutannya, kanan - atas - kiri - kanan? Kanan yang kedua tetap +1, karena pergerakan pemain sebelumnya adalah kiri, sehingga tidak dianggap berurutan.


## Penjelasan kode 
- Saya menambahkan 1 variabel baru yang bernama toWhere untuk menandakan kemana arah pemain bergerak. Saya juga menambahkan 1 fungsi di dalam game.java, yang bernama AddScore dimana berguna untuk menambahkan score sesuai dengan parameternya. Jika pemain bergerak ke salah satu arah maka variabel toWhere akan menandakan ke arah mana player tersebut bergerak jika pemain bergerak tersebut bergerak ke arah yang sama seperti yang sebelumnya maka score tidak akan bertambah.

## Dokumentasi
![Animation](https://user-images.githubusercontent.com/96176429/233841912-3046f8a0-346d-4160-a902-2cebe67e00d9.gif)



