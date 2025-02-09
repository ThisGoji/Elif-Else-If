# if elif else digunakan jika terdapat dari 3 atau kondisi lebih
umur = 18
if umur > 1:
    print("Anda sudah dewasa")
elif umur > 18:
    print("Anda sudah dewasa")
else:
    print("Kamu masih anak-anak")

nilai = 10
if nilai >= 90:
    print("A")
elif nilai >= 80:
    print("B")
elif nilai >= 70:
    print("C")
elif nilai >= 60:
    print("D")
else:
    print("E")

angka = input("masukkan angka")
angka = int(angka)

if angka % 2 == 0:
        print("genap")
else:
        print("Negativ")
