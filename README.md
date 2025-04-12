import random

print("Selamat datang di permainan Tebak Angka!")
angka_rahasia = random.randint(1, 100)

while True:
    tebakan = int(input("Tebak sebuah angka antara 1 dan 100: "))

    if tebakan < angka_rahasia:
        print("Terlalu rendah, coba lagi!")
    elif tebakan > angka_rahasia:
        print("Terlalu tinggi, coba lagi!")
    else:
        print("Selamat! Anda berhasil menebak angka tersebut.")
        break
