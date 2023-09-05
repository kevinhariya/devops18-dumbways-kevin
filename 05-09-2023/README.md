1.Penjelasan text manipulation beserta step by step

1.Penjelasan apa itu text manipulation
   Text manipulation adalah proses mengubah teks untuk mencapai tujuan tertentu. Ini melibatkan operasi seperti mencari, mengganti, memisahkan, menggabungkan, dan 
   memformat teks. Contoh penggunaan text manipulation termasuk mengganti kata, memotong teks menjadi bagian-bagian, dan menghitung jumlah kata.

   
cat

1.cat namafile=untuk melihat file

2.cat > namafile = untuk mengubah file tanpa nano

3.cat file1 file2 > filegabungan = untuk menggabungkan dua file jadi satu file
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/564b3a6f-23cd-47be-a0ad-9b3742eceb8d)


sed

1.sed 's/katalama/katabaru/g' file = untuk mereplace kata
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/b0768694-a065-49e4-98d4-eb761106bcbf)


grep

1.grep kata file = untuk mencari kata pada file

2.grep -c kata file = untuk menghitung jumlah kata pada file

3.grep kata * = untuk mencari file yang berisi kata
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/b1814e04-c31c-4c21-a33a-335c9968bf13)


sort

1.sort file / sort -r file (reverse) = untuk mengurutkan berdasarkan abjad atau angka
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/72e47e0e-2793-4f27-9422-8099e99bcefa)


awk

awk '{print $1}' file = untuk menampilkan kata, baik kata pertama kedua atau seterusnya
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/d2cd1ac9-ddc1-4604-902d-46c194e84811)


cut

1.cut -b 1 file = untuk mengambil huru pertama, kedua atau seterusnya

2.cut -c 1,2,3,4 file = untuk mengambil beberapa huruf pada urutan tertentu

3.cut -d " " -f 1 file = untuk mengambil kata pada file tertentu
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/9199bc35-2663-4730-ab72-59309f113c04)


echo

1.echo "kata kata" = untuk mencetak kata

2.echo "kata kata" > file = untuk mereplace isi file dengan kata

3.echo "kata kata" >> file = untuk menambahkan isi file dengan kata
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/22f82ff9-ce03-4dd5-9284-9a5805b409d5)

htop
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/4a4f8f60-8e80-42ec-b048-daa3c9c6bdde)

CPU = jumlah core yang kita miliki.

Mem = total penggunaan memory.

Swp = Memory cadangan.

Tasks = aplikasi yang sedang berjalan di server.

Load average = rata-rata aplikasi yang berjalan.

Uptime = berapa lama server kita hidup.

PID = nomor proses id setiap proses yang berjalan di linux.

VIRT = memory yang terpakai.

Command = perintah apa yang sedang di jalankan.















