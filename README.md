# Jarkom-Modul-1-IT01-2023
1. Lakukan filter ftp, ditemukan aktivitas STOR
![1-1](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/1-1.jpg)
![1-2](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/no1%20terminal.jpg)

2. Lakukan filter http, lalu follow stream pada yang punya info get http, dan terdapat info server
![2-1](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/2-1.jpg)
![2-2](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/2-2.jpg)
![2-3](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/no2%20terminal.jpg)

3. Untuk melihat berapa banyak paket yang tercapture dengan alamat IP source atau destination adalah 239.255.255.250 dan port 3702 di Wireshark, gunakan filter berikut:
(ip.src == 239.255.255.250 && udp.port == 3702) || (ip.dst == 239.255.255.250 && udp.port == 3702)
![3-1](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/3.png)
Setelah itu tinggal hitung jumlah package yg ada, yaitu ada 21. Lalu masukkan 21 ke jawaban, setelah jawaban benar ada soal lagi yaitu menggunakan protokol apa, sesuai dari hasil filternya, package package diatas menggunakan protokol UDP
![3-2](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/3%20terminal.png)
note : Untuk hasil flag yang berada pada screenshot diatas berbeda dari yang di submit karena untuk CMD nya sudah terclose, jadi saya mengulangi sekali lagi untuk cara pengerjaannya

5. Cari package pada urutan ke 130, setelah itu klik 2 kali dan cari nilai checksum.setelah menemukan nilainya, bisa inputkan pada nc dan mendapatkan hasil flagnya.
![4-1](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/4.png)
![4-2](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/4%20terminal.png)

6. Follow SMTP kemudian baca, dan ditemukan ada password yang di encode base64, kemudian lakukan decode, kemudian ekstrak zip dengan password yang diberikan. Konek ke nc yang terdapat disitu, kemudian jawab pertanyaan dengan analisis
![5-1](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/5-1.jpg)
![5-2](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/5-2.jpg)
![5-3](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/5-3.jpg)
![5-4](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/no5%20terminal.jpg)

7. Menuju paket nomer 7812, lalu dilihat ip sourcenya. kemudian petunjuk a1 e5 u21 menunjukkan bahwa 1 diubah ke a, dst. Decode ip sourcenya.
![6-1](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/6-1.jpg)
![6-2](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/6-2.jpg)
![6-3](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/no6%20terminal.jpg)

8. Menggunakan filter ip.dst, lalu dihitung jumlah packetnya yaitu ada 6
![7-1](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/7.jpg)

9. Dengan filter ini, Wireshark akan menampilkan semua paket yang memiliki port tujuan 80, baik menggunakan protokol TCP atau UDP.
![8-1](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/8%20terminal.png)

10. Dengan filter ini, Wireshark akan menampilkan semua paket yang berasal dari alamat IP 10.51.40.1 dan tidak menuju ke alamat IP 10.39.55.34.
![9-1](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/9%20terminal.png)

11. Filter dengan telnet, lalu follow streamnya. di stream terakhir terdapat password. dan di stream 2 ada username dengan password yang sama
![10-1](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/10-1.jpg)
![10-2](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/10-2.jpg)
![10-3](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/no10%20terminal.jpg)
