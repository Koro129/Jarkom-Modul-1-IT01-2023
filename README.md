# Jarkom-Modul-1-IT01-2023
1. Lakukan filter ftp, ditemukan aktivitas STOR
![1-1](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/1-1.jpg)
![1-2](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/no1%20terminal.jpg)

2. Lakukan filter http, lalu follow stream pada yang punya info get http, dan terdapat info server
![2-1](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/2-1.jpg)
![2-2](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/2-2.jpg)
![2-3](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/no2%20terminal.jpg)

5. Follow SMTP kemudian baca, dan ditemukan ada password yang di encode base64, kemudian lakukan decode, kemudian ekstrak zip dengan password yang diberikan. Konek ke nc yang terdapat disitu, kemudian jawab pertanyaan dengan analisis
![5-1](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/5-1.jpg)
![5-2](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/5-2.jpg)
![5-3](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/5-3.jpg)
![5-4](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/no5%20terminal.jpg)

6. Menuju paket nomer 7812, lalu dilihat ip sourcenya. kemudian petunjuk a1 e5 u21 menunjukkan bahwa 1 diubah ke a, dst. Decode ip sourcenya.
![6-1](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/6-1.jpg)
![6-2](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/6-2.jpg)
![6-3](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/no6%20terminal.jpg)

8. Menggunakan filter ip.dst, lalu dihitung jumlah packetnya yaitu ada 6
![7-1](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/7.jpg)

10. Filter dengan telnet, lalu follow streamnya. di stream terakhir terdapat password. dan di stream 2 ada username dengan password yang sama
![10-1](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/10-1.jpg)
![10-2](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/10-2.jpg)
![10-3](https://github.com/Koro129/Jarkom-Modul-1-IT01-2023/blob/main/screenshot/no10%20terminal.jpg)
