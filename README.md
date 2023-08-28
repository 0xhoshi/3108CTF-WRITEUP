# WRITEUP-3108CTF
---------------------------------------------------------------------------
## __Categories__

- [**TUGASAN UTAMA : WARKAH UNTUK PERWIRA**](#TUGASAN-UTAMA--WARKAH-UNTUK-PERWIRA)
  - [Tugasan I : Seruan Perwira](#Tugasan-I--Seruan-Perwira)
  - [Tugasan II : Tali Barut](#Tugasan-II--Tali-Barut)
  - [Tugasan III : Pangkalan Gelap](#Tugasan-III--Pangkalan-Gelap)

<!-- [**TUGASAN SAMPINGAN (OSINT)**](#TUGASAN-SAMPINGAN-(OSINT))
  - [Pertemuan Kapista : Babak I (Mudah)](#Pertemuan-Kapista-:-Babak-I-(Mudah))
  - [Pertemuan Kapista : Babak II (Mudah)](#Pertemuan-Kapista-:-Babak-II-(Mudah))
  - [Pertemuan Kapista : Finale (Mudah)](#Pertemuan-Kapista-:-Finale-(Mudah))
  - [Hero Melayu (Mudah)](#Hero-Melayu-(Mudah))
  - [Kisah Lama (Mudah)](#Kisah-Lama-(Mudah))
  - [Mesej Dalam Botol (Sederhana)](#Mesej-Dalam-Botol-(Sederhana))
  - [Saya Di Mana (Mudah)](#Saya-Di-Mana-(Mudah))
 
- [**TUGASAN SAMPINGAN (WEB)**](#TUGASAN-SAMPINGAN-(WEB))
  - [Lemah (Mudah)](#Lemah-(Mudah))
  - [Wantujus (Mudah)](#Wantujus-(Mudah))
  - [Wantusom (Sederhana)](#Wantusom-(Sederhana))
  - [Pantun Pantul (Sederhana)](#Pantun-Pantul-(Sederhana)) 

- [**TUGASAN SAMPINGAN (CRYPTOGRAPHY)**](#TUGASAN-SAMPINGAN-(CRYPTOGRAPHY))
  - [Nasihat (Mudah)](#Nasihat-(Mudah))
  - [Selamat Malam (Sederhana)](#Selamat-Malam-(Sederhana))
  - [Keretapi Tanah Melayu 🚂 (Mudah)](#Keretapi-Tanah-Melayu--(Mudah))
  - [Jerebu (Sederhana)](#Jerebu-(Sederhana))
  - [1957bit (Sederhana)](#1957bit-(Sederhana))

- [**TUGASAN SAMPINGAN (MISC)**](#TUGASAN-SAMPINGAN-(MISC))
  - [Mencari Rahsia Si Dia (Mudah)](#Mencari-Rahsia-Si-Dia-(Mudah))
  - [Pesan Tentang Bicara (Sederhana)](#Pesan-Tentang-Bicara-(Sederhana))
  - [3108 CTF Town (Sederhana)](#3108-CTF-Town-(Sederhana))
  - [Nasi Lemak 1 Juta (Mudah)](#Nasi-Lemak-1-Juta-(Mudah))
 
- [**TUGASAN SAMPINGAN (STEGA)**](#TUGASAN-SAMPINGAN-(STEGA))
  - [Tugu Negara (Sederhana)](#Tugu-Negara-(Sederhana))
  - [Jalur Gemilang (Mudah)](#Jalur-Gemilang-(Mudah))
  - [Hari Keramat (Mudah)](#Hari-Keramat-(Mudah))
  - [Uncover (Sederhana)](#Uncover-(Sederhana))
 
- [**TUGASAN SAMPINGAN (NETWORK)**](#TUGASAN-SAMPINGAN-(NETWORK))
  - [Johan (Mudah)](#Johan-(Mudah))
  - [Lagi-Lagi Johan (Mudah)](#Lagi-Lagi-Johan-(Mudah))
  - [Jalan Jalan Di Kuala Lumpur (Mudah)](#Jalan-Jalan-Di-Kuala-Lumpur-(Mudah))
 
- [**TUGASAN SAMPINGAN (FORENSICS)**](#TUGASAN-SAMPINGAN-(FORENSICS))
  - [Negeri-Negeri Di Malaysia (Mudah)](#Negeri-Negeri-Di-Malaysia-(Mudah))
  - [Hatta (Sederhana)](#Hatta-(Sederhana))

- [**TUGASAN SAMPINGAN (REVERSE ENGINEERING)**](#TUGASAN-SAMPINGAN-(REVERSE-ENGINEERING))
  - [Sarawak](#sarawak)
 
- [**TUGASAN KHAS : KENALI PENAJA**](#TUGASAN-KHAS-:-KENALI-PENAJA)
  - [YAYASAN DIGITAL MALAYSIA](#YAYASAN-DIGITAL-MALAYSIA)
  - [RE:HACK](#RE:HACK)
  - [TENANG KOMUNITI](#TENANG-KOMUNITI)
  - [ASK PENTEST](#ASK-PENTEST)
  - [SCAMGATE](#SCAMGATE)-->
 
---------------------------------------------------------------------------

## TUGASAN UTAMA : WARKAH UNTUK PERWIRA
- ### Tugasan I : Seruan Perwira

![tugasan1](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/TUGASAN%20UTAMA/Tugasan%20I/1.png?raw=true)

Untuk tugasan I, kita dibekalkan dengan satu [pautan](https://www.youtube.com/watch?v=DFBNEsKJW6I) Youtube yang bertajuk ```SERANGAN SIBER ITSLOKI```.

![itsloki](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/TUGASAN%20UTAMA/Tugasan%20I/Screenshot%202023-08-28%20185632.png?raw=true)

Seperti yang dapat kita lihat di deskripsi video, terdapat pautan lain yang membawa kita ke laman sesawang Mediafire.

```https://www.mediafire.com/file/oar5si2djkthe0m/Chal_1_-_Pahlawan_BS.zip/file```

Selepas memuat turun dan mengekstrak fail yang diberikan, kita disapa dengan fail EML yang bertajuk aneh, mungkin morse code?

![eml](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/TUGASAN%20UTAMA/Tugasan%20I/Screenshot%202023-08-28%20190505.png?raw=true)

Fail EML adalah fail bagi emel yang telah disimpan, maka kita boleh mengakses fail tersebut menggunakan aplikasi emel.

![emel](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/TUGASAN%20UTAMA/Tugasan%20I/Screenshot%202023-08-28%20191243.png?raw=true)

Isi email tersebut adalah kata-kata dalam bentuk morse code dan satu fail ```attachments.zip```.
Menggunakan morse code decoder, Morse code yang tertera bermaksud :

```REMEMBER OUR SECRET``` dan ```INGATLAH 4 DIGIT KOD RAHSIA KITA```

Fail yang diberikan memerlukan kata laluan untuk diakses. Berdasarkan emel, kata laluan tersebut adalah dalam bentuk 4 digit kod rahsia.

Sebagai perwira yang mempunyai semangat patriotik yang tinggi, tekaan saya bagi kata laluan 4 digit tersebut adalah ```3108```.



![flag1](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/TUGASAN%20UTAMA/Tugasan%20I/Screenshot%202023-08-28%20193534.png?raw=true)

```kata laluan : 3108```

Fail yang diekstrak mengandungi satu text file dan satu gambar.

```Bendera : 3108{1E2A3C68CC5C0207886EDE403EEF230DC7C0FBD0}```

- ### Tugasan II : Tali Barut
![tugasan2](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/TUGASAN%20UTAMA/Tugasan%20II/2.png?raw=true)

Tugasan II menyatakan ahli ITSLOKI mempunyai akaun media sosial mereka tersendiri.

Disebabkan Tugasan II merupakan kesinambungan Tugasan I, mungkin kita boleh mencari petunjuk dari fail yang telah diekstrak sebelum ini.

![godam](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/TUGASAN%20UTAMA/Tugasan%20II/image.jpeg?raw=true)

Terdapat beberapa nama ahli ITSLOKI yang tertera dalam gambar yang diperoleh.

Selepas percubaan OSINT kesemua nama di beberapa media sosial, ```p3tualang``` didapati mempunyai akaun media sosial [TikTok](https://www.tiktok.com/@p3tualang1337).

Terdapat pautan discord pada satu kiriman di akaun TikTok p3tualang.

![TIKTOK](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/TUGASAN%20UTAMA/Tugasan%20II/Screenshot%202023-08-28%20202708.png?raw=true)

```https://discord.gg/4SudntVNer```

Pautan tersebut membawa kita ke discord server p3tualang yang mengandungi pelbagai maklumat.

Selepas mengimbas beberapa maklumat, salah satu yang terlihat meragukan dan berpotensi menjadi bendera adalah teks-teks berikut :

```baabbaaaaaaabbbabbababaaaaaaaaaabbb abbbbaabaabaaabbabbaabaaabaaabaaaaa! aaaaaabbabaaabbaaaaa baabbaabaaababbaaaaaaabbb abbaaaabaaabbababaabbabaaabbaaabbbbaaaaaabaaa abaabaaaaababbaaaaaaabbbbaaaaaabbab. 31```

```08{baaba3abbabbaabb14baabaaaaaa_abbbb3ababaaaaaa}. abaaabaabbbaabaababbabbbaababaabaaa aabbababaaabbabaaaaa aaaba2 babaaabbabbaabbbabaaababa abbaaaabaaabbabbbaaaaabaabaaabaaaaaabbabaabba abbaaaaaaaababbaaaaabbaaabaabaabaaaaaaaa. aaabaaaaaabaaababaaa aabaaabbabaaababaaabbba```

```aaabbbbbaabbaabaaaaabb baabbaabaababbbbaabb aaabbababbabbaa baabaaabaabaaabbababaabaabaaab aaabbabaaabaabaaaabaabbbabaaabaaabb abaaabaabbbaabaababbabbbaababaabaaa aaabbaaaaaabbab baabaaabaabaaabaaaaaabbabaabba baabaaabaabaaabbababaabaabaaab aaaba2 abbaaaabaabaaabaabaaababaaaaaa! -baabaaaaaaabbaaaaaabaaaaabaabbaabbbaaaaaabbab```

Untuk menentukan teks ini berbentuk apa, kita boleh menggunakan [cipher identifier](https://www.dcode.fr/cipher-identifier)

Teks ini adalah dalam bentuk [Baconian Cipher](https://www.dcode.fr/bacon-cipher), decode dan kita akan peroleh petikan berikut :

```TAHNIAH PERWIRA ANDA TELAH MENJUMPAI JAWAPAN. 3108{S3NT14SA_P3KA}. ITSLOKI CUBA UNTUK MENYERANG MALAYSIA. CARI ENCRYPTED TEXT DLM SERVER DISCORD ITSLOKI DAN SERANG SERVER MEREKA! -SAMBATHAN```

```Bendera : 3108{S3NT14SA_P3KA}```

- ### Tugasan III : Pangkalan Gelap
  ![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/TUGASAN%20UTAMA/Tugasan%20III/3.png?raw=true)
