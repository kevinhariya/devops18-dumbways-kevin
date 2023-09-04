1. Penjelasan Penjelasan tentang Distributed Version Control
   Distributed Version Control atau (DVC) adalah metode pengelolaan versi yang memungkinkan Developer bekerja secara terdistribusi dengan repositori yang 
   terdistribusi secara lokal. Setiap pengembang memiliki salinan penuh dari repositori dengan sejarah lengkap perubahan. DVC, seperti Git, memungkinkan kolaborasi, 
   fleksibilitas, dan ketahanan terhadap gangguan. Developer dapat bekerja secara independen, membuat cabang, dan menyinkronkan perubahan dengan pengembang lain. 
   Namun, penggunaan DVC memerlukan pemahaman yang lebih dalam dan disiplin dalam mengelola versi aplikasi/software.
   
2. buat repository dengan nama makanan kesukaan kalian (diluar tugas) yang berisi 3 file dengan isi yang berbeda,
   Buat 2 branch
   
   1.Masuk ke folder project lalu buat folder mkdir bakso bakar lalu cd bakso bakar dan ketikan git init, git init digunakan untuk membuat repositori Git baru di 
     dalam direktori proyek. Repositori ini akan melacak perubahan yang terjadi pada proyek.
   ![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/245415c1-4621-4042-b13b-30a6a33fd1a5)


   
   2.Anda dapat membuat repositori baru menggunakan Command-Line Interface GitHub, GitHub CLI atau disingkat sebagai gh, adalah alat baris perintah yang 
     memungkinkan 
     Anda berinteraksi dengan GitHub melalui terminal. sudo apt update && sudo snap install gh --classic, dengan gh ini nantinya kita bisa membuat repo github 
     langsung dari terminal.
   ![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/cd842cba-4471-4a51-8a65-b0296789c963)
   


   3.Ketikan gh repo create baksobakar --public, Perintah gh repo create baksobakar --public digunakan untuk membuat repositori baru dengan nama "baksobakar" di 
     GitHub melalui CLI (Command-Line Interface) GitHub (gh). Opsi --public menentukan bahwa repositori yang dibuat akan memiliki status publik, yang berarti dapat 
     diakses dan dilihat oleh siapa saja. dan anda juga bisa melihat status atau alamat url repo yang tadi dibuat dengan perintah gh repo view baksobakar.
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/79a2f31f-221c-4247-b21c-de6b5527f90a)

   

   4.Gunakan coma touch untuk menambah 3 file sekaligus 'touch file1 file2 file3`, setelah 3 file tadi dibuat lalu git add. Perintah git add digunakan untuk 
     menambahkan semua perubahan dalam direktori proyek ke staging area sebelum melakukan commit. Dengan menjalankan perintah ini, Anda memberitahu Git agar 
     melacak 
     perubahan yang ada dalam file-file proyek. Setelah perubahan ditambahkan ke staging area, Anda dapat melakukan commit untuk menyimpan perubahan-perubahan 
     tersebut ke dalam repositori Git. git commit -m "Create 3 file".
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/44bf6e31-1e9a-4b90-add0-84c5b367b37c)

   

   5.Selanjutnya lakukan push dengan git push -u origin main.
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/868197be-432a-4d42-91c6-44139f0b2140)

   

   6.Selanjutnya membuat dua branches yang berbeda git branch staging dan git branch production.
   ![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/cd01ca89-f21e-4ad7-b752-7e814bd575d7)
   


   7.Langkah terakhir untuk mempublish semua branch yang telah kita buat ke dalam platfrom github dengan cara, git push origin staging dan juga git push origin 
     production.
   ![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/05b9608d-8a54-45e4-87dc-6882233119b5)



   8.Dan berikut adalah hasil dari sample repo, 3 file, dan juga 2 branch baru yang telah kita buat.
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/1bf792df-d57c-4581-a479-2ad601f1df7c)

   
   

  4. Cari 3 command git yang belum dijelaskan
     
     1.git statsh, Perintah "git stash" digunakan dalam Git untuk menyimpan perubahan sementara yang belum siap untuk di-commit. Ini berguna ketika sedang bekerja 
       pada suatu cabang (branch) dan perlu beralih ke cabang lain tetapi tidak ingin melakukan commit perubahan yang belum selesai.
     
     2.git reflog, "git reflog" digunakan untuk melihat riwayat referensi atau perubahan referensi dalam repositori Git. Ini membantu melacak perpindahan referensi 
       seperti HEAD, cabang, atau tag, dan memulihkan keadaan sebelumnya jika terjadi kesalahan atau kehilangan commit.

     3.git cherry-pick, "git cherry-pick" digunakan untuk mengambil perubahan spesifik dari satu cabang dan menerapkannya ke cabang lain dalam Git.


 
