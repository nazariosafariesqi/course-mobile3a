
Faris Ikhlasul Haq
07 / TI-2A

Jadi pembelajaran yang saya dapat pada hari adalah mengenai Recyler View yang terdiri dari beberapa Layout yaitu Grid Layout, Liner Layout dan Cardview. 
Sebenarnya masalah pada ListView dapat diatasi dengan menggunakan ViewHolder pattern., namun penggunaannya belum diharuskan di ListView. Berbeda dengan RecyclerView yang mewajibkan menggunakan ViewHolder. RecyclerView dan LayoutManager: Komponen antarmuka yang bertugas untuk menampilkan data set yang dimiliki di dalamnya. Layoutmanager akan mengatur posisi tampilan data baik itu secara list (vertikal), grid (baris dan kolom) atau staggered grid (grid yang memiliki susunan tak seragam / tak beraturan) Layout Inflater = merubah menjadi ke kode java atau kotlin  
OnBind View Holder untuk mengikat sebagai acuan untuk mengambil nilai sesuai position 1 Buah adapter maka menampilkan akan sejumlah item yang diinginkan. 
Komponen yang akan mengatur bagaimana menampilkan data set ke dalam RecyclerView. Di sinilah terjadi proses pengisian tampilan (ViewInflate) dari file layout xml untuk tiap elemen dari data yang sebelumnya terpasang (bind) ke dalam RecyclerView. 
Kumpulan data yang dimiliki dan ingin ditampilkan. Bisa berupa array, list maupun obyek map. 
Tambahkan dependencies komponen recyclerview pada file build.gradle  level modul. Tambahkan obyek RecyclerView di berkas layout xml dari activity / fragment. Definisikan model kelas (POJO) yang akan digunakan sebagai data source. Buat berkas layout xml untuk baris item di RecyclerView. Serta ada beberapa pelajaran tentang ControlHandler dan Bind File.