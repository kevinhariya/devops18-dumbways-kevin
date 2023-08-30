Deploy Aplikasi wayshub-frontend dengan menggunakan NodeJS

1.Pertama-tama kita bisa membuat folder project terlebih dahulu dengan menggunakan comand mkdir.

![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/8f9c3916-7486-489f-9e7a-7ce228a2c84d)

2.setelah membuat folder project kita lalu meng clone website wayshub dengan mengambilnya langsung dari repositori github dengan perintah git clone 
  https://github.com/dumbwaysdev/wayshub-frontend.

![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/a82f9b8f-a907-440b-81b1-bf4764ac4f10)

3.Setelah selesai meng-clone lalu kita masuk ke folder wayshub dengan comand cd lalu di dalam folder kita harus menginstall semua dependensi dan package yang di 
  perlukan, kita bisa melakukannya dengan cukup mengetikan npm install


![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/858f27e3-fd80-4f6d-a201-e6008b4edaf0)

4.Kita juga bisa memperbaiki keamanan dengan npm audit fix (opsional).

![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/7623e48a-212d-49fa-9d01-23d47299e5ca)

5.Selanjutnya kita bisa membangun website kita dengan comand npm run build.




2.Deploy Golang dengan menampilkan nama kita


1, Pertama kita harus menginstall bahasa pemograman golang terlebih dahulu di os ubuntu kita, sebelumnya kita akan meng update repositori ubuntu dengan comand sudo 
   apt update && sudo apt upgrade -y.

  ![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/01933839-e868-431b-b4e5-7b9dffbe23cc)
  

2.Setelah selesai mengupdate repo ubuntu kita akan membuat folder baru yang akan kita berinama golang di dalam folder project yang telah kita buat.

![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/ce86f1e6-a089-4d42-b4d6-157872387827)


3.Selanjutnya kita bisa menginstall golang resmi dari repositori ubuntu dengan simpelnya mengetikan comand sudo apt install golang lalu kita tunggu sampai proses 
  installasi selesai akan tetapi kita disarankan untuk menginstallnya dari webnya golang dengan perintah wget https://dl.google.com/go/go1.13.5.linux-amd64.tar.gz 
  lalu sudo tar -C /usr/local/ -xzf go1.13.5.linux-amd64.tar.gz.

![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/f946cc63-9a8d-407a-a47c-215066c29feb)


4.Selanjutnya kita akan membuat file baru dengan nama print-name.go go sendiri adalah ekstensi dari golong ketikan comand berikut: nano print name.go dan ketikan 
  kode yang ada dibawah gambar ini.

  ![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/85b421e4-ff42-49fe-9434-29f66e99f595)
  

5.Setelah selesai kita bisa keluar dari nano dengan menekan tombol ctrl+x yang ada di keyboard, dan ketikan comand go build print-name.go untuk membangun aplikasi 
   golang yang telah kita buat.

  ![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/3ef49f80-5aeb-4df1-bf1a-727513212711)



   
6.Setelah selesai membangun file tadi kita akan notice bahwa ada file baru di folder kita dengan nama print-name, kita bisa langsung menjalankan file tersebut 
  dengan mengetikan ./print-name di terminal dan kode tersebut akan berjalan dan menampilkan nama kita.
  
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/d31e8b9f-d313-4584-8d39-75c63501cd8c)




  



Deploy Python dengan menampilkan nama kita

1.Untuk langkah pertama sama seperti project golang, kita bisa membuat folder terlebih dahulu di dalam project kita bernama python, karna python sudah hampir 
  terinstall semua secara bawaan di hampir semua distro linux jadi kita hanya akan menginstall pip dengan comand sudo apt install pip.

  ![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/f828bb50-cb31-423f-a02d-cfdc71c3a19a)
  

2. Setelah pip terinstall, kita akan membuat file baru dengan ekstensi .py dengan nama print-name.py dan kita juga akan menginstall flask untuk menyajikan code 
   kita yang akan di tampilkan didalam web browser, kita bisa menginstall flask dengan comand pip install flask.

   ![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/fbf2d4d1-4170-4103-8243-c665cdb09e8b)



3.Tuliskan code seperti di bawah ini, lalu setelah selesai kita akan keluar dari nano dengan menekan tombol ctrl+x.

![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/f52680bf-b8d7-4bd7-b5d7-0cd25724a2e4)


4.Setelah selesai kita bisa menjalankan script tersebut dengan perintah python3 print-name.py disana flask akan memberi tahu bahwa script kita telah running di 
  local host maupun jaringan local kita.

![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/81ea8c7b-bd59-4ed9-bfcd-72d686b3769e)


5.Terakhir kita bisa mengecek di browser dengan mengetikan alamat ip addres computer kita dan disana akan muncul nama kita.


![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/7987b624-3cfd-4646-9905-ec4fe6a1e603)



   




