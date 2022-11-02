# #Vücut Kitle İndeksi Hesaplama :

name = input("Lütfen Adınızı Yazınız:  ")
kg = float(input("Kilonuz:  "))
print("Lütfen boyunuzu 1.60 - 1.85 gibi değerlerle giriniz...")
hg = float(input("Boyunuz:   "))

index = (kg) / (hg ** 2)

if (index >= 0) and (index <= 18.4):
    print(f"{name} kilo indeksin: {index} ve kilo değerlendirmen Zayıf")

elif (index > 18.4) and (index <= 24.9):
    print(f"{name} kilo indeksin: {index} ve kilo değerlendirmen Normal")
    
elif (index > 24.9) and (index <= 29.9):
    print(f"{name} kilo indeksin: {index} ve kilo değerlendirmen Kilolu")

elif (index > 29.9) and (index <= 34.9):
    print(f"{name} kilo indeksin: {index} ve kilo değerlendirmen Obez")

else:
    pass
