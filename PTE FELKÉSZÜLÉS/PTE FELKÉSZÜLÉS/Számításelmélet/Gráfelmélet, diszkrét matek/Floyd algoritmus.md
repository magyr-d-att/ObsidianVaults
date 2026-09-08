Megmondja egy súlyozott gráf két tetszőleges pontjának egymástól való távolságát.

![[Pasted image 20260908040531.png]]


Táblázatban felírjuk a súlyozásokat a közvetlen szomszédoknak:

![[Pasted image 20260908040148.png]]

Lépkedünk a nodeokon, majd közvetett szomszédokon átvezető utakkal javítjuk, ha jobb elérhető:

pl: 3- on átvezető útnál:

- megnézzük melyik nodeok vezetnek 3-ba és hova lehet eljutni belőle:
- pl: node 3 vizsgálata -> node 4: 7 - 3 - 4 = 49, 1 - 3 - 4 = 38  
- felírjuk az összes legrövidebb utat.
- táblázatban 7 - 3 - 4 út = 49, ami jobb mint végtelen.
