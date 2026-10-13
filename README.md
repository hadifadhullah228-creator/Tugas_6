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

<img width="1267" height="780" alt="image" src="https://github.com/user-attachments/assets/6f6079f7-448e-4944-a070-64c50c69a55a" />



c. Jadikan program ke 1 sebagai foreground, tekan ^Z dan kembalikan program
tersebut ke background

<img width="800" height="600" alt="5c" src="https://github.com/user-attachments/assets/7c5d89ad-4a64-47bd-b1c5-2b0c879105fc" />


d. Stop program background dengan utilitas kill

<img width="800" height="600" alt="5d" src="https://github.com/user-attachments/assets/69d289c1-175b-45a5-91e7-4e67969414f9" />



6. History
a. Ganti nilai HISTSIZE dari 1000 menjadi 20

<img width="800" height="600" alt="6a1" src="https://github.com/user-attachments/assets/2a427807-571d-438c-8ff2-fc3bcfc869e0" />


b. Gunakan fasilitas history dengan mengedit instruksi baris ke 5 dari instruksi yang
terakhir dilakukan

<img width="800" height="600" alt="6b" src="https://github.com/user-attachments/assets/9be2fa93-46ab-4b38-a178-ecacbd7dd857" />


c. Ulangi instruksi yang terakhir. Gunakan juga ^P dan ^N untuk bernavigasi pada
history bufer

<img width="800" height="600" alt="6c" src="https://github.com/user-attachments/assets/d7ec46af-e14d-4e26-b4c6-82ddbd6ecf2f" />


d. Ulangi instruksi pada history bufer nomor 150


<img width="800" height="600" alt="6d" src="https://github.com/user-attachments/assets/727dad04-33fe-49af-9672-a0ef3833bff4" />


e. Ulangi instruksi dengan prefix “ls”

<img width="800" height="600" alt="6e" src="https://github.com/user-attachments/assets/d1d302b8-9e79-482d-8d67-22300dfc1c32" />

