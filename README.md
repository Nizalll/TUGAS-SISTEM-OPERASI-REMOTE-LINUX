# TUGAS-SISTEM-OPERASI-REMOTE-LINUX 
Nama: Nazif Nizal
NIM: 09011282328070
Kelas: SK3A

Bahan-bahan=/*Linux ubuntu server 
            /*Linux ubuntu dekstop
          

Langkah-langkah

1.Install linux server dan desktop

2.buka linux server dan ubah network menjadi bridge adapter
![alt text](https://github.com/Nizalll/TUGAS-SISTEM-OPERASI-REMOTE-LINUX/blob/images/Screenshot%202024-10-30%20213709.png?raw=true)


3.jalankan perintah berikut sudo apt update,sudo apt install openssh-server

4.aktifkan ssh, sudo systemctl start ssh

5.periksa status SSH server untuk memastikan bahwa layanan aktif dengan sudo systemctl status ssh

6. cek ip dengan, ifconfig

7.lalu buka ubuntu dekstop, atur network dengan bridge adapter

8.buka terminal dan ketik perintah ssh username@IP_server




