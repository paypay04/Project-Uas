program ini memungkinkan kita untuk memasukan nama pengguna dan nomer rumah lalu di tampilkan dalam bentuk tabel

struktur program ini terdiri dari tiga kelas Utama yaitu:
1. class data berfungsi Bertanggung jawab untuk menyimpan data pengguna. 
2. class viw Mengembalikan seluruh daftar pengguna  da
3. class proses Mengatur alur logika, mulai dari menerima input pengguna hingga menampilkan data

1. class Data 
add_user: Untuk menambahkan data pengguna ke dalam daftar.
get_users: Mengembalikan seluruh daftar pengguna.

![class data](https://github.com/user-attachments/assets/543126e8-e5c1-462f-8d9e-ee0fea30eba1)


2. class view 
display_users: Menerima data pengguna sebagai parameter dan menampilkannya di terminal dengan format yang rapi.  
Lihat bagaimana format tabelnya diatur menggunakan fungsi bawaan Python, seperti format.

![class view](https://github.com/user-attachments/assets/3dbbd218-ee6b-4802-88f6-f80482f2a82a)


3. class proses 
get_user_input: Meminta input dari pengguna, seperti nama dan nomor rumah. Ada juga validasi input untuk memastikan nomor rumah adalah angka.  
run: Metode ini adalah inti dari program. Di sini kita menjalankan proses input pengguna secara berulang hingga pengguna memilih untuk berhenti, lalu menampilkan hasilnya.

![class project](https://github.com/user-attachments/assets/5ffad754-cb90-4b08-841b-4da69d4e73ec)


dan yang terakhir fungsi Utama program  memiliki blok if _name_ == "_main_":, yang berfungsi sebagai titik masuk utama. Di sini, kita membuat instance dari kelas Process dan menjalankan metode run.

![if main](https://github.com/user-attachments/assets/3cad7d48-a8c1-42c7-9c8c-9fc44642a537)


1. ketika program dijalankan, kita diminta memasukkan nama dan nomor rumah.  
2. Setelah input, kita bisa memilih untuk menambahkan pengguna lain atau berhenti.  
3. Ketika selesai, semua data pengguna akan ditampilkan dalam bentuk tabel

![Program berhasil](https://github.com/user-attachments/assets/2464383b-4c1f-4da6-b1e1-76a18a06840f)


karena no rumah harus berupa angka maka harus di isi dengan angka. Jika di isi dengan variabel lain maka program akan eror

![program tidak berhasil](https://github.com/user-attachments/assets/6df30525-129e-4d03-ac63-67d6393f2947)


Demikian penjelasan tentang program ini! , program ini memisahkan logika data, tampilan, dan proses, sehingga lebih mudah dipahami dan dikembangkan.

berikut link video youtube penjelasannya
https://youtu.be/7fEM5RoxcMs?si=GLc3oK-A_ueJuykS
