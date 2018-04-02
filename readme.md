# Java 8 Stream API Cook Book and Practical Example

![Imgur](https://i.imgur.com/Zz60wq7.png)

Kumpulan dokumentasi _Cook Book_ (buku resep) Java 8 Stream API, berserta 
contoh-contoh pengunaan praktis yang siap pakai dalam berbagai kasus. 

## 1. Baca Dahulu

Dokumentasi ini ditulis dengan tujuan dan harapan dapat digunakan sebagai 
acuan cepat dalam pengunaan Java Stream API berserta _libraries_ terkait lainnya. 
Dokumentasi akan dibagi berdasarkan kategori skenario serta kasus pengunaannya.

Sebelum memulai, silakan pahami dahulu point-point dibawah ini:

1. Untuk mencoba contoh-contoh dibawah, Anda membutuhkan __Java Development Kit (JDK) 8__. 
Akses ke link berikut untuk [Download JDK 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)

2. Untuk meminimalisir [_Boilerplate Code_](https://en.wikipedia.org/wiki/Boilerplate_code),
pada sebagian skenario saya mengunakan _library_ [Lombok](https://projectlombok.org/).
Silakan baca cara instalasi dan pemakaian _library_ Lombok nya.

3. Untuk contoh-contoh yang mengunakan _3rd party library_ diluar JDK,
akan saya sertakan link dan rujukan untuk mempelajari lebih lanjut.

4. Dokumentasi ini tidak diterbitkan maupun dimaintain secara versi, namun 
akan di-update secara terus menurut melalui repository GitHub ini. Hal
ini juga merupakan alasan kenapa saya tidak menuliskan nya ke dalam Blog.

5. Sebagian dari contoh mungkin bukan merupakan solusi optimal/ efisien, 
hanya sebagai penyelesaian untuk mendapatkan hasil yang sesuai.



## 9. Releated Reference
- [Java Stream Package Doc](https://docs.oracle.com/javase/8/docs/api/java/util/stream/package-summary.html)
