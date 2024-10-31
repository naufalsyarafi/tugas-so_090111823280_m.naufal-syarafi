# tugas-so_090111823280_m.naufal-syarafi
#REMOTE UBUNTU SERVER dengan PROTOKOL SSH
TEORI DASAR
#SISTEM OPERASI LINUX
Linux merupakan software sistem operasi open source yang gratis untukdisebarluaskan di bawah lisensi GNU. Linux merupakan turunan dari unix dandapat bekerja pada berbagai macam perangkat keras koputer mulai dari interx86 sampai dengan RISC.Dengan lisensi GNU (Gnu Not Unix) Anda dapat memperoleh program,lengkap dengan kode sumbernya (source code). Tidak hanya itu, andadiberikan hak untuk mengkopi sebanyak anda mau, atau bahkan mengubahkode sumbernya dan itu semua legal dibawah lisensi. Meskipun gratis, lisensiGNU memperbolehkan pihak yang ingin menarik biaya untuk penggandaanmaupun pengiriman program.

2.Remote Server
Remote server adalah teknologi yang memungkinkan pengguna untuk mengakses sebuah server dan jaringan dari jarak jauh. Jadi meskipun tidak menggunakan jaringan LAN yang sama dengan server, pengguna server tetap bisa mengakses dan mengontrol server tanpa harus ke lokasi. Server jarak jauh (remote) juga merupakan suatu server yang bisa diakses dengan bagian proses lain tanpa harus membuka koneksi secara langsung tanpa harusterpisah.

LANGKAH-LANGKAH:
1).Membuka ubuntu server dan login ke halaman root

2).MENG-INSTALL OPENSSH DALAM TERMINAL UBUNTU SERVER konsol: sudo apt install openssh -y

3).start dan cek status service openssh

4).konfigurasi untuk mengganti port ssh jadi 40

konsol: nano /etc/ssh/sshd_config

5).start dan cek status port ssh

6).lihat alamat ip code: ifconfig

7).masukkan ip dan port dihalaman root aplikasi putty

8).jika sudah koneksi maka akan tampil login pada putty

selesai,perangkat sudah dapat dikendalikan menggunakan metode SSH server.
