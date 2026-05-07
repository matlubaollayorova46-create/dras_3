# dras_3
Pythonda raqamlar ustida matematik vazifalarni bajarishga imkon beruvchi keng qamrovli matematik modulni o'z ichiga olgan o'rnatilgan matematik funktsiyalar to'plami mavjud.
1111111
O'rnatilgan matematik funktsiyalar
va funksiyalari iterable min()ichidagi max()eng past yoki eng yuqori qiymatni topish uchun ishlatilishi mumkin:

MisolO'zingizning Python serveringizni oling
x = min(5, 10, 25)
y = max(5, 10, 25)

print(x)
print(y)
Funksiya abs()ko'rsatilgan sonning absolyut (musbat) qiymatini qaytaradi:

Misol
x = abs(-7.25)

print(x)
Funksiya x qiymatini y ( xy ) darajasiga qaytaradi .pow(x, y)

Misol
4 ning qiymatini 3 darajasiga qaytaring (4 * 4 * 4 bilan bir xil):

x = pow(4, 3)

print(x)

REKLAMALARNI OLIB TASHLASH

Matematika moduli
mathPython shuningdek , matematik funktsiyalar ro'yxatini kengaytiradigan deb nomlangan o'rnatilgan modulga ega .

Uni ishlatish uchun siz mathmodulni import qilishingiz kerak:

import math
Modulni import qilgandan so'ng math, siz modulning usullari va konstantalaridan foydalanishni boshlashingiz mumkin.

Masalan, usul math.sqrt()sonning kvadrat ildizini qaytaradi:

Misol
import math

x = math.sqrt(64)

print(x)
Usul math.ceil()sonni eng yaqin butun songacha yuqoriga yaxlitlaydi va math.floor() usul sonni pastga eng yaqin butun songacha yaxlitlaydi va natijani qaytaradi:

Misol
import math

x = math.ceil(1.4)
y = math.floor(1.4)

print(x) # returns 2
print(y) # returns 1
Konstanta math.pi, PI (3.14...) qiymatini qaytaradi:

Misol
import math

x = math.pi

print(x)
