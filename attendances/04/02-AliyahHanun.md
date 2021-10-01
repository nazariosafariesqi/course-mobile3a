Aliyah Hanun S 
1941720175
TI 3A 
02 

Rangkuman Pertemuan 4:

Adaptor paling sederhana untuk digunakan disebut ArrayAdapter karena adaptor mengonversi objek ArrayList menjadi item View yang dimuat ke dalam container ListView.

RecyclerView adalah ViewGroup yang merender tampilan berbasis adaptor dengan cara yang serupa. Itu seharusnya menjadi penerus ListView dan GridView.
Setiap elemen individu dalam daftar ditentukan oleh objek view holder. 

RecyclerView meminta tampilan tersebut, dan mengikat tampilan ke datanya, dengan memanggil metode di adaptor. adaptor dapat ditentukan dengan memperluas RecyclerView.Adapter.

Manajer tata letak mengatur elemen individual dalam daftar Anda. Anda dapat menggunakan salah satu pengelola tata letak yang disediakan oleh pustaka RecyclerView, atau Anda dapat menentukan sendiri. Manajer tata letak semuanya didasarkan pada kelas abstrak LayoutManager perpustakaan.

RecyclerView provides these built-in layout managers:
- LinearLayoutManager shows items in a vertical or horizontal scrolling list.
- GridLayoutManager shows items in a grid.
- StaggeredGridLayoutManager shows items in a staggered grid.

RecyclerView menyertakan jenis adaptor baru. Ini adalah pendekatan yang mirip dengan yang sudah Anda gunakan, tetapi dengan beberapa kekhasan, seperti ViewHolder yang diperlukan.
Anda perlu mengganti tiga metode:
- onCreateViewHolder()
- onBindViewHolder()
- getItemCount()
