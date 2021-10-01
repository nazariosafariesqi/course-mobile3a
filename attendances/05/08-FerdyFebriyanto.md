# KONSEP DASAR FLUTTER

<hr>

* Nama      : Ferdy Febriyanto
* NIM       : 1941720007
* Kelas     : TI3A
* Pertemuan : 5 (Lima)

---

## Rangkuman
- Pada pertemuan kelima mata kuliah pemograman mobile, materi yang dibawakan adalah tentang [Flutter](https://flutter.dev/docs/get-started/install/macos).

> Flutter adalah sebuah alat yang membuat kita bia membangun aplikasi antar platform (iOs, Android) secara native atau native cross-platform dengan menggunakan satu bahasa pemrograman dan satu basis kode. Native cross-platform yang dimaskud bukan sebuah aplikasi web yang dibungkus oleh native app tetapi kita benar benar membangun dua aplikasi berbeda untuk iOs dan Android yang kemudian bisa kita distribusikan ke Apple App Store maupun Google Play Store.

- Adapun untuk menggunakan tools ini kita perlu [menginstall SDK Flutter](https://flutter.dev/docs/get-started/install) sesuai Operating System yang digunakan.
- Flutter ini dapat digunakan di berbagai IDE, dikarenakan saya memiliki IDE visual studio code. Maka saya perlu [setup editor codenya](https://flutter.dev/docs/get-started/editor?tab=vscode) 
- Untuk membuat aplikasi flutter pertama kali kita ikuti [dokumentasi Flutter](https://flutter.dev/docs/get-started/codelab) ini.
- Kita disini belajar tentang User interface, widget, layouts dan masih banyak lagi.

> MaterialApp adalah sebuah parent dimana yang diapitnya akan menerapkan style material design. Selain itu, dia juga memiliki control untuk mengatur route, theme, supported locales, dan lain sebagainya. Akan tetapi pada seri kali ini kita hanya akan membahas tentang theme-nya saja, adapun fungsi lainnya akan dirangkaikan dengan materi lainnya.
> Scaffold memiliki peran untuk mengatur struktur visual layout dengan mengimplementasikan material design, dimana dia juga memiliki kemampuan untuk membuat app bars, drawers, snack bars, bottom sheets dan lain sebagainya.
> appBar adalah salah satu properti yang dimiliki oleh Scaffold widget untuk membuat sebuah bar pada aplikasi, salah satu contohnya adalah menampilkan teks Belajar MaterialApp Scaffold
> Column bisa menampung lebih dari 1 widget, sehingga kita bisa memasukkan widget lainnya di dalam children-nya sesuka hati. Seperti yang disinggung di awal bahwa column akan menyusun widget yang ada di dalamnya dari atas ke bawah.
> Penerapan Row sama saja dengan Column, bisa menampung lebih dari 1 widget di dalamnya. Hanya saja berbeda orientasi penggunaannya saja. Buka file yang sama dan modifikasi menjadi.
