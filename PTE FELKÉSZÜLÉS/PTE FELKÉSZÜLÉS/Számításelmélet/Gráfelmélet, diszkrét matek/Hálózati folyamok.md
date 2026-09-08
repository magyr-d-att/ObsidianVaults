Irányított gráf (Hálózat) javító algoritmus (Ford-Fulkerson):

![[Pasted image 20260908022641.png]]

Jelenlegi folyamot visszafele piros nyíllal, szabad kapacitást zöld vonal.

Végignézve az lesz javító út, amivel több jut a végébe pl. S(ource) - B - A - D - T(arget), mértéke a legszűkebb út.

Egy folyam értéke mindig egyenlő lesz: sum(ki) - Sum(be)
## Vágás:

Csúcsok kiválasztása, úgy, hogy lesz egy X halmaz amiben bent van a kezdőpont, és V(G) - X ahol nincs, de a T bent van.

Vágás kapacitása: A vágásban szereplő élek összege. Visszafele mutatókat nem számoljuk.

## Ford-Fulkerson Tétel
Maximális folyam: Max folyam mindig <= mint a min vágás.
