## Nama Kelompok

1. Fahrurrazi (1910131210002)
2. Fahrul Ikhsan Hidayatullah (1910131210004)
3. Rizky Ahmad (1910131310003)

# Client Sever
1. install terlebih dahulu network manager dengan net tools, perintah nya yaitu apt install network-manager dan apt install net-tools.

![gambar](/Tugas%202/Gambar/gambar_1.png)

2. kemudian atur ip address dengan mengetikan nano /etc/network/interfaces kemudian atur dengan konfigurasi seperti pada gambar berikut untuk ip address yang utama enp0s3 dan untuk ip yang akan di ping menggunakan enp0s8.

![gambar](/Tugas%202/Gambar/gambar_2.png)

3. kemudian restart jaringan dengan menggunakan systemctl restart networking dan systemctl restart networking.service untuk memulai ulang konfigurasi agar bisa mengubah ip yang telah di edit tadi.

![gambar](/Tugas%202/Gambar/gambar_3.png)

4. lalu lihat alamat ip yang sudah di restart dengan mengetikan perintah sudo ifconfig seperti pada gambar dibawah.

![gambar](/Tugas%202/Gambar/gambar_4.png)

5. lakukan ping ip pada linux dengan mengetikan perintah ping 192.168.42.1 untuk memanggil ip jika berhasil maka akan muncul tampilan sebagai berikut.

![gambar](/Tugas%202/Gambar/gambar_5.png)

6. lalu coba lakukan ping pada windows jika berhasil maka akan muncul tampilan sebagai berikut.

![gambar](/Tugas%202/Gambar/gambar_6.png