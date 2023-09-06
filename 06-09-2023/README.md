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



3.Selanjutnya kita akan mengedit file config di nginx yang kita punya dengan menggunakan sudo nano /etc/nginx/nginx.conf.






