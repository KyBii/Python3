# Tugas Python3
## 1. Percabangan If
### Source Code

```py
is_day = False
is_night = False

if is_day: 
    print("Selamat Siang") 
elif is_night: 
    print("Selamat Malam") 
else:
    print("Abigail Perkasa") 
```
### VS Code & Output
![R1](https://user-images.githubusercontent.com/93004722/140647175-b1ae7fc1-075a-4c75-a3dd-69faa3ce7bb5.PNG)

## 2. Operator Perbandingan
### Source Code

```py
grade = 4

if grade >= 8:
    print("Nilai kamu A")
elif grade >= 7:
    print("Nilai kamu B")
elif grade >= 6:
    print("Nilai kamu C")
else:
    print("Makanya belajar yang rajin")
```
### VS Code & Output
![R2](https://user-images.githubusercontent.com/93004722/140647557-33b34eb3-9080-40da-ba9f-67c72317c17c.PNG)

## 3. Operator Logika
### Source Code

```py
nama = "Abigail Perkasa"
Validator =  True

if len(nama) > 4 and Validator:
    print(f"Selamat datang {nama}")
else:
    print("Nama terlalu pendek")
    
# False or True = True
# True or False = True
# True and False = False
# True and True = True
```

### VS Code & Output
![R3](https://user-images.githubusercontent.com/93004722/140648443-b93d0a43-1964-4c70-9f3b-ccdcb11c88e6.PNG)

## 4. Perulangan While
### Source Code

```py
cetak = 1

while cetak < 5:
    print("#" * cetak)
    cetak +=1

print("Finish")
```
### VS Code & Output
![R4](https://user-images.githubusercontent.com/93004722/140650037-d5d2d038-27ed-4a0a-9cfd-86ad693ede82.PNG)

## 5. Game Tebak Angka
### Source Code

```py
nomor = (10 + 5) * 2 ** 4
print(nomor)
#TANDA KURUNG
#PERPANGKATAN 
#PERKALIAN ATAU PEMBAGIAN
#PEJUMLAHAN ATAU PENGURANGAN
```
### VS Code & Output
![W5](https://user-images.githubusercontent.com/93004722/140632737-3056242e-515c-4671-9fc9-55a99e797a96.PNG)

## 6. Aplikasi Kalkulator
### Source Code

```py
nomor = 7.7
nomor = round(nomor)
print(nomor)
```
### VS Code & Output
![W6](https://user-images.githubusercontent.com/93004722/140632818-b9c03018-9234-4fcd-9afc-6755b2b8fa7f.PNG)
