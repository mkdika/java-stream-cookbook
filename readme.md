# Java 8 Stream API Cook Book and Practical Example
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](/LICENSE)

Kumpulan dokumentasi _Cook Book_ (buku resep) Java 8 Stream API, berserta 
contoh-contoh pengunaan praktis yang siap pakai dalam berbagai kasus. 

![Imgur](https://i.imgur.com/Zz60wq7.png)


## 1. Readme First

> Untuk referensi mengenai pengenalan dan apa itu Java Stream API, silakan
ke bagian [Related Reference](#related-reference)

Dokumentasi ini ditulis dengan tujuan dan harapan dapat digunakan sebagai 
acuan cepat dalam pengunaan Java Stream API berserta _libraries_ terkaitaa lainnya. 
Dokumentasi akan dibagi berdasarkan 3 fase stream API yaitu: __Source, Intermediate Operation,
Terminal Operation.__

Sebelum memulai, silakan baca dahulu point-point dibawah ini:

1. Untuk mencoba contoh-contoh dibawah, Anda membutuhkan instalasi __Java Development Kit (JDK) 8__. 
Akses ke link berikut untuk [Download JDK 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)

2. Untuk meminimalisir [_Boilerplate Code_](https://en.wikipedia.org/wiki/Boilerplate_code), 
pada sebagian skenario saya mengunakan _library_ [Lombok](https://projectlombok.org/).
Silakan baca cara instalasi dan pemakaian _library_ Lombok nya. Atapun
code-code yang tidak berkaitan hanya akan saya tulis sebagai informasi dalam komentar (remarks).

3. Untuk contoh-contoh yang mengunakan _3rd party library_ diluar JDK,
akan saya sertakan link dan rujukan lebih lanjut nya. Untuk mempermudah
_library dependency management_ saya akan gunakan [Maven](https://maven.apache.org/).

4. Dokumentasi ini tidak dirilis maupun dimaintain secara versi, namun 
akan di-update secara terus menurut melalui repository GitHub ini. Hal
ini juga merupakan alasan kenapa saya tidak menuliskan nya ke dalam Blog.

5. Sebagian dari contoh mungkin bukan merupakan solusi optimal/ efisien, 
hanya sebagai penyelesaian untuk mendapatkan hasil yang sesuai.

6. Untuk sementara waktu sampai struktur dokumentasi telah lebih solid.
Saya menutup kolaborasi untuk dokumentasi ini. Apabila Anda memiliki ide
ataupun masukan silakan diisi pada [GitHub Issues](https://github.com/mkdika/java-stream-cookbook/issues).

7. Untuk referensi tambahan dan dokumentasi terkait lainnya, silakan ke bagian
[Releated Reference](#related-reference).

## 2. Stream Creation

#### Read Text Data from URL
#### Read Text Data from File
#### Iterate Stream with Index
#### Primitive Type Stream
#### Integer Range
#### Merging Multiple Stream

## 3. Stream Intermediate Operation

#### Sorting
#### Sorting Multiple Level
#### Combine Multiple List with Flatmap

## 4. Stream Terminal Operation

#### Group By and Do Something
#### Result to List
#### Result to Map
#### Result to String (Joining)

## 5. Stream Enchancement Library

Berikut merupakan contoh-contoh yang mengunakan library/framework alternatif 
dari Java 8 Stream API.

### 5.1 Streamex

Untuk rujukan lebih lanjut mengenai [Streamex](https://github.com/amaembo/streamex)

_Coming soon.._


### 5.2 Protonpack

Untuk rujukan lebih lanjut mengenai [Protonpack](https://github.com/poetix/protonpack)

_Coming soon.._


### 5.3 jOOL
Untuk rujukan lebih lanjut mengenai [jOOL](https://github.com/jOOQ/jOOL)

_Coming soon.._

## Related Reference
- [Java 8 Streams Introduction](http://www.baeldung.com/java-8-streams-introduction)
- [Java Stream Package Doc](https://docs.oracle.com/javase/8/docs/api/java/util/stream/package-summary.html)


