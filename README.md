# Tugas-6

1. Eksekusi seluruh profile yang ada :
   
a. Edit file profile /etc/profile dan tampilkan pesan sebagai berikut :
echo “Profile dari /etc/profile”

<img width="1272" height="795" alt="image" src="https://github.com/user-attachments/assets/966ab2a3-81e6-44e8-b9e8-eaa76dd6af7f" />




b. Asumsi nama anda stD02001, maka edit semua profile yang ada yaitu :

<img width="1307" height="827" alt="image" src="https://github.com/user-attachments/assets/a68f6f8d-1d29-414b-ad6f-5dd55676b19b" />




Ganti nama /home/mahasiswa dengan nama anda sendiri. Pada setiap
file tersebut, cantumkan instruksi echo, misalnya pada /home/
mahasiswa/.bash_profile :
echo “Profile dari .bash_profile”
Lakukan hal yang sama untuk file lainnya, sesuaikan tampilan dengan nama file
yang bersangkutan.


c. Jalankan instruksi subtitute user, kemudian keluar dengan perintah exit sebagai
berikut:

<img width="912" height="762" alt="image" src="https://github.com/user-attachments/assets/998811e1-23a8-45f0-b0d8-ee7ef63d6d28" />



2. Prompt String (PS)
   
a. Edit file .bash_profile, ganti prompt PS1 dengan ‘>’. Instruksi export diperlukan
dengan parameter nama variable tersebut, agar perubahan variable PS1 dikenal
oleh semua shell

<img width="1258" height="758" alt="image" src="https://github.com/user-attachments/assets/b136eae8-ce91-4818-a47c-2c715f29fe54" />



b. Eksperimen hasil PS1 :

<img width="1277" height="713" alt="image" src="https://github.com/user-attachments/assets/1a627011-4898-4352-bc7e-bd58f60a55dd" />



3. Logout

<img width="1265" height="713" alt="image" src="https://github.com/user-attachments/assets/f25b47bc-9e14-4524-8d1f-727f41e02097" />



4. Bash script
   
a. Buat 3 buah script p1.sh, p2.sh, p3.sh dengan isi masing-masing :
p1.sh
#! /bin/bash

<img width="1243" height="786" alt="image" src="https://github.com/user-attachments/assets/1fd335b9-e54c-4b8a-9a40-82e0eba74ec6" />



p2.sh
#! /bin/bash

<img width="1262" height="786" alt="image" src="https://github.com/user-attachments/assets/0749fde7-0fb8-4197-901e-6857d3da370c" />



p3.sh
#! /bin/bash

<img width="1267" height="777" alt="image" src="https://github.com/user-attachments/assets/431634d9-9765-4277-8a12-c58570a79783" />



b. Jalankan script tersebut sebagai berikut :

<img width="1262" height="791" alt="image" src="https://github.com/user-attachments/assets/90bf97c9-f887-417b-89a2-16316d7c5d1b" />


<img width="1263" height="777" alt="image" src="https://github.com/user-attachments/assets/596005bd-1eb5-448d-91b9-59673538f467" />


<img width="1255" height="782" alt="image" src="https://github.com/user-attachments/assets/d9e1cc4c-5098-44bd-b0b3-06421050fcba" />




5. Jobs
   
a. Buat shell-script yang melakukan loop dengan nama pwaktu.sh, setiap 10 detik,
kemudian menyimpan tanggal dan jam pada file hasil.

<img width="1271" height="785" alt="image" src="https://github.com/user-attachments/assets/af21969c-ee2e-4b5c-a587-e9f787e95d2f" />



b. Jalankan sebagai background; kemudian jalankan satu program (utilitas find) di
background sebagai berikut :

<img width="947" height="281" alt="image" src="https://github.com/user-attachments/assets/7f7fd7bd-f5eb-4abf-a56d-d49eef149cfd" />




c. Jadikan program ke 1 sebagai foreground, tekan ^Z dan kembalikan program
tersebut ke background

<img width="697" height="278" alt="image" src="https://github.com/user-attachments/assets/467c3b3a-d215-42e0-a36e-1922f5ae324d" />



d. Stop program background dengan utilitas kill


<img width="1267" height="770" alt="image" src="https://github.com/user-attachments/assets/35ac7fcd-d5a7-41da-b07c-56605032adcc" />

<img width="1255" height="773" alt="image" src="https://github.com/user-attachments/assets/62e6153f-7bba-4a1c-863b-d4a96ba9399f" />







6. History
   
a. Ganti nilai HISTSIZE dari 1000 menjadi 20

<img width="1263" height="777" alt="image" src="https://github.com/user-attachments/assets/5bf610da-6744-456a-a49d-f9da5e53d520" />

b. Gunakan fasilitas history dengan mengedit instruksi baris ke 5 dari instruksi yang
terakhir dilakukan

<img width="1073" height="306" alt="image" src="https://github.com/user-attachments/assets/8d28c179-9088-4639-bd0e-2f8c78375d60" />



c. Ulangi instruksi yang terakhir. Gunakan juga ^P dan ^N untuk bernavigasi pada
history bufer

<img width="752" height="233" alt="image" src="https://github.com/user-attachments/assets/0dc273dc-a993-455d-bec8-01ed17148ad2" />


d. Ulangi instruksi pada history bufer nomor 150


<img width="1001" height="437" alt="image" src="https://github.com/user-attachments/assets/4c68a81f-534d-44f4-8654-2af8d6502ab0" />


e. Ulangi instruksi dengan prefix “ls”

<img width="1266" height="307" alt="image" src="https://github.com/user-attachments/assets/05594f37-6cfe-47cf-b95e-05f8f2f9752a" />


