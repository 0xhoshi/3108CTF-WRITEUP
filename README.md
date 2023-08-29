# WRITEUP-3108CTF
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
 
- [**TUGASAN SAMPINGAN (WEB)**](#TUGASAN-SAMPINGAN-WEB)
  - [Lemah (Mudah)](#Lemah-Mudah)
  - [Wantujus (Mudah)](#Wantujus-Mudah)
  - [Wantusom (Sederhana)](#Wantusom-Sederhana)
  - [Pantun Pantul (Sederhana)](#Pantun-Pantul-Sederhana) 

- [**TUGASAN SAMPINGAN (CRYPTOGRAPHY)**](#TUGASAN-SAMPINGAN-CRYPTOGRAPHY)
  - [Nasihat (Mudah)](#Nasihat-Mudah)
  - [Selamat Malam (Sederhana)](#Selamat-Malam-Sederhana)
  - [Keretapi Tanah Melayu 🚂 (Mudah)](#Keretapi-Tanah-Melayu--Mudah)
  - [Jerebu (Sederhana)](#Jerebu-Sederhana)
  - [1957bit (Sederhana)](#1957bit-Sederhana)

- [**TUGASAN SAMPINGAN (MISC)**](#TUGASAN-SAMPINGAN-MISC)
  - [Mencari Rahsia Si Dia (Mudah)](#Mencari-Rahsia-Si-Dia-Mudah)
  - [Pesan Tentang Bicara (Sederhana)](#Pesan-Tentang-Bicara-Sederhana)
  - [3108 CTF Town (Sederhana)](#3108-CTF-Town-Sederhana)
  - [Nasi Lemak 1 Juta (Mudah)](#Nasi-Lemak-1-Juta-Mudah)
 
<!-- [**TUGASAN SAMPINGAN (STEGA)**](#TUGASAN-SAMPINGAN-(STEGA))
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

3) Komen yang ditinggalkan di source code, iaitu ```rok14h@l33t```

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/PENAJA/Screenshot%202023-08-28%20235814.png?raw=true)

Kerana laman sesawang ini menggunakan ```textpattern cms```, pastinya terdapat direktori log masuk bagi pengarang.

Jalankan directory scanning pada domain dan kita peroleh direktori ```/textpattern```

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/PENAJA/Screenshot%202023-08-28%20235814.png?raw=true)

Memasukkan ```rok14h``` sebagai nama pengguna dan ```rok14h@l33t``` sebagai kata laluan akan memberi kita akses sebagai admin laman sesawang.

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

- ### Pertemuan Kapista : Finale (Mudah)

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

- ### Mesej Dalam Botol (Sederhana)

![mesej](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Mesej%20Dalam%20Botol%20(Sederhana)/MESEJDALAMBOTOL.png?raw=true)

Kita diberi satu gambar dan satu fail rar yang memerlukan kata laluan.

Cari gambar tersebut di [Google Images](https://www.google.com/imghp?hl=en) untuk memperoleh maklumat tentang bahtera tersebut.

![mesej](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Mesej%20Dalam%20Botol%20(Sederhana)/Screenshot%202023-08-29%20003521.png?raw=true)

Bahtera Pertiwi kelihatan sepadan dengan gambar yang dibekalkan.

![mesej](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Mesej%20Dalam%20Botol%20(Sederhana)/Screenshot%202023-08-29%20003633.png?raw=true)

Tahun pembinaannya ialah 2014.

Masukkan ```BAHTERAPERTIWI_2014``` sebagai kata laluan bagi "botol" dan kita akan peroleh gambar berikut :

![mesej](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Mesej%20Dalam%20Botol%20(Sederhana)/Screenshot%202023-08-29%20003954.png?raw=true)

tulisan yang terdapat di sisi gambar tersebut adalah dalam bentuk [ROT47](https://www.dcode.fr/rot-47-cipher), decode dan peroleh bendera.

```Bendera : 3108{D3W1~K1R4N4}```

- ### Saya Di Mana (Mudah)

![saya di mana](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Saya%20di%20Mana%20(Mudah)/SAYADIMANA.png?raw=true)

![saya di mana](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Saya%20di%20Mana%20(Mudah)/saya_dimana.jpg?raw=true)

Menggunakan maklumat yang diberikan di deskripsi dan di dalam gambar, lokasi yang dimaksudkan ialah ```Dataran Pahlawan Melaka```.

Cari ```Dataran Pahlawan Melaka``` di Google Maps dan lihat "Reviews" terkini.

![saya di mana](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Saya%20di%20Mana%20(Mudah)/Screenshot%202023-08-29%20005351.png?raw=true)

![saya di mana](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/OSINT/Saya%20di%20Mana%20(Mudah)/Screenshot%202023-08-29%20005428.png?raw=true)

```Bendera : 3108{d4tar4n_p4hl4w4n}```

## TUGASAN SAMPINGAN (WEB)

- ### Lemah (Mudah)

![lemah](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/WEB/Lemah%20(Mudah)/LEMAH.png?raw=true)

Kita dibekalkan dengan satu pautan ```lemah.bahterasiber.my```.

Pergi ke pautan ini dan kita akan disapa dengan laman log masuk.

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/WEB/Lemah%20(Mudah)/Screenshot%202023-08-29%20210907.png?raw=true)

Lihat source laman ini dan lihat kod untuk ```auth.js```.

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/WEB/Lemah%20(Mudah)/Screenshot%202023-08-29%20210950.png?raw=true)

```
$(".c_submit").click(function(event) {
  event.preventDefault();
  var u = $("#cuser").val();
  var p = $("#cpass").val();
  if (u === "Jati" && p === String.fromCharCode(51,49,48,56,123,112,52,115,115,119,48,114,100,95,108,51,109,52,104,33,125)) {
    if (document.location.href.indexOf("?p=") === -1) {
      document.location = document.location.href + "?p=" + p;
    }
  } else {
    $("#cresponse").html("<div class='alert alert-danger'>Wrong password sorry.</div>");
  }
});
```
Kod ini hanya menerima input dengan nama pengguna ```Jati``` dan kata laluan ```String.fromCharCode(51,49,48,56,123,112,52,115,115,119,48,114,100,95,108,51,109,52,104,33,125)```

Run function ini dan peroleh bendera.

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/WEB/Lemah%20(Mudah)/Screenshot%202023-08-29%20211021.png?raw=true)

```Bendera : 3108{p4ssw0rd_l3m4h!}```

- ### Wantujus (Mudah)

![lemah](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/WEB/Lemah%20(Mudah)/LEMAH.png?raw=true)

pautan yang diberikan membawa kita ke laman berikut :

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/WEB/Wantujus%20(Mudah)/Screenshot%202023-08-29%20211204.png?raw=true)

Kalahkan Pakwan dengan memilih mana-mana antara tiga pilihan sehingga menang 10 kali.

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/WEB/Wantujus%20(Mudah)/Screenshot%202023-08-29%20211244.png?raw=true)

Lihat biskut yang diberi menggunakan [Cookie Editor](https://chrome.google.com/webstore/detail/cookie-editor/hlkenndednhfkekhgcdicdfddnkalmdm).

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/WEB/Wantujus%20(Mudah)/Screenshot%202023-08-29%20211403.png?raw=true)

Biskut yang diberi adalah dalam bentuk [BASE64](https://www.base64decode.org/), decode dan peroleh bendera.

```Bendera : 3108{biskut_marie}```

- ### Wantusom (Sederhana)

![lemah](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/WEB/Wantusom%20(Sederhana)/WANTUSOM.png?raw=true)

laman ini saman seperti Wantujus, tetapi kali ini kemenangan kita mustahil untuk melebihi 9 kali.

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/WEB/Wantusom%20(Sederhana)/Screenshot%202023-08-29%20213404.png?raw=true)

Lihat source untuk lihat bagaimana laman ini berfungsi.

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/WEB/Wantusom%20(Sederhana)/Screenshot%202023-08-29%20214025.png?raw=true)

tukar nilai 9 ke nombor yang lebih besar pada baris kod ini untuk menang dan peroleh biskut.

```
 if (winCount === 9) {
    computerChoice = getUnbeatableChoice(playerChoice);
  }
```
↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓↓
```
 if (winCount === 11) {
    computerChoice = getUnbeatableChoice(playerChoice);
  }
```
![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/WEB/Wantusom%20(Sederhana)/Screenshot%202023-08-29%20214744.png?raw=true)

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/WEB/Wantusom%20(Sederhana)/Screenshot%202023-08-29%20214756.png?raw=true)

Biskut adalah dalam bentuk [BASE64](https://www.base64decode.org/), decode dan peroleh bendera.

```Bendera : 3108{biskut_tiger}```

- ### Pantun Pantul (Sederhana)

![lpantun](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/WEB/Pantun%20Pantul%20(Sederhana)/PANTUNPANTUL.png?raw=true)

Laman ini meminta kita untuk melengkapkan pantun yang diberi.

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/WEB/Pantun%20Pantul%20(Sederhana)/Screenshot%202023-08-29%20220305.png?raw=true)

Lihat source untuk mengetahui lebih lanjut tentang laman ini.

fungsi ```bendera()``` ini akan memberikan kita bendera apabila digunakan.

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/WEB/Pantun%20Pantul%20(Sederhana)/Screenshot%202023-08-29%20220434.png?raw=true)

Run function ```bendera()``` dan peroleh bendera.

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/WEB/Pantun%20Pantul%20(Sederhana)/Screenshot%202023-08-29%20220458.png?raw=true)

```Bendera : 3108{pantun1337kerat}```

## TUGASAN SAMPINGAN (CRYPTOGRAPHY)

- ### Nasihat (Mudah)

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/CRYPTO/Nasihat%20(Mudah)/NASIHAT.png?raw=true)

Tugasan ini memberikan kita dua fail untuk dimuat turun, salah satunya merupakan fail yang ditulis dalam bahasa pengaturcaraan python.

Muat turun dua fail ini dalam satu direktori dan lihat kod python yang diberi.

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/CRYPTO/Nasihat%20(Mudah)/Screenshot%202023-08-29%20223123.png?raw=true)

Run kod ini dan masukkan kata laluan seperti yang tertera di dalam kod.

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/CRYPTO/Nasihat%20(Mudah)/Screenshot%202023-08-29%20223323.png?raw=true)

```Bendera : 3108{rukun_n3g4r4_adlh_p3nt!ng}```

- ### Selamat Malam (Sederhana)

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/CRYPTO/Selamat%20Malam%20(Sederhana)/SELAMATMALAM.png?raw=true)

Kita dibekalkan dengan satu teks fail yang isinya adalah seperti berikut :

```
<Senandung Lena>

nzhrs wzozn rmtzgzmpf, dzqzs gzmtrhnf hzzg pf yvipzgz
zpf gzppzm k3imzs nvny1zipzmnf kvitr
hzzg hvn0z yzbzmtzm 8znkri nvnfwzipzm hrmzinf
pzf pzgz pvkzwzpf, qzmtzm grmttzopzmpf hvmwrirzm wr hrmr
mznfm nzozn rmr, hvnfzmbz gvozs yrmzhz wzm kvitr


gfgfkozs Nzgznf
hzmt gvqZ nzOzn zpzm gryz
pzf zpzm yzrp-yzrp hzqZ
grwzp zwz Bzmt yzpzo nvmbzprgrnf Hvpzizmt
hzzg wzgzmtmbz pvovnzbzi uzqzi
pzf wzm zpf zpzm hvoznzg


qzmtzm pzf yvizmR nvorszg pvofzi qvmwvoZnf
hzbZmt, hvnfzmbz hvwzmt Nzizp gviyzpzi
kvizmt wr ofzi tzkfiZ zpzM gvifh yvitlozp
kvtzmtozs oztf kvmtzmgzi ovmz rmr
pvmwzgrkfm hzzg hvmzmwfmt rmr ovmbzk


kvqznpzm nzgznf
hzmt gvqz nzozn zpzm gryz
pzf zpzm yzrp-yzrp hzqz
grwzp zwz bzmt yzpzo nvmbzprgrnf hvpzizmt
hzzg gviyrgmbz ilmz uzqzi
prgz kzhgr zpzm hvqzsgviz
```

teks yang diberikan adalah dalam bentuk [Atbash Cipher](https://www.dcode.fr/atbash-cipher), decode dan kita akan peroleh teks berikut :

```
masih dalam ingatanku, wajah tangismu saat ku berkata
aku takkan p3rnah memb1arkanmu pergi
saat sem0a bayangan 8ampir memudarkan sinarmu
kau kata kepadaku, jangan tinggalkanku sendirian di sini
namun malam ini, semuanya telah binasa dan pergi


tutuplah Matamu
sang tejA maLam akan tiba
kau akan baik-baik sajA
tidak ada Yang bakal menyakitimu Sekarang
saat datangnya kelemayar fajar
kau dan aku akan selamat


jangan kau beranI melihat keluar jendelAmu
sayAng, semuanya sedang Marak terbakar
perang di luar gapurA akaN terus bergolak
peganglah lagu pengantar lena ini
kendatipun saat senandung ini lenyap


pejamkan matamu
sang teja malam akan tiba
kau akan baik-baik saja
tidak ada yang bakal menyakitimu sekarang
saat terbitnya rona fajar
kita pasti akan sejahtera
```
Asingkan nombor dan huruf besar daripada teks tersebut dan gabungkan untuk peroleh bendera.

```Bendera : 3108{MALASIAAMAN}```

- ### Keretapi Tanah Melayu 🚂 (Mudah)

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/CRYPTO/Keretapi%20Tanah%20Melayu%20(Mudah)/KERETAPI.png?raw=true)

Tugasan ini juga memberikan kita satu fail teks yang kandungannya adalah seperti berikut :

```
Sistem kereta api di Tanah Melayu bermula pada 1 Jun 1885 apabila jajaran keretapi yang pertama di Tanah Melayu sepanjang 8.25 batu (13.28 km) antara Taiping dengan Port Weld dibuka secara rasmi. Dibina menggunakan tolok meter, laluan ini dibina untuk mengangkut bijih timah daripada lombong-lombong di Taiping ke laut di Port Weld. Landasan di laluan ini pernah diangkut untuk pembinaan Landasan Kereta Api Burma semasa pendudukan Jepun di Tanah Melayu tetapi diganti semula sppraeh·e·baanr··p-tlbr·uktpe··aemgiul·i·aeut·uktpebaaanaKam·gb·a·te8·uKt·gUgebP·k)niadu·1anlAnpR·gb·ah1,l·lurw·gb·aNm·2aanau·tmniad·a8·e·ulaeaiisuanaaenraatn03{qlzulvu1u0pnpuy=eea·eeagnbrki.Slpspmuanlla·eeaaiTiigPr·ed·eeaalla·eeaaibbsdntdkbrabn·anmnu·isktrTnhMly.naalla·eeaaitreu·dlhlla·ln-ul·upryn·iuapd·5Spebr18,lla·eeaiSne·jn·Srma-otDcsn·agdbk·aaJli19,lla·eu·no-aa·odyn·iuapd·au·83·aunKaaLmu-aagyn·iuapd··oebr19,dnlla·riBktMraa·agdbk·aa1Jli19.Ksmalla-aunkrt·p·n·iabnknatr·ridna·eebnpd·au·93·18aVY5bFZlZdclcFZhaFYFdRbVZJcVZla=}lspn·areaek·uktpanoW,bpanr··aai·sul·cdeaa·aAranr··sta·uKgaLuadka1em·6anrpuio(enrioy·up·a8·uTksThaadkatn9lau·pRnadka7ve8··uP-iejy·up·u·9euanl·eaidmg·aP·gSm·ah1.0HWWGWmm2mmWmX2GQ
```
Teks yang kelihatan mengarut tersebut adalah dalam bentuk [Rail Fence Cipher](https://www.boxentriq.com/code-breaking/rail-fence-cipher), decode dan kita akan peroleh teks seperti berikut :

```
selepas·peperangan·berakhir.·Selepas·pembukaan·laluan·kereta·api·Taiping-Port·Weld,·beberapa·laluan·kereta·api·bebas·dan·tidak·bersambung·lain·muncul·di·sekitar·Tanah·Melayu.Antara·laluan·kereta·api·tersebut·adalah·laluan·Klang-Kuala·Lumpur·yang·dibuka·pada·15·September·1886,·laluan·Keretapi·Sungei·Ujong·(Seremban-Port·Dickson)·yang·dibuka·pada·Julai·1891,·laluan·Teluk·Anson-Tapah·Road·yang·dibuka·pada·tahun·1893,·laluan·Kuala·Lumpur-Rawang·yang·dibuka·pada·7·November·1892,·dan·laluan·Prai-Bukit·Mertajam·yang·dibuka·pada·1·Julai·1899.·Kesemua·laluan-laluan·kereta·api·ini·disambungkan·antara·Prai·dengan·Seremban·pada·tahun·1903.·3108{aHVqYW5lbWFzZGluZWdlcmlvcmFuZ2h1amFuYmF0dWRpbmVnZXJpc2VuZGlyaQ==}
```

```Bendera : 3108{aHVqYW5lbWFzZGluZWdlcmlvcmFuZ2h1amFuYmF0dWRpbmVnZXJpc2VuZGlyaQ==}```

- ### Jerebu (Sederhana)

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/CRYPTO/Jerebu%20(Sederhana)/JEREBU.png?raw=true)

Tugasan ini memberikan kita satu gambar yang terdiri daripada "Music Sheet".

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/CRYPTO/Jerebu%20(Sederhana)/Jerebu.png?raw=true)

Ini merupakan [Music Sheet Cipher](https://www.dcode.fr/music-sheet-cipher), melihat kepada bilangan karakter yang perlu di-decode, tidaklah rajin untuk saya decode satu persatu.

Maka, saya cari "notes-notes" yang kelihatan lain daripada yang lain berpotensi menjadi nombor format bendera```3108```.

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/CRYPTO/Jerebu%20(Sederhana)/21.png?raw=true)

"notes" di atas terlihat janggal, decode dan kita akan peroleh bendera.

```Bendera : 3108{P3RJ4NJNASEAN}```

- ### 1957bit (Sederhana)

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/CRYPTO/Jerebu%20(Sederhana)/JEREBU.png?raw=true)

Kita diberikan satu fail teks yang berbentuk binary seperti berikut :

```
01111100 01011100 01000111 01010011 01010100 01010010 01010100 00010111 01011010 01010000 01000001 01010110 00010001 01010001 01010100 01000101 01011000 00011001 01011100 01011001 01011000 00011001 01010111 01000010 01011010 01011000 01011011 00010111 01011010 01011100 01000111 01010110 01011111 01011000 00010101 01011001 01010000 01001010 01011100 01010101 00010001 01011101 01011100 01010110 01011111 01001101 01010100 01000101 01010000 00011001 01000110 01011110 01010111 01011000 01000111 00010111 01010101 01011000 01011011 00010111 01000010 01011000 01000001 01000010 00011101 00110011 01100001 01010010 01000101 01011000 01000101 01011110 00010001 01010010 01010000 01000101 01010000 01010111 01010100 00010111 01000001 01011100 01000111 01011101 01000100 01011000 01011011 01010000 01010000 01010111 00010101 01000111 01010100 01001011 01000010 01011110 01000011 01011000 00010101 01001110 01010000 01010111 01010010 00010111 01011011 01010000 01000010 01010110 00010001 01011101 01010100 01011001 00010001 01010001 01010100 01000011 01011000 01010111 01001100 01010110 00010001 01011011 01010000 01000101 01000010 01011000 01000001 01000010 00011111 00110011 01100110 01010010 01011101 01011000 01011000 01010110 01000101 00011001 01011000 01010010 01011111 01000000 01010100 01011010 01010011 01001100 01000001 00010111 01011001 01011000 01000111 01011110 00010001 01010010 01010000 01011010 01010100 01001011 01010001 01010010 01011010 01011000 01010100 01011001 00010001 01010010 01010000 00011010 00000111 00001111 00010100 00111101 00000010 00001000 00000101 00001111 01001010 01110100 01100001 00001111 00000010 00001011 01111111 01010001 00000101 01110100 01111000 01100010 01001001 01110010 01110110 01011101 00000100 00001010 01111001 01110100 01011011 01000000 01111110 01101110 01000110 01101000 01101111 01101110 01100111 01011101 01110010 01101111 01001000 01110111 01001111 01101101 01100000 01001100 01111110 01100110 01100010 01111110 01110111 00000000 01010011 01110100 01000000 01111111 01101011 01111111 01010010 01010001 01110011 01001100 00000011 00000011 01010010 01001011 00000010 01100010 01011011 01111101 01011011 01101110 01011011 01011011 01011111 01110110 01101011 01100011 01110010 00001111 01001100
```
[XOR](https://www.dcode.fr/xor-cipher) Binary tersebut dengan kunci ```1957``` dan peroleh binary berikut :

```
01001101 01100101 01110010 01100100 01100101 01101011 01100001 00100000 01101011 01101001 01110100 01100001 00100000 01101000 01100001 01110010 01101001 00100000 01101001 01101110 01101001 00100000 01100010 01110101 01101011 01100001 01101110 00100000 01101011 01100101 01110010 01100001 01101110 01100001 00100000 01101110 01100001 01110011 01101001 01100010 00100000 01100100 01101001 01100001 01101110 01110100 01100001 01110010 01100001 00100000 01110011 01101001 01100110 01100001 01110010 00100000 01100100 01100001 01101110 00100000 01110011 01100001 01110100 01110101 00101100 00001010 01010100 01100101 01110100 01100001 01110000 01101001 00100000 01101011 01100101 01110010 01100001 01101110 01100001 00100000 01110000 01100101 01110010 01101010 01110101 01100001 01101110 01100111 01100001 01101110 00100000 01110000 01100101 01110010 01110111 01101001 01110010 01100001 00100000 01111001 01100001 01101110 01100111 00100000 01101010 01101001 01110111 01100001 00100000 01100100 01100001 01101110 00100000 01101000 01100001 01110100 01101001 01101110 01111001 01100001 00100000 01100010 01100101 01110010 01110011 01100001 01110100 01110101 00101110 00001010 01010011 01100101 01101100 01100001 01101101 01100001 01110100 00100000 01101101 01100101 01101110 01111001 01100001 01101101 01100010 01110101 01110100 00100000 01101000 01100001 01110010 01101001 00100000 01101011 01100101 01101101 01100101 01110010 01100100 01100101 01101011 01100001 01100001 01101110 00100000 01101011 01100101 00101101 00110110 00110110 00100001 00001010 00110011 00110001 00110000 00111000 01111011 01001101 01010100 00111000 00110011 00110010 01001010 01100110 00110100 01001101 01001101 01010101 01111000 01001011 01000011 01101010 00110101 00110011 01001100 01000011 01101010 01111001 01001011 01011001 01110111 01010001 01011010 01011001 01010110 01100100 01000111 01011000 01111001 01001110 01111010 01011010 01010001 01110101 01001011 01010001 01010011 01000111 01000010 00110111 01100010 01001101 01110101 01001000 01011010 01000110 01100111 01100110 01000010 01110101 00110110 00110100 01100011 01110010 00110111 01010101 01101010 01000100 01101110 01011001 01101010 01100010 01101010 01000001 01011010 01011010 01000111 00111000 01111101
```

Decode [Binary](https://cryptii.com/pipes/binary-decoder) yang diperoleh.

```
Merdeka kita hari ini bukan kerana nasib diantara sifar dan satu,
Tetapi kerana perjuangan perwira yang jiwa dan hatinya bersatu.
Selamat menyambut hari kemerdekaan ke-66!
3108{MT832Jf4MMUxKCj53LCjyKYwQZYVdGXyNzZQuKQSGB7bMuHZFgfBu64cr7UjDnYjbjAZZG8}
```

```Bendera : 3108{MT832Jf4MMUxKCj53LCjyKYwQZYVdGXyNzZQuKQSGB7bMuHZFgfBu64cr7UjDnYjbjAZZG8}```

## TUGASAN SAMPINGAN (MISC)

- ### Mencari Rahsia Si Dia (Mudah)

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/MISC/Mencari%20Rahsia%20Si%20Dia%20(Mudah)/MENCARIRAHSIASIDIA.png?raw=true)

Kita diberikan dengan satu teks panjang berbentuk spam :

```
Dear Colleague , This letter was specially selected 
to be sent to you ! We will comply with all removal 
requests . This mail is being sent in compliance with 
Senate bill 1621 ; Title 4 , Section 309 ! Do NOT confuse 
us with Internet scam artists ! Why work for somebody 
else when you can become rich as few as 10 WEEKS . 
Have you ever noticed most everyone has a cellphone 
& most everyone has a cellphone ! Well, now is your 
chance to capitalize on this ! WE will help YOU use 
credit cards on your website and decrease perceived 
waiting time by 140% ! You can begin at absolutely 
no cost to you ! But don't believe us ! Prof Ames of 
Alaska tried us and says "Now I'm rich, Rich, RICH" 
. We assure you that we operate within all applicable 
laws . You will blame yourself forever if you don't 
order now . Sign up a friend and you'll get a discount 
of 40% . Thanks ! Dear Sir or Madam ; This letter was 
specially selected to be sent to you . If you no longer 
wish to receive our publications simply reply with 
a Subject: of "REMOVE" and you will immediately be 
removed from our mailing list ! This mail is being 
sent in compliance with Senate bill 1620 , Title 3 
; Section 302 . This is different than anything else 
you've seen . Why work for somebody else when you can 
become rich in 49 months ! Have you ever noticed people 
will do almost anything to avoid mailing their bills 
& society seems to be moving faster and faster ! Well, 
now is your chance to capitalize on this . We will 
help you decrease perceived waiting time by 150% plus 
SELL MORE . You are guaranteed to succeed because we 
take all the risk ! But don't believe us ! Prof Jones 
who resides in Tennessee tried us and says "Now I'm 
rich many more things are possible" ! We are licensed 
to operate in all states ! You have no reason not to 
act now . Sign up a friend and you get half off . Thanks 
. Dear Friend , This letter was specially selected 
to be sent to you . If you no longer wish to receive 
our publications simply reply with a Subject: of "REMOVE" 
and you will immediately be removed from our club ! 
This mail is being sent in compliance with Senate bill 
1620 , Title 6 , Section 305 ! This is not multi-level 
marketing ! Why work for somebody else when you can 
become rich in 38 weeks . Have you ever noticed how 
many people you know are on the Internet and nearly 
every commercial on television has a .com on in it 
! Well, now is your chance to capitalize on this ! 
WE will help YOU deliver goods right to the customer's 
doorstep plus increase customer response by 160% ! 
You can begin at absolutely no cost to you . But don't 
believe us ! Prof Simpson who resides in Idaho tried 
us and says "I was skeptical but it worked for me" 
! We are licensed to operate in all states ! We IMPLORE 
you - act now . Sign up a friend and you'll get a discount 
of 30% . Thanks .
```
"Apa benda ni ??", ya, saya pun rasa begitu ketika menyelesaikan tugasan ini.

Decode teks di atas menggunakan [Spamimic](https://www.spammimic.com/decode.shtml) dan peroleh bendera.

```Bendera : 3108{sebuah_erti_pengorbanan}```

- ### Pesan Tentang Bicara (Sederhana)

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/MISC/Pesan%20Tentang%20Bicara%20(Sederhana)/PESANTENTANGBICARA.png?raw=true)

Kita diberikan satu gambar seperti berikut :

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/MISC/Pesan%20Tentang%20Bicara%20(Sederhana)/PESANTENTANGBICARA.png?raw=true)

Terdapat [Morse Code](https://morsedecoder.com/) di dalam gambar, decode dan kita peroleh :

```3108 NILQEP_CIZOPSW_FGMEPK```

Teks ini adalah dalam bentuk [Vigenere Cipher](https://www.dcode.fr/vigenere-cipher), Decode dengan kunci ```KEY``` dan peroleh bendera.

```Bendera : 3108{DENGAR_SEBELUM_BICARA}```

- ### 3108 CTF Town (Sederhana)

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/MISC/3108%20CTF%20Town%20(Sederhana)/3108CTFTOWN.png?raw=true)

Kita diberikan satu fail GBA yang berupa permainan video.

Main permainan video ini menggunakan GBA Emulator dan peroleh bendera.

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/MISC/Pesan%20Tentang%20Bicara%20(Sederhana)/PESANTENTANGBICARA.png?raw=true)

```Bendera : 3108{b4ntu_4m4l4n_mul1a}```

- ### Nasi Lemak 1 Juta (Mudah)

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/MISC/Nasi%20Lemak%201%20Juta%20(Mudah)/NASILEMAK1JUTA.png?raw=true)

Untuk tugasan ini, kita diberikan fail ```.exe``` seperti berikut :

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/MISC/Nasi%20Lemak%201%20Juta%20(Mudah)/NASILEMAK1JUTA.png?raw=true)

untuk mendapatkan bahan rahsia, kita memerlukan 1 juta nasi lemak, tidaklah berdaya jari ini untuk menekan sehingga memperoleh 1 juta nasi lemak.

Dengan itu, kita boleh gunakan [Cheat Engine](https://www.cheatengine.org/downloads.php) untuk menukar nilai nasi lemak menjadi 1 juta lalu memperoleh bahan rahsia.

![tugasan3](https://github.com/0xhoshi/3108CTF-WRITEUP/blob/main/3108CTF/MISC/Nasi%20Lemak%201%20Juta%20(Mudah)/NASILEMAK1JUTA.png?raw=true)

```Bendera : 3108(B2148ED1A1EA228DD33363B6D1134063B59B62DB)```

## TUGASAN SAMPINGAN (STEGA)
