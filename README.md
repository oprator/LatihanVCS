# LatihanVCS
Tutorial cara penggunaan git

Pertama kalian harus instal terlebih dahulu software Git Lalu kalian bisa buka software tersebut

1.Login Git

Langkah pertama kalian adalah memasukan username dengan menggunakan perintah:

$ git config --global user.name "UsernameAnda"

lalu kalian tambahkan juga email dengan menggunakan perintah

$ git config --global user.email "email anda"

![Gambar 1](screenshot/1.png)

Buat folder dengan menggunakan perintah dan buka folder tersebut

$mkdir Tugas

![Gambar 11](screenshot/11.png)

$cd Tugas

![Gambar 12](screenshot/12.png)


2.Login Github

Langkah kedua kalian bisa login ke dalam website github, Setelah kalian login akan muncul tampilan dashboard dari github tersebut

![Gambar 2](screenshot/2.png)

3.Membuat Repository Server

Setelah berhasil login ke GitHub, Anda bisa mulai membuat repository. Klik tombol New pada menu Repositories untuk membuat repository baru.

![Gambar 3](screenshot/3.png)

Kemudian kaliam akan diarahkan pada halaman untuk membuat repository baru seperti gambar di bawah ini.

![Gambar 4](screenshot/4.png)

Jika sudah akan muncul tampilan seperti ini:

![Gambar 5](screenshot/5.png)

kalian langsung copy url dan masukan perintah

$ git clone https://github.com/oprator/LatihanVCS.git

untuk menampilkan file README.md 

![Gambar 6](screenshot/6.png)

Untuk menambahkan file yang baru saja dibuat tersebut menggunakan perintah

$git add README.md

![Gambar 7](screenshot/7.png)

Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah

$ git commit -m "Menambahkan file"

![Gambar 8](screenshot/8.png)

kemudian gunakan perintah

$git branch -M main

![Gambar 9](screenshot/9.png)

Setelah itu menambahkan remote repository. remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository, sehingga dapat diakses oleh banyak user. dengan menggunakan perintah

$ git remote add origin https://github.com/oprator/LatihanVCS.git

![Gambar 10](screenshot/10.png)

Dan untuk mengirim perubahan pada local repository ke server gunakan perintah

$git push -u origin main

![Gambar 11](screenshot/11.png)

Dan kita bisa cek di repository langsung pada website github