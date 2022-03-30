> Ketika mengoperasikan Linux OS kita harus menggunakan ***shell***, yaitu interface yang menyediakan akses ke layanan sistem operasi. 
***Shell*** disini bertugas untuk memproses semua perintah yang diketik di Command-Line Interface (**CLI**). 

> Penggunaan **CLI** akan lebih efektif karena Task yang membutuhkan proses dengan banyak langkah melalui GUI dapat dilakukan hanya dalam waktu sekian detik dengan mengetikkan command atau perintah ke **CLI**.

> Berikut adalah beberapa perintah dasar yang wajib diketahui untuk membantu pengguna baru menjelajahi Linux.


## Basic Commands di Linux
1. **pwd Command**
> Perintah dasar Linux **pwd** berfungsi untuk mencari path dari directory (folder) yang Anda gunakan saat ini. Contohnya adalah **/home/username**.

2. **cd Command**
> Untuk menjelajahi directory linux kita bisa menggunakan perintah **cd**. Misalnya kita ingin mengakses directory **/home/username/aFolder**, maka ketik **cd /home/username/aFolder**.

> Contoh shortcut dalam perintah cd :
>- **cd ..** : Untuk pindah ke satu directory diatas.
>- **cd** : Jika ingin langsung menuju folder home.
>- **cd-** : Untuk berpindah ke directory sebelumnya.  

3. **ls Command**
> **ls** berguna untuk melihat konten atau isi directory. Secara default perintah ini akan menampilkan isi directory saat ini. Untuk menampilkan isi directory lain contohnya **ls /home/username/aFolder**, untuk menampilkan isi directory **aFolder**

4. **cat Command**
> Perintah **cat** berfungsi untuk membuat daftar konten atau isi file pada standard output (sdout). Contohnya **cat file.txt**.

5. **cp Command**
> Perintah **cp** berguna untuk menyalin file dari directory saat ini ke directory yang berbeda. Contohnya **cp gambar.jpg /home/username/Pictures** untuk membuat salinan **gambar.jpg** dari directory saat ini ke directory **Pictures**.

6. **mv Command** 
> Perintah **mv** untuk memindahkan file, dan mengubah nama file. Contohnya **mv file.txt /home/username/Documents** dan untuk mengubah nama file bisa dengan **mv oldname.ext newname.ext**.

7. **mkdir Command**
> Perintah **mkdir** untuk membuat directory baru. Contohnya **mkdir aFolder**, maka akan muncul directory baru bernama **aFolder**.

8. **rmdir Command** 
> Perintah **rmdir** berguna untuk menghapus directory. Namun, **rmdir** hanya bisa digunakan untuk menghapus directory kosong.

9. **rm Command** 
> Perintah **rm** berguna untuk menghapus directory beserta semua isinya. 

> Harap Berhati-hati saat menggunakan perintah **rm**, perhatikan directory mana anda berada saat ini. Sekali command rm dijalankan, maka semua file tidak bisa dikembalikan.

10. **locate Command**
> Perintah **locate** digunakan untuk mencari file, seperti command pencarian pada Windows OS. Apabila ditambahkan argumen **-i**, command ini akan bersifat *case-insensitive* sehingga file dapat dicari meski Anda tidak mengingat namanya dengan tepat.

> Untuk mencari file yang memuat dua atau lebih dari dua kata, gunakan tanda bintang. Misalnya, perintah **locate -i school*note** akan mencari file yang pada namanya termuat kata “school” dan “note”, entah itu huruf besar atau kecil.

11. **find Command**
> Perintah **find** memiliki fungsi yang sama dengan perintah **locate**. Bedanya, perintah **find** lebih ditujukan untuk mencari file yang berlokasi di dalam directory yang diberikan. Contohnya **find /home/ -name notes.txt** akan mencari file bernama **notes.txt** di dalam directory home dan subdirectory-nya.

12. **grep Command** 
> 	Perintah **grep** berguna untuk melakukan pencarian disemua text di dalam file yang diberikan. Contohnya **grep helloworld notepad.txt** untuk mencari kata **helloworld** di file **notepad.txt**. 

13. **sudo Command** 






