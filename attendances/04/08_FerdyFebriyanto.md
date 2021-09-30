<h1>Nama : Ferdy Febriyanto</h1>
NIM  : 1941720007
Kelas : TI3A
Pertemuan 3</h1>

<hr>

<h1>RecyclerView Android Studio</h1>

- <b>RecyclerView</b> adalah versi ListView yang lebih canggih dan fleksibel. Widget ini adalah kontainer untuk menampilkan rangkaian data besar yang bisa digulir secara sangat efisien dengan mempertahankan tampilan dalam jumlah terbatas.

- Untuk membuat recyclerview diperlukan data, data ini dapat berasal dari :

- Lokal dari variabel atau dari database lokal device android yang digunakan.
- Internet dari server yang di request melalu REST atau dengan cara lain.

- <b>Data</b> ini akan di representasikan sebagai sebuah file models dalam project android.

- <b>Adapter</b> menghubungkan data Anda dengan RecyclerView. Adapter menyiapkan data dan cara menampilkan data dalam view holder. Bila data berubah, adapter akan memperbarui materi tampilan item daftar terkait dalam RecyclerView.

- Adapter juga merupakan ekstensi dari RecyclerView.Adapter. Adapter menggunakan ViewHolder untuk menampung tampilan yang menyusun setiap item dalam RecyclerView, dan mengikat data untuk ditampilkan dalam tampilan yang menampilkannya.

- <b>View holder</b> adalah bagian dari adapter yang berisi tampilan informasi untuk menampilkan satu item dari layout item.

- <b>Pengelola layout menangani penyusunan (layout)</b> komponen antarmuka pengguna dalam suatu tampilan. Semua grup tampilan memiliki pengelola layout. Untuk LinearLayout, sistem Android menangani layout untuk Anda. RecyclerView memerlukan pengelola layout eksplisit untuk mengelola susunan list item yang terdapat di dalamnya. Layout ini bisa vertikal, horizontal, atau berupa grid.

- Daftar hutang
- Buat layout item_hutang.xml
- Buat package models
- Buat class Hutang.java
 
- private String nama;
- private int jumlah;

- Cmd + N untuk generate

- Konstruktor
- Setter dan getter

- Membuat package adapters
- Membuat class HutangAdapter extends RecyclerView.Adapter<HutangAdapter.ViewHolder>{}
- Import rv widget recyclerview
- Jika munch manfaatkan fitur android studio pika munch tanda será
- Alt + enter
- Ctrl + space
- Layout inflater fungsinya memanipulasi java. XML diubah menjadi kode java untuk kotlin
- Mengisi onBindViewHolder untuk menampilkan data
- Untuk mengambil data dari posisi
- Sebelum bah ke String Sebelum ditaruh ke text view
- Buka activity main
- Replace recycle view
- Buka main activity 
- Buat layout manager
- RecyclerView.LayoutManager
- Karena java perlu instansiasi items List Array list. 
- Items.add

- Linear layout manager
- Grid layout manager
- 


