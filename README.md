# Recyclerview
> RecyclerView adalah sebuah komponen tampilan (widget) yang lebih canggih ketimbang pendahulunya listview. Ia bersifat lebih fleksibel. RecyclerView memiliki kemampuan untuk menampilkan data secara efisien dalam jumlah yang besar. Terlebih jika Anda memiliki koleksi data dengan elemen yang mampu berubah-ubah sewaktu dijalankan (runtime).

## Pengunaan Recyclerview
Langkah-langkah mengimplementasikan recyclerview sebagai berikut :
- [x]	Tambahkan dependencies komponen recyclerview pada file build.gradle  level modul.
- [x]	Tambahkan obyek RecyclerView di berkas layout xml dari activity / fragment.
- [x]	Definisikan model kelas (POJO) yang akan digunakan sebagai data source.
- [x]	Buat berkas layout xml untuk baris item di RecyclerView.
- [x]	Buat sebuah kelas adapter yang inherit ke RecyclerView.Adapter dan ViewHolder untuk menampilkan tiap elemen data.
- [x]	Definisikan obyek RecyclerView berikut dengan bentuk yang diinginkan (bisa dalam bentuk list, grid, atau staggered) dan selanjutnya pasang obyek adapter (binding) agar bisa menampilkan koleksi data ke dalam RecyclerView.

## Berikut tampilan dari Recyclerview Pahlawan Indonesia
### tampilan mode List
> akan menampilkan daftar pahlawan beserta foto dan menampilkan sedikit informasi mengenai deskripsi pahlawan tersebut sekitar 2 baris
## Screnshoot
![ALt Text](https://github.com/rendiwibawa/Recyclerview_Basic/blob/master/List.jpeg)

### tampilan mode Grid
> akan menampilkan daftar pahlawan beserta foto dalam bentuk grid tanpa deskripsi/ hanya tampilan foto
## Screnshoot
![ALt Text](https://github.com/rendiwibawa/Recyclerview_Basic/blob/master/Grid.jpeg)

#THANKS


