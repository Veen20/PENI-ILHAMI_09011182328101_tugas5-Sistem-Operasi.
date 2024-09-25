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

  <img width="500" alt="Gambar WhatsApp 2024-09-25 pukul 19 36 31_5d8d2528" src="tps://github.com/user-attachments/assets/3e28dfae-e74e-4495-8bab-3d9ca0e38fe9">


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

  <img width="500" alt="Gambar WhatsApp 2024-09-25 pukul 19 50 22_3e9ac60a" src="https://github.com/user-attachments/assets/5caabcfa-226a-485f-97fa-47430e25d6db">


c. Jalankan instruksi subtitute user, kemudian keluar dengan perintah exit sebagai berikut: 
$ su mahasiswa \
$ exit 

kemudian gunakan opsi – sebagai berikut : 
$ su – mahasiswa \
$ exit \
Jelaskan perbedaan kedua utilitas tersebut. 

<br>

2. Prompt String (PS) 

a. Edit file .bash_profile, ganti prompt PS1 dengan ‘>’. Instruksi export diperlukan dengan 
parameter nama variable tersebut, agar perubahan variable PS1 dikenal oleh semua shell 
PS1=‟> „ 
export PS1 

b. Eksperimen hasil PS1 :
