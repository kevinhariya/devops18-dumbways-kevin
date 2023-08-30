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

  


  





