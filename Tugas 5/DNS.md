## Nama Kelompok

1. Fahrurrazi (1910131210002)
2. Fahrul Ikhsan Hidayatullah (1910131210004)
3. Rizky Ahmad (1910131310003)

# DNS (Domain Name System)

1. install dns terlebih dahulu dengan mengetikan perintah apt install bind9 dnsutils setelah itu akan muncul tampilan sebagai berikut.
![gambar](/Tugas%205/gambar/gambar%201.png)

2. setelah melakukan instalasi masuk ke dalam folder bind9 dengan mengetikan perintah cd /etc/bind dan lihat list file dengan mengetikan perintah ls setelah itu baru akan muncul hasil seperti digambar.
![gambar](/Tugas%205/gambar/gambar2.png)

3. copy folder dari db local ke db azi dan dari db 127 ke db 55 dengan cara mengetikan perintah cp db local db azi dan cp db 127 db 55 setelah selesai maka akan muncul hasil seperti pada gambar berikut.
![gambar](/Tugas%205/gambar/gambar3.1.png)
![gambar](/Tugas%205/gambar/gambar3.1.png)

4. langkah selanjut nya tinggal melakukan konfigurasi seperti gambar dibawah dengan cara mengetikan perintah nano db azi dan nano db 55 hingga mendapat hasil sebagai berikut.
![gambar](/Tugas%205/gambar/gambar4.png)
![gambar](/Tugas%205/gambar/gambar4.1.png)

5. langkah kelima kita tinggal mengaktifkan bind9 nya dengan cara mengetikan perintah systemctl start bind9.
![gambar](/Tugas%205/gambar/gambar5.png)

6. langkah ke enam jika sudah selesai maka kita bisa mencari alamat dns dengan cara mengetikan perintah nslookup azi042001.net.
![gambar](/Tugas%205/gambar/gambar6.png)