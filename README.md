# TUGAS PRAKTIKUM 3

## Latihan1

1. Kita membuat syntax untuk memasukan nilai pada N
- num = int(input("Masukan Nilai N:"))
2. Masukkan fungsi random() untuk menampilkan nilai secara acak
- from random import random
- a = random()
3. Lalu kita membuat variable untuk menentukan jumlah data yang di cari
- jumlah = num+1
- start = 0
- stop = jumlah
- step = 1
4. Masukan synyax looping for
- for i in range ( start, stop, step):
- print("Data ke:", i, "->", (a))
- i adalah jumlah looping dan a adalah nilai acak
5. Selesai

## Latihan2

1. Memperkenalkan variable x integer, kemudian menginput nilainya
- a = int()
2. Memperkenalkan variable b dengan nilai 0
- b = 0
3. Looping WHILE apabila nilai x tidak sama dengan 0
- while a >= 0:
4. Program yang akan di looping
- a = int(input("Masukkan Bilangan: "))
5. If kondisi apabila nilai a sama dengan 0
- if a == 0:
6. Fungsi yang menghentikan operasi dibawahnya jika suatu kondisi yang ditentukan telah tercapai
- break
7. If kondisi apabila nilai a lebih besar dari nilai b
- if a > b:
8. Nilai b sama dengan nilai a
- b = a
9. Mencetak bilangan terbesar
- print("Bilangan terbesar adalah", b)
10. Selesai 

## Program 1

1. Nilai modal
- modal = 100000000
2. Nilai laba 0
- laba = 0
3. Nilai untung 0
- untung = 0
4. Perulangan i dengan niali awal 1, nilai akhir 9 dan step 1
- for i in range (1, 9):
5. Kondisi apabila belum bulan ke-3 laba masih 0%
- if(i < 3):
-- laba = 0
-- untung = untung + laba
6. Kondisi apabila belum memasukan bulan ke-5, mendapat laba sebesar 1%
- elif(i < 5):
- laba = modal*1/100
- untung = untung + laba
7. Kondisi apabila belum memasukan bulan ke-8, mendapat laba sebesar 5%
- elif(i < 8):
- laba = modal*5/100
- untung = untung + laba
8. Pada bulan ke-8 laba menurun 2%, sehingga laba bulan ke-8 sebesar 3%
- else:
- laba = modal*3/100
- untung = untung + laba
9. Mencetak laba per bulan
- print("Laba bulan ke", i, "sebesar:", laba)
10. Menghitung total laba selama 8 bulan
- print("Total laba adalah:", untung)
11. Selesai
