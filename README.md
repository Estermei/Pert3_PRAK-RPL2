Pada pertemuan 3 ini, kita belajar menerapkan konsep Model–View–Controller (MVC) dalam membuat program sederhana. MVC membantu memisahkan struktur aplikasi menjadi tiga bagian agar lebih rapi dan mudah dikelola.
- Model berisi class ModelMahasiswa yang menyimpan struktur data mahasiswa (seperti id, nama, npm, semester, ipk). Model bertanggung jawab mengelola data dan aturan yang terkait.
- DAO (Data Access Object) digunakan untuk mengatur proses penyimpanan, pengambilan, dan pengelolaan data mahasiswa. DAO bertindak sebagai penghubung antara model dan proses database/data list.
- Controller berfungsi sebagai pengatur alur program. Controller menerima input dari user (melalui View), lalu mengatur proses seperti menambah data, menampilkan data, menghapus data, atau memperbarui data mahasiswa.
- View berisi tampilan yang digunakan untuk berinteraksi dengan user. View menampilkan menu, menampilkan hasil data, dan menerima input dari pengguna.
