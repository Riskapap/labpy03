# TUGAS PRAKTIKUM 3

## Latihan1
-Kita membuat syntax untuk memasukan nilai pada N
	num = int(input("Masukan Nilai N:"))
-Masukkan fungsi random() untuk menampilkan nilai secara acak
	from random import random
	a = random()
-Lalu kita membuat variable untuk menentukan jumlah data yang di cari
	jumlah = num+1
	start = 0
	stop = jumlah
	step = 1
-Masukan synyax looping for
	for i in range ( start, stop, step):
	print("Data ke:", i, "->", (a))
	i adalah jumlah looping dan a adalah nilai acak
-Selesai

## Latihan2
-Memperkenalkan variable x integer, kemudian menginput nilainya
	a = int()
-Memperkenalkan variable b dengan nilai 0
	b = 0
-Looping WHILE apabila nilai x tidak sama dengan 0
	while a >= 0:
-Program yang akan di looping
	a = int(input("Masukkan Bilangan: "))
-If kondisi apabila nilai a sama dengan 0
	if a == 0:
-Fungsi yang menghentikan operasi dibawahnya jika suatu kondisi yang ditentukan telah tercapai
	break
-If kondisi apabila nilai a lebih besar dari nilai b
	if a > b:
-Nilai b sama dengan nilai a
	b = a
-Mencetak bilangan terbesar
	print("Bilangan terbesar adalah", b)
-Selesai 

## Program 1
-Nilai modal
	modal = 100000000
-Nilai laba 0
	laba = 0
-Nilai untung 0
	untung = 0
-Perulangan i dengan niali awal 1, nilai akhir 9 dan step 1
	for i in range (1, 9):
-Kondisi apabila belum bulan ke-3 laba masih 0%
	if(i < 3):
	laba = 0
	untung = untung + laba
-Kondisi apabila belum memasukan bulan ke-5, mendapat laba sebesar 1%
	elif(i < 5):
        laba = modal*1/100
        untung = untung + laba
-Kondisi apabila belum memasukan bulan ke-8, mendapat laba sebesar 5%
	elif(i < 8):
        laba = modal*5/100
        untung = untung + laba
-Pada bulan ke-8 laba menurun 2%, sehingga laba bulan ke-8 sebesar 3%
	else:
        laba = modal*3/100
        untung = untung + laba
-Mencetak laba per bulan
	print("Laba bulan ke", i, "sebesar:", laba)
-Menghitung total laba selama 8 bulan
	print("Total laba adalah:", untung)
-Selesai
