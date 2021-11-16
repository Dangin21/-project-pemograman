# Projek Pemograman
NAMA  : I GUSTI SURYA DANGIN MARDIKA
NIM   : 312110476
KELAS : TI.21.BA.1


# Cara penyelesaian dan codingan
Latihan 1 Lab 2

1. Buat program sederhada dengan input 2 buah bilangan, kemudian tentukan bilangan terbesar dari kedua bilangan tersebut menggunakan statement if.

codingannya
![ing1]https://github.com/Dangin21/-project-pemograman/blob/main/screnshoot%20codingan/2021-11-16%20(7).png

hasilnya
![ing2]https://github.com/Dangin21/-project-pemograman/blob/main/screnshoot%20codingan/2021-11-16%20(8).png


Latihan 2 Lab 2
2. Buat program untuk mengurutkan data berdasarkan input sejumlah data (minimal 3 variable input atau lebih), kemudian tampilkan hasilnya secara berurutan mulai dari data terkecil.

Codingannya
![ing3]https://github.com/Dangin21/-project-pemograman/blob/main/screnshoot%20codingan/2021-11-16%20(11).png

hasilnya
![ing4]https://github.com/Dangin21/-project-pemograman/blob/main/screnshoot%20codingan/2021-11-16%20(10).png


*Latihan 1
1. Buat program dengan perulangan bertingkat (nested) for yang menghasilkan output sebagai berikut:

# Codingan
```
s = ''
for i in range (10):
    s += str(i) +'\t   '
print (s)

s = ''
for i in range (1, 11):
    s += str(i) +'\t   '
print (s)

s = ''
for i in range (2, 12):
    s += str(i) +'\t   '
print (s)

s = ''
for i in range (3, 13):
    s += str(i) +'\t   '
print (s)

s = ''
for i in range (4, 14):
    s += str(i) +'\t   '
print (s)

s = ''
for i in range (5, 15):
    s += str(i) +'\t   '
print (s)

s = ''
for i in range (6, 16):
    s += str(i) +'\t   '
print (s)

s = ''
for i in range (7, 17):
    s += str(i) +'\t   '
print (s)

s = ''
for i in range (8, 18):
    s += str(i) +'\t   '
print (s)

s = ''
for i in range (9, 19):
    s += str(i) +'\t   '
print(s)
```
<img width="777" alt="new11" src="https://user-images.githubusercontent.com/93661771/141786316-3def5504-7fbe-4e22-87cb-859c181a7647.PNG">
<img width="777" alt="new22" src="https://user-images.githubusercontent.com/93661771/141786440-0d8abb33-2f6c-4aa8-9527-d44ae0148e66.PNG">

# Hasil Output Codingan
<img width="943" alt="end" src="https://user-images.githubusercontent.com/93661771/141784182-24ee62ba-56d9-48d7-acaa-e702e787f7e0.PNG">

*Latihan 2
1. Tampilkan n bilangan acak yang lebih kecil dari 0.5.
2. nilai n diisi pada saat runtime
3. anda bisa menggunakan kombinasi while dan for untuk menyelesaikannya

# Codingan
```
print('==== Bilangan Acak yang lebih kecil dari 0.5 ====')
print(' ')
import random
N = int(input("Masukan nilai N : "))
a = 0
for x in range(N):
    a += 1
    b = random.uniform(.0,.5)
    print('Data ke:',a,'==>',b)
print('Selesai')
print(' ')
jawab = 'lanjutkan'
hitung = 0
while jawab == "lanjutkan":
    hitung += 1
    jawab = input('Ingin Mengulang ? (Y/N) : ')
    if jawab == "Lanjutkan":
        break
print('Total perulangan : ' + str (hitung))
```
# Hasil Codingan (Program)
![hasil codingan](https://user-images.githubusercontent.com/46749500/53287636-a9dbbc80-37b1-11e9-8043-13169152b9dd.png)

# Tugas Latihan 
1. Simpan project Praktikum hari ini ke repository server.
2. Buat penjelasan setiap Lab/latihannya pada file README.md

# Sekian & Terimakasih