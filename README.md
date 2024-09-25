# PENI-ILHAMI_09011182328101_tugas5-Sistem-Operasi.

<div align="center">

## Praktikum 5 Job Control

*Dosen Pengampu:*\
Ahmad Heryanto, M. T.\
Adi Hermansyah, M. T.\
Sutarno, M.T.\
Iman Saladin B. Azhar, S. Kom., M. M.SI.\
Dr. Ahmad Zarkarsi, M. T.



<img src="https://github.com/user-attachments/assets/b086809c-d41c-4331-a4f6-93500d076a9c" alt="Alt Text" width="400">

<br>
<br>

*Disusun Oleh:*\
NAMA        : PENI ILHAMI\
NIM         : 09011182328101\
KELAS       : SK3B

<br>
<br>

*PRODI SISTEM KOMPUTER*  
*FAKULTAS ILMU KOMPUTER*  
*UNIVERSITAS SRIWIJAYA* \
*2024*

<br>
<br>

</div>

### TUGAS

1. Eksekusi seluruh profile yang ada : 

a. Edit file profile /etc/profile dan tampilkan pesan sebagai berikut : 
echo “Profile dari /etc/profile” 

  <img width="500" alt="Gambar WhatsApp 2024-09-25 pukul 16 48 13_dc0190dd" src="https://github.com/user-attachments/assets/541e772d-f7d7-48fe-88bb-2f2d6374b82a">
<br>
  <img width="500" alt="Gambar WhatsApp 2024-09-25 pukul 19 36 31_1f13bd21" src="https://github.com/user-attachments/assets/f4bf28e2-b72b-4852-9ac5-e90a67f26188">


b. Asumsi nama anda stD02001, maka edit semua profile yang ada yaitu : 

/home/stD02001/.bash_profile \
/home/. stD02001/.bash_login \
/home/mahasiswa/.profile \
/home/mahasiswa/.bashrc 

Ganti nama /home/mahasiswa dengan nama anda sendiri. Pada setiap 
file tersebut, cantumkan instruksi echo, misalnya pada /home/ mahasiswa/.bash_profile : \
echo “Profile dari .bash_profile” \
Lakukan hal yang sama untuk file lainnya, sesuaikan tampilan dengan nama file yang 
bersangkutan. 

  <img width="500" alt="Gambar WhatsApp 2024-09-25 pukul 19 36 31_e173cfe8" src="https://github.com/user-attachments/assets/901555e6-46c9-4ee2-aa7b-23ecef46f8d6">
<br>
  <img width="500" alt="Gambar WhatsApp 2024-09-25 pukul 19 50 22_3e9ac60a" src="https://github.com/user-attachments/assets/5caabcfa-226a-485f-97fa-47430e25d6db">
<br>
  <img width="500" alt="Gambar WhatsApp 2024-09-25 pukul 19 58 03_189a441d" src="https://github.com/user-attachments/assets/d4d3bcdb-e626-4420-af68-f315cbe07bc8">
<br>
  <img width="500" alt="Gambar WhatsApp 2024-09-25 pukul 20 04 01_11b05c24" src="https://github.com/user-attachments/assets/6a11d65e-f34a-4e4d-ab4e-2b86833e9a48">
<br>
  <img width="500" alt="Gambar WhatsApp 2024-09-25 pukul 20 08 53_66c61571" src="https://github.com/user-attachments/assets/71552c87-47e3-441e-8b4e-9546ef40b8f4">

c. Jalankan instruksi subtitute user, kemudian keluar dengan perintah exit sebagai berikut: \
$ su mahasiswa \
$ exit 

 <img width="500" alt="Gambar WhatsApp 2024-09-25 pukul 20 08 53_66c61571" src="https://github.com/user-attachments/assets/71552c87-47e3-441e-8b4e-9546ef40b8f4">

kemudian gunakan opsi – sebagai berikut : \
$ su – mahasiswa \
$ exit \

  <img width="500" alt="Gambar WhatsApp 2024-09-25 pukul 20 13 22_f353209e" src="https://github.com/user-attachments/assets/6810f7e8-1c35-4eb0-a0c0-128d196f16c5">

Jelaskan perbedaan kedua utilitas tersebut. \
Perbedaan antara perintah su peni-ilhami dan su - peni-ilhami terletak pada cara keduanya mengelola sesi login dan lingkungan shell.

su peni-ilhami:

1. Perintah ini hanya mengganti identitas pengguna menjadi peni-ilhami tanpa memulai sesi login penuh. Lingkungan shell yang dijalankan tetap mewarisi variabel-variabel dari pengguna sebelumnya.
2. Hanya file .bashrc yang dieksekusi, tanpa mengubah variabel lingkungan secara signifikan.
<br>
su - peni-ilhami:

1. Perintah ini memulai sesi login penuh untuk pengguna peni-ilhami, mirip dengan saat pengguna tersebut masuk langsung ke sistem.
File profil login seperti /etc/profile dan .bash_profile dijalankan, sehingga menginisiasi lingkungan baru yang sesuai dengan pengaturan pengguna.
2. Kesimpulannya, perintah su peni-ilhami hanya mengubah pengguna tanpa memodifikasi lingkungan shell secara menyeluruh, sementara su - peni-ilhami menjalankan sesi login lengkap dan menerapkan konfigurasi lingkungan baru dari file profil pengguna.

<br>

2. Prompt String (PS) 

a. Edit file .bash_profile, ganti prompt PS1 dengan ‘>’. Instruksi export diperlukan dengan 
parameter nama variable tersebut, agar perubahan variable PS1 dikenal oleh semua shell 
PS1=‟> „ 
export PS1 

b. Eksperimen hasil PS1 :
