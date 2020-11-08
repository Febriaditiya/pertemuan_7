lab3


# program python perulangan bertingkat
 
 perulangan dalam bahasa pemrograman berfungsi melakukan sesuatu secara berulang-ulang.
terdapat dua jenis perulangan di python, yaitu `for` dan `while`<br>
`for` disebut counted loop (perulangan yang terhitung)<br>
`while` di sebut uncounted loop (perulangan yang tak terhitung)<br>
`for` biasanya digunakan untuk mengulangi code yang sudah diketahui banyak perulangan <br>
`while` untuk perulangan yang memiliki syarat dan tidak tentu berapa banyak perulangannya.<br>

## latihan 1
 membuat program dengan perulangan bertingkat  (nested) for.

**code**

	baris = 10
	kolom = baris

	for i in range (baris):
   		for j in range (kolom):
      	 	tambahkan = i+j
       		print("{0:>5}".format(tambahkan),end='')
    
  		print() 

pertama kita menentukan banyak nya perulangan sebanyak 10x

	baris = 10
	kolom = baris

variable `i` berfungsi untuk menampung ideks

dan fungsi `range()` berfungsi untuk membuat list dengan range dari 1-10.

	for i in range (baris):
    		for j in range (kolom):
        	tambahkan = i+j
        	print("{0:>5}".format(tambahkan),end='')
    
    	print()

hasil dari output

![lab3.1.png](/gambar/lab3.1.png) 

## latihan 2
 
struktur Algoritma latihan2

	1.Mulai 
	2.TampilKan n bilangan acak yang lebih kecil dari 0.5
	3.Nilai n diisi pada saat runtime 
	4.Anda bisa menggunakan kombinasi  `while` atau `for` untuk menyelesaikannya.
	5.Gunakan fungsi `random()` yang dapat diimport terlebih dahulu.
	6.Selesai

Step pada souce code latihan2

![lab3.3.png](/gambar/lab3.3.png)

Output dari latihan2

![lab3.2.png](/gambar/lab3.2.png)    