# Jelenlét riport kalkulált mezői

A riportban a rögíztett órákon kívül az alábbi kalkulált mezők jelennek meg:

### Munkaórák összesen
[badge:blue:MÓ]
Az adott hónapra beírt óraszámok összege.

### Munkanapi munkaórák összesen
[badge:blue:MMÓ]
Azokra a napokra beírt óraszámok összege, amelyeknek kategóriája: M, SZ, FSZ.

### Munkanapok száma
[badge:blue:MSZ]
Napok száma, ahol kat4gória M, FSZ

### Átlagos munkanap hossza (óra)
[badge:blue:ÁMH]
MMÓ / MSZ hányadosa

### MKH	Munkaidő keret hossza
[badge:blue:MKH]
[TS:Csak Munkakeret használata esetén jelenik meg.]
Munkarend szerinti óraszám, ahol kategória M, FSZ. Az egész keretre vonatkozó érték látszik, akkor is, ha az hosszabb, mint egy hónap.

### HLO	Havi ledolgozandó órák
[badge:blue:HLO]
[TS:Csak akkor jelenik meg, ha nincs munkakeret beállítva.]
Munkarend szerinti óraszám, ahol őstípus: M, FSZ

### HBÓ	Hátralévő beosztható órák
[badge:blue:HBÓ]
[TS:Csak Munkakeret használata esetén jelenik meg.]
[badge:gray:MKH] - [badge:gray:MMÓ] egész keretre (nem csak az adott hónap)

### HÁLÓ	Hátralévő ledolgozandó órák
[badge:blue:HÁLÓ]
[TS:Csak akkor jelenik meg, ha nincs munkakeret beállítva.]
[badge:gray:HLO] - [badge:gray:MMÓ]

### ÁI	Állásidő
[badge:blue:ÁI]
[TS:Csak akkor jelenik meg, ha nincs munkakeret beállítva.]
M kategóriájú napokon azon különbségek összege, ahol kisebb a ledolgozott óraszám, mint a munkarend szerinti (napi szinten) (pl: 8 órás munkanapon 6 órát dolgozott)

### ÁIK	Állásidő
[badge:blue:ÁIK]
[TS:Csak Munkakeret használata esetén jelenik meg.]
[badge:gray:HBÓ] abszolút értéke, ha [badge:gray:HBÓ] > 0

### TÓM	Túlóra - Munkanap
[badge:blue:TÓM]
[TS:Csak akkor jelenik meg, ha nincs munkakeret beállítva.]
M kategóriájú napokon azon napi eltérések összege, ahol nagyobb a ledolgozott óraszám, mint a munakrend szerinti óraszám (pl: 8 órás munkanapon 10 órát dolgozott)

### TÓÜ	Túlóra - Ünnepnap
[badge:blue:TÓÜ]
P kategóriájú nap, ami naptár szerint ünnepnap, a beírt órák összege

### TÓV	Túlóra - Vasárnap
[badge:blue:TÓV]
P kategóriájú nap, ami naptár szerint ünnepnap, a beírt órák összege, és nem [badge:gray:TÓÜ]

### TÓP	Túlóra - Pihenőnap
[badge:blue:TÓP]
P kategóriájú nap, ami naptár szerint ünnepnap, a beírt órák összege, és nem [badge:gray:TÓÜ] vagy [badge:gray:TÓV]

### TÓMK	Túlóra - Munkanap
[badge:blue:TÓMK]
[TS:Csak Munkakeret használata esetén jelenik meg.]
[badge:gray:HBÓ] abszolút értéke, ha [badge:gray:HBÓ] < 0


