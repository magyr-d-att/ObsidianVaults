## Páros gráf:
Akkor páros gráf, ha fel lehet bontani a csúcsait egy A és B halmazra, úgy hogy ezen halmazokon belül nem megy él

- Ahhoz hogy páros legyen a gráf minden benne lévő körnek párosnak kell lennie.

## Párosítás:
Egy élhalmazból kiválasztott részhalmaz, amelyre igaz, hogy semelyikének nincs közös végpontja.

**Maximális párosítás** = Max független élek száma.

## Megtalálása:
alternáló utas algoritmus:
- Kiindulunk egy random párosításból
- Ilyen sorrendben megyünk végig: Nincs bent - bent van - nincs bent.. etc
- Javító utat keresünk - olyat ami többet ad.
Javító út feltétele: 
- ->Az élsorozat egy páratlan hosszú út- G-ben.
- ->Az élek felváltva elemei M-nek.
- -> az út kezdő és végpontja nem illeszkedik semelyik M-beli élre.

## Tutte-tétel:
Egy gráfban csak akkor létezik teljes párosítás, ha bárhogy elhagyott pontok ugyanannyi vagy kevesebb páratlan csúcsú komponenst hagynak hátra.

## Hall-tétel:
Legyen N(X) egy olyan halmaz ami tartalmazza A olyan szomszédait, amelyek B-ben vannak.

Kizárólag akkor van A-t fedő párosítása egy gráfnak, ha X elemszáma <= N(X) Elemszáma.

## Frobenius-tétel:
Ha A és B-ben van ugyanolyan mennyiségű csúcs van, és van A-t lefedő párosítás, akkor az B-t is fedi.