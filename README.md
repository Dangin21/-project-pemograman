# Projek Pemograman
Nama    : I Gusti Surya Dangin Mardika
Nim     : 312110476
Kelas   : TI.21.BA.1

# Lab 2 Lat 1
1. Buat program sederhada dengan input 2 buah bilangan, kemudian tentukan bilangan terbesar dari kedua bilangan tersebut menggunakan statement if.

- Codingan

# menentukan 2 bilangan dari yang terbesar
print(' ')
print('Program menentukan Nilai Terbesar dari 2 bilangan')

print(' ')
a = int(input("bilangan pertama: "))
b = int(input("bilangan kedua: "))

print(' ')
if a > b:
    maks = a
else:
    maks = b

print('Bilangan Terbesar adalah %d' % maks)

# Lab 2 Lat 2
2. Buat program untuk mengurutkan data berdasarkan input sejumlah data (minimal 3 variable input atau lebih), kemudian tampilkan hasilnya secara berurutan mulai dari data terkecil

- Codingan

print('')
print("Mengurutkan data dari yang terkecil")
data = []
for i in range (3):
    x = int(input('Masukan bilangan: '))
    data.append(x)
print('Data sebelum diurutkan: ', data)
list.sort(data)
print('Data dari yang terkecil: ', data)

# Lab 3 Lat 1
1. Buat program dengan perulangan bertingkat (nested) for yang menghasilkan output sebagai berikut

- Codingan

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

# Lab 3 Lat 2
2.  Tampilkan n bilangan acak yang lebih kecil dari 0.5.
    nilai n diisi pada saat runtime
    anda bisa menggunakan kombinasi while dan for untuk menyelesaikannya

- Codingan

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

###### TERIMA KASIH ######