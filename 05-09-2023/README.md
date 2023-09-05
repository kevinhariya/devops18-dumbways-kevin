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
1.Penjelasan tentang Htop:
Htop adalah sebuah utilitas pengawasan sistem interaktif berbasis teks yang digunakan untuk memonitor dan mengelola kinerja sistem di lingkungan Linux. Ini adalah alternatif yang lebih kuat dan serbaguna dibandingkan dengan utilitas top bawaan di Linux. Htop menyediakan antarmuka yang lebih mudah digunakan dan menampilkan informasi yang lebih terperinci tentang penggunaan CPU, memori, dan sumber daya sistem lainnya.


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



![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/b7ddc570-b865-4472-8c5b-201c0c4fccd6)
command f1 sampai f10 harus digunakan menggunakan fn+f1 dst

help = untuk mengetahui lebih lanjut mengenai tool di htop atau informasi tentang htop
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/5813891c-d22e-49b8-9467-2a46d9ae8ebc)


setup = untuk mengatur htop baik pada tampilan maupun informasi yang ingin ditampilkan pada kolom dan baris monitoring
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/4fa31eee-516f-4d44-9f8e-a2dd9564e504)


search = untuk mencari proses, user, command dengan nama tertentu
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/e015863b-d13b-40c3-9ba9-c91eb365329a)


filter = untuk memfilter command, proses, user dengan nama tertentu
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/990764ee-0f89-455e-ba91-289c1e57bc92)


tree = untuk menampilkan cabang command
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/f50f6827-178b-4234-8ed4-b47d41bcf920)


sortby = untuk mengurutkan berdasarkan karateristik tertentu seperti pada gambar
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/0ae0a48b-30e3-4e45-930c-fc79274dba2e)




3.BASH Script untuk instalasi nginx
![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/cdf44391-6583-4c10-9781-5eb6dcbf88cb)

![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/257b5255-6030-4158-9868-f9d2b10cdbd5)

![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/d2f54c4d-630b-42fd-8e05-d3083ccd3fe7)

![image](https://github.com/kevinhariya/devops18-dumbways-kevin/assets/135611481/63b2ef9d-32a6-4f3e-8c35-16c2ef48970f)



















