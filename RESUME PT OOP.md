RESUME MATERI OBJECT ORIENTED PROGRAMMING (OOP) PYTHON

1. Pengertian OOP

Object Oriented Programming (OOP) adalah metode pemrograman yang menggunakan konsep objek dan class untuk membuat program lebih terstruktur, rapi, dan mudah dikembangkan.

Konsep dasar OOP:

- Class: Cetakan atau rancangan untuk membuat objek.
- Object: Hasil dari class.
- Attribute: Data atau karakteristik yang dimiliki objek.
- Method: Fungsi yang berada di dalam class.

2. Membuat Class dan Object

Contoh kode:

class iphon:
    pass

class hp:
    pass

iphon1 = iphon()
iphon2 = iphon()

hp1 = hp()
hp2 = hp()

Penjelasan:

- class iphon digunakan untuk membuat class bernama iphon.
- class hp digunakan untuk membuat class bernama hp.
- pass berarti class belum memiliki isi atau perintah.
- iphon1 dan iphon2 merupakan objek dari class iphon.
- hp1 dan hp2 merupakan objek dari class hp.

3. Fungsi Type()

Contoh kode:

print(type(iphon1))
print(type(iphon2))
print(type(hp1))
print(type(hp2))

Penjelasan:

Fungsi type() digunakan untuk mengetahui jenis atau class dari sebuah objek.

4. Membuat Class Mahasiswa

Contoh kode:

class Mahasiswa:
    nim = 0
    nama = ""

    def perkenalan(self):
        print(f"halo nama saya {self.nama}")

    def hello(self, nama):
        print(f"hello {nama}, nama saya {self.nama}")

Penjelasan:

- Mahasiswa merupakan nama class.
- nim merupakan atribut untuk menyimpan nomor induk mahasiswa.
- nama merupakan atribut untuk menyimpan nama mahasiswa.
- perkenalan() merupakan method untuk memperkenalkan diri.
- hello() merupakan method untuk menyapa orang lain.
- self digunakan untuk mengakses atribut dan method milik objek itu sendiri.

5. Membuat Object Mahasiswa

Contoh kode:

mahasiswa = Mahasiswa()
mahasiswa.nama = "esta"

mahasiswa.perkenalan()
mahasiswa.hello("queen")

Penjelasan:

Kode tersebut membuat objek bernama mahasiswa dari class Mahasiswa. Kemudian nama mahasiswa diisi dengan "esta".

Hasil output:

halo nama saya esta
hello queen, nama saya esta

6. Instance Attribute

Instance attribute adalah atribut yang dimiliki oleh masing-masing objek dan nilainya dapat berbeda antara satu objek dengan objek lainnya.

Contoh kode:

mahasiswa1 = Mahasiswa()
mahasiswa1.nim = 123456
mahasiswa1.nama = "esta"

print(mahasiswa1.nim)
print(mahasiswa1.nama)

mahasiswa2 = Mahasiswa()
mahasiswa2.nim = "123456"
mahasiswa2.nama = "queen"

print(mahasiswa2.nim)
print(mahasiswa2.nama)

Penjelasan:

Pada contoh tersebut terdapat dua objek mahasiswa, yaitu:

- mahasiswa1 memiliki NIM 123456 dan nama esta.
- mahasiswa2 memiliki NIM "123456" dan nama queen.

Walaupun berasal dari class yang sama, setiap objek dapat memiliki nilai atribut yang berbeda.

7. Kesimpulan

Object Oriented Programming (OOP) merupakan konsep pemrograman yang menggunakan class dan object. Class berfungsi sebagai cetakan untuk membuat objek. Objek memiliki atribut sebagai tempat menyimpan data dan method sebagai fungsi untuk menjalankan perintah.

Dengan menggunakan OOP, program Python menjadi lebih terstruktur, mudah dipahami, dan memudahkan pengelolaan data.

Materi yang dipelajari:

1. Pengertian OOP.
2. Membuat class.
3. Membuat object.
4. Menggunakan fungsi type().
5. Membuat attribute.
6. Membuat method.
7. Memahami self.
8. Instance attribute.
