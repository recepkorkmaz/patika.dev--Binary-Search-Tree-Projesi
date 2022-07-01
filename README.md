# ***www.patika.dev -> Binary-Search-Tree-Projesi***

# 1.) [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamaları

**Verilen Örneğe göre;**
- Root: 7

*7'nin Sağında 7'den büyük Solunda ise 7'den küçük olan sayılar olacaktır.*

**Buna göre;**

***Start ->***
- [7 5 1 8 3 6 0 9 4 2]
- [5 7 1 8 3 6 0 9 4 2]
- [1 5 7 8 3 6 0 9 4 2]
- [1 3 5 7 8 6 0 9 4 2]
- [1 3 5 6 7 8 0 9 4 2]
- [1 3 5 6 7 8 0 9 4 2]
- [0 1 3 5 6 7 8 9 4 2]
- [0 1 2 3 5 6 7 8 9 4]
- [0 1 2 3 4 5 6 7 8 9]

***Stop<-***

# 2.) Big-O Gösterimi:
*O(n)*