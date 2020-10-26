# PENGENALAN GITHUB
 
 Github adalah sebuah layanan repositori untuk menyimpan project secara online, project yang kita upload di github bersifat
open-source yang bisa dikembangkan oleh programmer lain. Kelebihan github adalah ketika kita membuat sebuah repositori
project, kemudian menguploadnya lalu kita membuat perubahan atau penambahan pada project tersebut dan di upload ulang ke
repositori itu maka project yang lama tidak akan hilang, jadi kita bisa membuat beberapa versi dari project yang dibuat dan 
hal ini sangat memudahkan bila kita ingin ke versi sebelumnya.
 Github merupakan layanan repositori git yang sangat besar dan telah dikenal luas. Banyak varian repositori yang bisa diakses
secara gratis sehingga menjadikan Github menjadi terkenal dengan layanan penyimpanan source code. Jika proyek kita bersifat 
open source, Github bisa menjadi pilihan yang tepat. Namun kelemahannya, jika kita menginginkan privasi untuk proyek, kita
harus membayar Github.
	
# PERINTAH DASAR GITHUB
 
 Ada beberapa perintah dasar yang biasanya digunakan, perintah dimulai dari kata "git" :

**git init**
untuk membuat repositori lokal di dalam folder project

**git clone**
untuk meng-clone atau meng-copy projek dari repositori

**git status**
untuk menampilkan status pada repositori lokal

**git add**
untuk menambah file baru pada repositori yang dipilih

**git commit**
untuk menyimpan perubahan dan setiap perubahan ini wajib memberikan keterangan pada setiap perubahan

**git push**
untuk mengirimkan perubahan file setelah di commit ke repositori

**git pull**
untuk mengambil file yang sudah di ubah dan di upload

**git branch**
untuk melihat branch yang tersedia pada repositori

**git merge**
untuk menggabungkan semua branch yang ada pada repositori

# LANGKAH MEMBUAT REPOSITORI
 
 Berikut adalah langkah-langkahnya :

1. Download software Git disini. Sesuaikan dengan sistem operasi yang digunakan, disini saya menggunakan Windows
2. Lakukan instalasi Git seperti software pada umumnya
3. Silahkan buat akun terlebih dahulu di github.com
4. Login ke Github.com dan buatlah sebuah repository baru dengan mengeklik tombol yang terletak pada kanan atas seperti gambar berikut:

![Sc9](https://user-images.githubusercontent.com/73066008/97151751-8812b400-17a2-11eb-87f4-df499b34c254.png)

5. Buat repository baru, misalnya dengan nama “Latihan_VCS” kemudian klik tombol Create repository lihat gambar:

![Sc10](https://user-images.githubusercontent.com/73066008/97152028-e9d31e00-17a2-11eb-82b0-813bfe64dfb6.png)

6. Sekarang kita bisa mengakses remote repository dengan url
https://github.com/alridwanluthfi00/Latihan_VCS.git

![Sc15](https://user-images.githubusercontent.com/73066008/97153453-16883500-17a5-11eb-8955-27ec656b3fe2.png)

7. Arahkan pada direktori tempat project akan diupload ke repository di Github
8. Untuk pengguna Windows klik kanan folder project dan pilih Git Bash. Berikut gambarnya:

![Sc16](https://user-images.githubusercontent.com/73066008/97154517-8c40d080-17a6-11eb-9ebd-bd103161525e.png)

9. Kemudian akan muncul command prompt / CMD dari git bash tersebut
10. Selanjutnya yang perlu kita lakukan adalah mengkonfigurasikan username & email kita pada git dengan mengetikan syntax: 
 'git config --global user.name "Nama Anda"' 'git config --global user.email "Email Anda"'. Seperti pada gambar dibawah.

![Sc3](https://user-images.githubusercontent.com/73066008/96375780-4338bd00-11a5-11eb-9f1a-702a4b27f3af.png)

11.  Setelah melakukan konfigurasi username dan email, kemudian lakukan inisiasi dengan menulis perintah berikut
 'Git init'

![Sc17](https://user-images.githubusercontent.com/73066008/97158390-eee89b00-17ab-11eb-92a4-7104bfe88b12.png)

12. Kemudian tambahkan semua file yang ada dalam folder project kita, ketikan
 'Git add *'dan buat commit projectnya, sebagai contoh disini commit “LatihanVCS”
 'Git commit –m "LatihanVCS"

![Sc18](https://user-images.githubusercontent.com/73066008/97165711-b3070300-17b6-11eb-93f0-b59966ca900a.png)

13. Setelah kita buat commit untuk projectnya, remote repository yang telah dibuat tadi, contoh https://github.com/alridwanluthfi00/LatihanVCS.git, ketikan
Git remote add origin https://github.com/alridwanluthfi00/LatihanVCS.git

![Sc19](https://user-images.githubusercontent.com/73066008/97167318-2c075a00-17b9-11eb-89e7-067d52dc1eed.png)

14. Kirim project ke repository kita
 'Git push origin master'

![Sc20](https://user-images.githubusercontent.com/73066008/97168317-d3d15780-17ba-11eb-96bc-d2baecca2231.png)

15. Terakhir, kita akan diminta username dan password kita. Untuk password mungkin kita tidak akan melihat password yang kita ketikan
16. Tunggu sampai project selesai di upload
17. Jika proses upload selesai, cek pada Github lalu refresh repository, maka file kita sudah terupload disana

![Sc21](https://user-images.githubusercontent.com/73066008/97168689-6eca3180-17bb-11eb-9e7e-c898e48e8269.png)


## SEMOGA BERMANFAAT, SEKIAN DAN TERIMA KASIH. WASSALAMU'ALAIKUM WARRAHMATULLAHI WABARAKATUH
