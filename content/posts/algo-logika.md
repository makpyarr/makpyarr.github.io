---
title: ALGORITMA - LOGIKA.
date: 2022-09-08
categories: [algoritma]
tags: [wika-purbasari, algoritma, ci3, materi, logika,pertemuan-1]
duration: 42:00
---

{{< step label="Pendahuluan" duration="2:00" >}}

perhatikan argumen dibawah ini :
> Jika anda mahasiswa informatika maka anda tidak sulit belajar algoritma. Jika anda tidak suka begadang maka anda bukan mahasiswa Informatika.Tetapi, anda sulit belajar Algoritma dan anda tidak suka begadang.Jadi anda bukan mahasiswa informatika

apakah kesimpulan dari argumen diatas valid?
alat bantu untuk memahami argumen tersebut adalah **Logika**


{{< /step >}}


{{< step label="Apakah Logika Itu?" duration="3:00" >}}

- Banyak teorema dalam Ilmu Komputer/Informatika yang membutuhkan pemahaman logika

- Bahkan,logika adalah ***jantung*** dari algoritma dan pemrograman

- Logika merupakan dasar dari semua penalaran(*reasoning*) 

- Penalaran didasarkan pada hubungan antara pernyataan (*statements*)
{{< /step >}}


{{< step label="Proposisi" duration="3:00" >}}

- Proposisi adalah kalimat deklaratif yang bernilai benar (true) atau salah (false),tetapi tidak dapat sekaligus keduanya. Kebenaran atau kesalahan dari sebuah kalimat disebut nilai kebenaran(truth value)
- sebuah proposisi (proposition) atau statement ialah sebuah kalimat deklaratif yang memiliki tepat satu nilai kebenaran,yaitu : "Benar"(B) atau "Salah"(S)
>**Contoh Proposisi**
> - 6 adalah bilangan genap
> - Ibukota provinsi jawa barat adalah Semarang
> - Kemarin hari hujan
> - 2 + 2 =4

> **Bukan Proposisi**
> - Jam berapa kereta tiba?
> - Tolong ambilkan buku tulis itu !
> - X + 3 = 8
> - X > 3 

{{< /step >}}

{{< step label="Mengkombinasikan Proposisi" duration="3:00" >}}

- Operator Logika untuk  menkombinasikan proposisi yaitu dan(and),atau(or) dan tidak(not)
- Proposisi yang terbentuk dari  pengkombinasian beberapa proposisi  atomik disebut proposisi majemuk
>**Proposisi majemuk ada 3 macam**
> - Konjungsi(conjunction)
> - Disjungsi(disjunction)
> - Ingkaran(negation)

## 1. Konjungsi / AND / ^ ##
Konjungsi p dan q dinyatakan dengan, p ^ q,adalah sebuah proposisi yang bernilai benar jika proposisi p dan q  keduanya bernilai benar.

Pernyataan ”p DAN q” dapat ditulis p ^ q  
>Contoh:
> - p = Bumi adalah satu-satunya planet di jagat raya yang mempunyai  kehidupan. (B)
> - q = Satu dekade sama dengan 10 tahun. (B)
> - p ^ q = Bumi adalah satu-satunya planet di jagat raya yang  mempunyai kehidupan dan	satu dekade sama dengan 10 tahun.

Tabel kebenaran:

| p | q | p^q |
| ----------- | :---------: | ----------: |
| B | B | B |
| B | S | S |
| S | B | S |
| S | S | S |


## 2. Disjungsi / OR / V
Disjungsi p dan q dinyatakan dengan, p V q,adalah proposisi yang bernilai salah jika proposisi p dan q  keduanya bernilai salah.

Pernyataan ”p ATAU q” dapat ditulis p V q  

>Contoh:
> - p = Blaise Pascal menemukan mesin hitung.
> - q = Taufik hidayat pandai bermain bulu tangkis.
> - p V q = Blaise Pascal menemukan mesin hitung atau Taufik  hidayat pandai bermain bulu tangkis

Tabel kebenaran:

| p | q | pVq |
| ----------- | :---------: | ----------: |
| B | B | B |
| B | S | B |
| S | B | B |
| S | S | S |

## 3. Negasi / NOT / ~
p, yang memiliki nilai kebenaran negasinya ditulis sebagai p,  sedangkan lawannya adalah salah dan ditulis ~ p,

>Contoh:
> - p = Komputer digital elektronik pertama dirakit pada abad ke  dua puluh.
> - ~ p = Komputer digital elektronik tidak dirakit pada abad ke  dua puluh

Tabel kebenaran:

| p | ~p | 
| ----------- | :---------: |
| B | S |
| S | B |


{{< /step >}}