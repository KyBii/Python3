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
coba = 0
nomor_togel = 7
batas = 3

while coba < batas:
    tebakan = input("Masukkan angka (1-9) : ")
    tebakan = int(tebakan)
    if tebakan == nomor_togel:
        print("Selamat anda benar")
        break
    
    else :
        print("Anda salah")
    coba += 1
```
### VS Code & Output
![R5](https://user-images.githubusercontent.com/93004722/140697358-889cd843-fe6c-4e1c-89fd-4164ca579623.PNG)

## 6. Aplikasi Kalkulator
### Source Code

```py
perintah = ""

while perintah != "exit":
    perintah = input("Perintah : ")
    if perintah == "exit":
        break
    
    if perintah != '+' and perintah != '-' and perintah != '*' and perintah != '/':
        print("Perintah tak dikenali")
        continue
    
    a = int(input("Masukkan angka pertama : "))
    b = int(input("Masukkan angka kedua : "))
    
    if perintah == '+':
        hasil = a + b
    elif perintah == '-':
        hasil = a - b
    elif perintah == '*':
        hasil = a * b
    elif perintah == '/':
        hasil = a / b
   
    print(hasil)
print("Terima kasih!")
```
### VS Code & Output
![R6](https://user-images.githubusercontent.com/93004722/140697750-c6c033ba-6398-4c44-8991-14c6da3a9d42.PNG)
