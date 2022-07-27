# Proje-3 (Binary Search Tree)

## Soru
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

*Cevap*

![image](https://i.hizliresim.com/s7davso.png)

Root 6 seçilmiştir, şimdi soruda verildiği sırayla verileri yerleştirmeye başlayalım;
* 7 sayısı 6'dan büyük olduğu için 6'nın sağına yerleştirildi. 
* 5 sayısı 6'dan küçük olduğu için 6'nın soluna yerleştirildi.
* 1 sayısına baktığımızda önce 6'dan sonra 5'ten küçük olduğu için 5'in soluna yerleştirildi.
* 8 sayısı önce 6'dan sonra 7'den büyük olduğu için 7'nin sağına yerleştirildi.
* 3 sayısı sırasıyla baktığımızda 6'dan ve 5'ten küçük 1'den ise büyük olduğu için 1'in sağına yerleştirildi.
* 0 sayısı sırasıyla 6'dan, 5'ten ve 1'den küçük olduğu için 1'in soluna yerleştirildi.
* 9 sayısı sırasıyla önce 6'dan sonra 7'den ve son olarak 8'den büyük olduğu için 8'in sağına yerleştirildi.
* 4 sayısı 6'dan ve 5'ten küçük 1'den ve 3'ten büyük olduğu için 3'ün sağına yerleştirildi.
* 2 sayısı 6'dan ve 5'ten küçük 1'den büyük olduğu için 3'e bakıldı, 3'ten küçük olduğu için soluna yerleştirildi.

Herhangi bir veri ekleneceği veya yeri tespit edilmek istenildiğinde önce sayı değerine bakılıp her düğüme geldiğinde sayılar karşılaştırılmalı ve düğümün sağından mı yoksa solundan mı devam edileceğine bakılmalıdır.

https://www.patika.dev
