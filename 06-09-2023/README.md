menjalankan aplikasi dumbflix menggunakan PM2

1.Selanjutnya masuk ke dalam folder dumbflix dan jalankan `npm install` ini akan memasang semua dependensi dan module yang di perlukan untuk mendeploy si website dumblix, lalu jalankan `npm run build` ini akan membangun dan membuat folder build yang nantinya bisa kita gunakan untuk deploy website, terakhir jalankan `npm install -g serve` comand tersebut akan memasang serve secara global.
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/d162e4cd-84c2-4e8b-a9c5-f43098c6ff87)


2.Selanjutnya kita akan memasang pm2 jalankan perintah npm install -g pm2 npm akan menginstall pm2 secara global yang nantinya sangat berguna.
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/8743cb82-8eaa-4c56-ae64-dda422397ac1)


3.Setelah pm2 telah berhasil terinstall maka selanjutnya kita bisa langsung mendeploy website kita dengan comand pm2 serve build disini kita menjankannya dengan pm2 dari pada dengan npm, dan disana kita bisa melihat status dan informasti yang sangat bermanfaat dari pm2.
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/ea89b1ad-a6e8-4970-abc9-d3581958568d)


4.Terkahir kita bisa mengecek kedalam browser bahwa website kita telah berhasil di jalanlan disini kita akan mengetikan alamat ip computer kita beserta portnya yaitu 8080
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/9041fca9-a9b9-41c4-910e-cc188bab32d4)

.Membuat konfigurasi reverse proxy menguunakan 2 server didalam Vm

1.Masuk kedalam folder nginx dengan cara cd /etc/nginx lalu kita akan membuat folder didalam folder nginx mkdir dumbways && cd dumbways kita harus menggunakan jika ingin berinteraksi didalam folder etc karna folder etc sendiri masuk kedalam folder sistem root di linux, setelah masuk ke dalam folder dumbways kita akan membuat proxy dengan cara nano reverse-proxy.conf.
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/9383b69e-aed1-4031-9744-91088374fd98)



2.Kalian bisa mengikuti tulisan seperti saya yang ada di bawah ini, dengan catatan menggunakan ip komputer kalian sendiri beserta menggunakan port 8080.
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/a2b5fbba-0696-4985-a5a1-97f0ae684166)



3.Selanjutnya kita akan mengedit file config di nginx yang kita punya dengan menggunakan nano /etc/nginx/nginx.conf.
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/e50664f3-321e-4572-a1df-9e3af5cb44a6)



4.Kalian bisa menambahkan include seperti gambar yang ada di bawah ini, tulisan tersebut berfungsi sebagai akan memberitahu nginx bahwa akan membaca semua yang ada didalam folder dumbways termasuk config proxy yang sudah kita buat sebelumnya.
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/0f074e63-4598-4c36-b144-28743315fc53)



5.Setelah selesai mengedit file nginx.conf kita bisa mengecek bahwa systanx yang sudah kita tulis aman dan tidak ada eror dengan menulisakn sudo nginx -t dan jika mendapatkan pesan OK succesfull kita dapat melanjutkan ketahap berikutnya yaitu me reload nginx dengan cara sudo systemctl reload nginx.
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/09efbe50-7b02-4936-9039-d730b855c475)



6.Langkah selanjutnya kita harus mengedit file host yang ada di windows kita disini kalian bisa mengcopy path untuk masuk kedalam foldernya C:\Windows\System32\drivers\etc disana akan ada folder hosts dan buka dengan notedpad, pastikan menjalankannya dengan administrator agar kalian dapat mendedit file tersebut, selanjutnya masukan alamat ip kalian beserta nama webnya.
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/a9be7975-8dae-467f-8890-8fca5bcf3b4f)

![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/9ad8e630-93bf-4bef-9469-8c472fe5aaba)















