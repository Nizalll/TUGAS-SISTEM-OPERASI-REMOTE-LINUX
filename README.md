# TUGAS LAPORAN PRAKTIKUM SISTEM OPERASI-REMOTE LINUX UBUNTU SERVER MENGGUNAKAN LINUX UBUNTU DEKSTOP 
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
![alt text](https://github.com/Nizalll/TUGAS-SISTEM-OPERASI-REMOTE-LINUX/blob/images/Screenshot%202024-10-30%20211411.png?raw=true)
![alt text](https://github.com/Nizalll/TUGAS-SISTEM-OPERASI-REMOTE-LINUX/blob/images/Screenshot%202024-10-30%20211445.png?raw=true)



4.aktifkan ssh dengan, sudo systemctl start ssh dan periksa status SSH server untuk memastikan bahwa layanan aktif dengan sudo systemctl status ssh
![alt text](https://github.com/Nizalll/TUGAS-SISTEM-OPERASI-REMOTE-LINUX/blob/images/Screenshot%202024-10-30%20213942.png?raw=true)


5.cek ip dengan,ifconfig
![alt text](https://github.com/Nizalll/TUGAS-SISTEM-OPERASI-REMOTE-LINUX/blob/images/Screenshot%202024-10-30%20214026.png?raw=true)


6.lalu buka ubuntu dekstop, atur network dengan bridge adapter
![alt text](https://github.com/Nizalll/TUGAS-SISTEM-OPERASI-REMOTE-LINUX/blob/images/Screenshot%202024-10-30%20214128.png?raw=true)


7.buka terminal dan ketik perintah ssh username@IP_server
![alt text](https://github.com/Nizalll/TUGAS-SISTEM-OPERASI-REMOTE-LINUX/blob/images/Screenshot%202024-10-30%20214236.png?raw=true)

setelah terhubung kita bisa menjalankan perintah untuk linux server dari linux dekstop 
![alt text](https://github.com/Nizalll/TUGAS-SISTEM-OPERASI-REMOTE-LINUX/blob/images/Screenshot%202024-10-30%20214315.png?raw=true)

di atas adalah contoh perintah tentang menggunakan phyton dan memeriksa status ssh di linux server






