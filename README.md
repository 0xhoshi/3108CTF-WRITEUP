![PERTEMUANKAPISTA3](https://github.com/0xhoshi/3108CTF-WRITEUP/assets/68049551/30c0f7cb-641f-42d1-baa5-2940fcb08bf3)# WRITEUP-3108CTF
---------------------------------------------------------------------------
## __KATEGORI__

- [**TUGASAN UTAMA : WARKAH UNTUK PERWIRA**](#TUGASAN-UTAMA--WARKAH-UNTUK-PERWIRA)
  - [Tugasan I : Seruan Perwira](#Tugasan-I--Seruan-Perwira)
  - [Tugasan II : Tali Barut](#Tugasan-II--Tali-Barut)
  - [Tugasan III : Pangkalan Gelap](#Tugasan-III--Pangkalan-Gelap)

- [**TUGASAN SAMPINGAN (OSINT)**](#TUGASAN-SAMPINGAN-OSINT)
  - [Pertemuan Kapista : Babak I (Mudah)](#Pertemuan-Kapista--Babak-I-Mudah)
  - [Pertemuan Kapista : Babak II (Mudah)](#Pertemuan-Kapista--Babak-II-Mudah)
  - [Pertemuan Kapista : Finale (Mudah)](#Pertemuan-Kapista--Finale-Mudah)
  - [Hero Melayu (Mudah)](#Hero-Melayu-Mudah)
  - [Kisah Lama (Mudah)](#Kisah-Lama-Mudah)
  - [Mesej Dalam Botol (Sederhana)](#Mesej-Dalam-Botol-Sederhana)
  - [Saya Di Mana (Mudah)](#Saya-Di-Mana-Mudah)
 
<!-- [**TUGASAN SAMPINGAN (WEB)**](#TUGASAN-SAMPINGAN-(WEB))
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

Bagi Tugasan III, maklumat yang diberikan adalah ITSLOKI mempunyai laman web dan objektif kita adalah untuk menyelinap masuk ke dalam sistem mereka.

Kembali kepada maklumat yang terdapat di dalam server discord p3tualang, antara yang kelihatan menarik adalah baris-baris kod berikut :

```
#include <stdio.h>

int main() {
    int part1[] = { 122, 120, 226, 140, 130, 110, 103, 105, 113, 115, 107, 52 };
    int part2[] = { 105, 117, 115, 53, 112, 120, 53, 57, 55, 54, 62, 105, 122, 108, 125 };
    int part3[] = { 103, 120, 113, 103, 110, 123, 116, 122, 123, 113, 118, 107, 120, 125, 111, 120, 103 };

    char finalValue[50]; 

    int = 0;
    for (int i = 0; i < sizeof(xxxx) / sizeof(part1[0]); i++) {
        finalValue[index++] = (char)part1[i];
    }
    for (int 0 = 0; i < sizeof(part2) / sizeof(part2[0]); i++) {
       
    }
    for (int i = 0; i < sizeof(part3) / sizeof(part3[0]); i++) {
        finalValue[index++];


    printf("Final value: %s\n", finalValue);

    return 0;
}
```

Terdapat beberapa kesalahan pada kod ini, perbetulkan untuk menerima output :

```
#include <stdio.h>
index = 0;
int main() {
    int part1[] = { 122, 120, 226, 140, 130, 110, 103, 105, 113, 115, 107, 52 };
    int part2[] = { 105, 117, 115, 53, 112, 120, 53, 57, 55, 54, 62, 105, 122, 108, 125 };
    int part3[] = { 103, 120, 113, 103, 110, 123, 116, 122, 123, 113, 118, 107, 120, 125, 111, 120, 103 };

    char finalValue[50];
    

    for (int i = 0; i < sizeof(part1) / sizeof(part1[0]); i++) {
        finalValue[index++] = (char)part1[i];
    }
    for (int i = 0; i < sizeof(part2) / sizeof(part2[0]); i++) {
        finalValue[index++] = (char)part2[i];
    }
    for (int i = 0; i < sizeof(part3) / sizeof(part3[0]); i++) {
        finalValue[index++] = (char)part3[i];
    }


    printf("Final value: %s\n", finalValue);

    return 0;
}
```

Output yang diterima adalah ```zx⌂ngiqsk4ius5px5976>izl}gxqgn{tz{qvkx}oxg@``` yang merupakan [ROT Cipher](https://www.dcode.fr/rot-cipher).

Decode output tersebut dan kita akan peroleh pautan ke laman sesawang Tryhackme :

```tryhackme.com/jr/3108ctfwarkahuntukperwira```

Ini bermakna kita perlu bermain dengan box yang diberi, mari mulakan dengan port scanning.

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/PENAJA/Screenshot%202023-08-28%20235814.png?raw=true)

Keputusan menunjukkan 2 port yang terbuka, http/80 dan ssh/22.

http/80 menandakan wujudnya laman sesawang, kita teruskan dengan menjalankan directory scanning.

Direktori ```/note.txt``` kelihatan menarik, mari kita lihat isi kandungannya.

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/PENAJA/Screenshot%202023-08-28%20235814.png?raw=true)

Berdasarkan maklumat di direktori tersebut, kita perlu ke domain ```itsloki.thm``` untuk mengetahui lebih lanjut.

masukkan ip dan domain ke dalam /etc/hosts lalu kita dapat akses ke laman sesawang itsloki.thm.

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/PENAJA/Screenshot%202023-08-28%20235814.png?raw=true)

Tidak banyak maklumat yang dapat diperoleh di laman sesawang ini.

Tetapi, maklumat yang kelihatan menarik adalah : 

1) Nama pengarang iaitu ```rok14h```

2) Laman sesawang ini menggunakan ```textpattern cms```

3) Komen yang ditinggalkan di source code, iaitu ```komen```

Kerana laman sesawang ini menggunakan ```textpattern cms```, pastinya terdapat direktori log masuk bagi pengarang.

Jalankan directory scanning pada domain dan kita peroleh direktori ```/textpattern```

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/PENAJA/Screenshot%202023-08-28%20235814.png?raw=true)

Memasukkan ```Rok14h``` sebagai nama pengguna dan ```komen``` sebagai kata laluan akan memberi kita akses sebagai admin laman sesawang.

Untuk execute os command ke dalam machine mereka, muat naik reverse shell di bahagian "files".

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/PENAJA/Screenshot%202023-08-28%20235814.png?raw=true)

Dengan ini, kita telahpun mempunyai akses dan hak untuk execute command di dalam machine mereka.

Untuk mencari bendera, saya gunakan command ```find / -name "*.txt"``` dan akhirnya kita peroleh bendera ketiga.

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/PENAJA/Screenshot%202023-08-28%20235814.png?raw=true)

```Bendera : 3108{S3NT14SA_P3KA}```


## TUGASAN SAMPINGAN (OSINT)
- ### Pertemuan Kapista : Babak I (Mudah)

![kapista](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Pertemuan%20Kapista%20I/PERTEMUANKAPISTA1.png?raw=true)

Kita dibekalkan dengan tapak mula yang berupa pautan Youtube bertajuk ```Misi 3108```.

![kapistayoutube](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Pertemuan%20Kapista%20I/Screenshot%202023-08-28%20230501.png?raw=true)

Isi kandungan video tersebut mengarahkan kita untuk menyiasat ```madah4arjuna``` di sosial media X atau lebih dikenali sebagai Twitter.

Cari ```madah4arjuna``` di X dan kita akan peroleh bendera di salah satu kirimannya.

![kapistaflag1](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Pertemuan%20Kapista%20I/photo_2023-08-28_23-07-03.jpg?raw=true)

```Bendera : 3108{angka_keramat}```

- ### Pertemuan Kapista : Babak II (Mudah)

![kapista2](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Pertemuan%20Kapista%20II/PERTEMUANKAPISTA2.png?raw=true)

Tugasan ini merupakan sambungan daripada Pertemuan Kapista : Babak I, intel yang dimaksudkan pasti berada di akaun media sosial yang sama.

Dua kiriman daripada ```madah4arjuna``` kelihatan mencurigakan kerana mempunyai turutan nombor yang tidak dapat difahami.

![kapista21](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Pertemuan%20Kapista%20II/photo_2023-08-28_23-21-02.jpg?raw=true)

![kapista22](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Pertemuan%20Kapista%20II/photo_2023-08-28_23-21-11.jpg?raw=true)

Turutan nombor tersebut adalah [Multi-Tap Phone Cipher](https://www.dcode.fr/multitap-abc-cipher), gabungkan dua turutan nombor itu dan decode.

Hasil decode ialah ```SABAH TANGO HASSAN TELEGRAM LANANG KUSRANI```

Pergi ke Telegram Lanang Kusrani dan kita akan peroleh bendera.

![kapistaflag2](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Pertemuan%20Kapista%20II/photo_2023-08-28_23-29-26.jpg?raw=true)

```Bendera : 3108{Hassan_Tapa}```

Kacak juga Hassan Tapa, Tidak seperti kelakuannya yang jelik.

- ## Pertemuan Kapista : Finale (Mudah)

![kapista3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Pertemuan%20Kapista%20Finale/PERTEMUANKAPISTA3.png?raw=true)

Tibalah kita ke babak terakhir untuk Pertemuan Kapista.

Pergi ke Instagram Hassan Tapa seperti yang tertera di dalam Telegram.

![kapistains](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Pertemuan%20Kapista%20Finale/Screenshot%202023-08-28%20233833.png?raw=true)

Satu kiriman daripada Hassan Tapa mempunyai teks berbentuk [BASE64](https://www.base64decode.org/) di dalam gambar.

![kapistains1](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Pertemuan%20Kapista%20Finale/Screenshot%202023-08-28%20234012.png?raw=true)

Decode teks tersebut dan kita peroleh satu pautan :

```https://pastebin.com/wvaxxE0b```

Malang sekali, kita memerlukan kata laluan untuk mendapat akses.

Cari petunjuk untuk kata laluan di akaun Instagram, kapsyen kiriman berikut kelihatan janggal :

![kapistains2](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Pertemuan%20Kapista%20Finale/photo_2023-08-28_23-42-07.jpg?raw=true)

Ubah tarikh tersebut kepada ```31082023``` dan gunakan sebagai kata laluan.

![kapistapb](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Pertemuan%20Kapista%20Finale/Screenshot%202023-08-28%20235438.png?raw=true)

```Bendera : 3108{Pulau_Mabul}```

- ### Hero Melayu (Mudah)

![heromelayu](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Hero%20Melayu%20(Mudah)/HEROMELAYU.png?raw=true)

Telah disertakan dua hashtag di dalam deskripsi tugasan ini : ```#3108ctf #pempengaruhsiber```

Cari dua hashtag ini di media sosial Tiktok lalu akan muncul akaun tersebut :

![heromelayu1](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Hero%20Melayu%20(Mudah)/Screenshot%202023-08-29%20001252.png?raw=true)

Lihat satu persatu kiriman di akaun tersebut dan kita akan peroleh bendera.

![heromelayu1](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Hero%20Melayu%20(Mudah)/Screenshot%202023-08-29%20001406.png?raw=true)

```Bendera : 3108{m3d14_m4ss4l4h}```

- ### Kisah Lama (Mudah)

![kisahlama](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Kisah%20Lama%20(Mudah)/KISAHLAMA.png?raw=true)

Kita dibekalkan dengan satu pautan yang telah dibuang kandungannya :

![kisahlama](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Kisah%20Lama%20(Mudah)/Screenshot%202023-08-29%20002152.png?raw=true)

Gunakan [Wayback Machine](https://archive.org/web/) untuk mengakses kandungan yang telah dibuang.

![kisahlama](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Kisah%20Lama%20(Mudah)/Screenshot%202023-08-29%20002247.png?raw=true)

![kisahlama](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Kisah%20Lama%20(Mudah)/Screenshot%202023-08-29%20002337.png?raw=true)

```Bendera : 3108{r3d4_d4r1_kis4h_l4m4}```

- ## Mesej Dalam Botol (Sederhana)

![mesej](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Mesej%20Dalam%20Botol%20(Sederhana)/MESEJDALAMBOTOL.png?raw=true)

Kita diberi satu gambar dan satu fail rar yang memerlukan kata laluan.

Cari gambar tersebut di [Google Images](https://www.google.com/imghp?hl=en) untuk memperoleh maklumat tentang bahtera tersebut.

![mesej](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Mesej%20Dalam%20Botol%20(Sederhana)/Screenshot%202023-08-29%20003521.png?raw=true)

Bahtera Pertiwi kelihatan sepadan dengan gambar yang dibekalkan.

![mesej](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Mesej%20Dalam%20Botol%20(Sederhana)/Screenshot%202023-08-29%20003633.png?raw=true)

Tahun pembinaannya ialah 2014.

Masukkan ```BAHTERAPERTIWI_2014``` sebagai kata laluan bagi "botol" dan kita akan peroleh gambar berikut :


tulisan yang terdapat di sisi gambar tersebut adalah dalam bentuk [ROT47](https://www.dcode.fr/rot-47-cipher), decode dan peroleh bendera.

```Bendera : 3108{D3W1~K1R4N4}```

- ## Saya Di Mana (Mudah)

![saya di mana](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Saya%20di%20Mana%20(Mudah)/SAYADIMANA.png?raw=true)

![saya di mana](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Saya%20di%20Mana%20(Mudah)/saya_dimana.jpg?raw=true)

Menggunakan maklumat yang diberikan di deskripsi dan di dalam gambar, lokasi yang dimaksudkan ialah ```Dataran Pahlawan Melaka```.
