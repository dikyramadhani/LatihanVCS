# LatihanVCS
Repository ini dibuat untuk memenuhi Tugas Pertemuan 4 - Bahasa Pemrograman

Nama : Diky Ramadhani <br>
Kelas : TI.20.B1 <br>
NIM : 312010074 <br>

## Langkah-Langkah Penggunaan Git
* Langkah pertama, silahkan download git pada link berikut : [Klik disini](git-scm.com)
* Setelah file di download, selanjutnya lakukan instalasi dengan referensi berikut : [Panduan Installasi Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* Lalu jika installasi telah selesai, buka *software* **GitBash** pada menu di Windows, dan lakukan pengecekan versi,  dengan mengetik syntax berikut :
> git--version <br>
![gambar scm git](Gambar/git-version.PNG)
* Jika muncul tampilan git version, berarti Git sudah berhasil di install dan bisa di gunakan.
Langkah pertama, kita harus mengkonfigurasikan user nama dan email di Git, dengan mengetikkan syntax berikut :
> git config --global user.name "Masukkan Nama Anda disini" <br>
![gambar scm git](Gambar/git-username.PNG) <br>
> git config --global user.email "Masukkan Email anda disini" <br>
![gambar scm git](Gambar/git-useremail.PNG) <br>
Setelah diisi, silahkan lakukan pengecekan user nama dan email, dengan mengetikkan perintah berikut : <br>
> git config --global user.name <br>
> git config --global user.email <br>
* Buat akun di [GitHub](github.com) , seperti contoh dibawah. Dan lakukan *Verifikasi* akun melalui email yang sudah terdaftar.
![gambar scm git](Gambar/github-signup.PNG)
* Jika akun GitHub sudah dibuat dan di verifikasi, Proses selanjutnya silahkan buat *Repository* seperti gambar dibawah ini. <br>
**Penjelasan :**
> * Repository Name : (Isi nama repository yang diinginkan sesuai selera anda, contohnya seperti saya ingin membuat repository *LatihanVCS*) <br>
> * Description : (Isi dengan penjelasan tentang repository yang anda buat) <br>
> * Public / Private : (Pilih salah satu jenis repository akan bisa dilihat oleh semua orang atau tidak) <br>
> * Add a README.mc file : Centang pada bagian ini jika anda menginginkan file README.md ada di repository anda <br>
> * Add .gitignore : Merupakan sebuah file yang berisi daftar nama-nama file dan direktori yang akan diabaikan oleh Git <br>
> * Choose a license : Silahkan centang jika anda memiliki lisensi pada repository yang akan dibuat kemudian tekan tombol **Create Repository** untuk menyimpan <br>
![gambar scm git](Gambar/github-newrepo.PNG)
* Jika repository sudah dibuat maka akan muncul tampilan seperti dibawah ini :
![gambar scm git](Gambar/github-view1.PNG)
* Pembuatan akun dan repository pada GitHub telah selesai, lalu saat ini kita lakukan untuk *me-remote* repository GitHub pada GitBash Lokal. Caranya adalah, Pertama kita harus menyalin *link URL* git kita di Github, dengan cara tekan tombol *Code* lalu klik *Copy*.
* Setelah *Link URL* git kita tercopy, Selanjutnya silahkan buka File Explorer pada Windows, kemudian pilih folder dimana kita akan *Mendownload* Repository dari GitHub ke lokal. Kemudian Klik Kanan, Pilih **Git Bash Here**.
![gambar scm git](Gambar/klik-kanan.PNG)
* *Pop Up* Command Prompt (CMD) akan terbuka. Pada proses ini kita akan melakukan download file repository yang tadi dibuat, dengan mengetikkan *syntax* berikut :
> git clone [URL] Pada contohnya, saya akan memasukkan *git clone* <br>
> https://github.com/dikyramadhani/LatihanVCS.git <br>
![gambar scm git](Gambar/git-clone.PNG)
* Setelah proses cloning selesai, pada saat ini kita masih pada folfer awal (master), kita harus masuk kedalam folder yang telah di cloning tadi. yaitu, *LatihanVCS* dengan mengetikkan *syntax* berikut :
> cd LatihanVCS/ <br>
![gambar scm git](Gambar/cd.PNG)
* Lalu saat ini kita sudah masuk kedalam folder *LatihanVCS*,Silahkan edit file **README.md** yang ada di File Explorer. Bisa menggunakan Text Editor (*Sublime Text, Notepad, Notepad++, Visual Studio Code*). Edit sesuai keinginan anda.
Aturan file .md (Markdown) bisa dilihat di [Link ini](guides.github.com/features/mastering-markdown/) <br>
![gambar scm git](Gambar/edit-file.PNG)
Setelah file README.md diedit, silahkan simpan file tersebut dengan cara **CTRL+S** atau **File > Save**
* Langkah selanjutnya setelah file disimpan, kita kembali pada App Git Bash (CMD). Ketik pada Git Bash seperti berikut ini :
> git add <br>
![gambar scm git](Gambar/git-add.PNG)
* Setelah selesai melakukan *git add*. langkah selanjutnya adalah melakukan *commit*. Fungsi commit adalah untuk menyimpan perubahan yang dilakukan, tetapi tidak ada perubahan pada remote repository. Ketik pada App Git Bash seperti berikut ini :
> git commit "Update README.md"
![gambar scm git](Gambar/git-commit.PNG)
* Semua proses telah selesai, silahkan kembali ke Web Browser untuk melihat perubahan yang telah di *commit* dan *push* dari remote.
![gambar scm git](Gambar/github-view2.PNG)
## TERIMA KASIH , SEMOGA BERHASIL !

