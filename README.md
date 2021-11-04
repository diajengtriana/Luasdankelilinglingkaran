lingkaran.py

Berisi syntax untuk menghitung Luas & Keliling dalam bahasa pemrograman python.

Luas     = π × r²
Keliling = 2 x π × r
Nilai Phi yang akan digunakan adalah 3.14
r merupakan jari-jari lingkaran
Phi merupakan nilai konstanta di matematika sementara jari-jari merupakan jarak antara titik pusat dengan tepi lingkaran. Sebetulnya ada rumus lain untuk menghitung keliling lingkaran yaitu dengan menggunakan diameter, tapi pada kasus ini kita cukup menggunakan jari jari lingkaran saja.

phi = 3.14
r = float(input("Masukkan panjang jari-jari lingkaran: "))

luas = phi*(r*r)
keliling = 2*phi*r

print("Luas lingkaran adalah : "+ str(luas))
print("Keliling lingkaran adalah : "+ str(keliling))

<img width="731" alt="Screenshot 2021-11-03 160129" src="https://user-images.githubusercontent.com/92905452/140275212-c9301672-fac0-4c31-bf7b-2e46d75be24b.png">
