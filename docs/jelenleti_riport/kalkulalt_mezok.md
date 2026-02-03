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
[badge:gray:MMÓ] / [badge:gray:MSZ] hányadosa

### Munkaidő keret hossza
[badge:blue:MKH]
[low:Csak Munkakeret használata esetén jelenik meg.]
Munkarend szerinti óraszám, ahol kategória M, FSZ. Az egész keretre vonatkozó érték látszik, akkor is, ha az hosszabb, mint egy hónap.

### Havi ledolgozandó órák
[badge:blue:HLO]
[low:Csak akkor jelenik meg, ha nincs munkakeret beállítva.]
Munkarend szerinti óraszám, ahol őstípus: M, FSZ

### Hátralévő beosztható órák
[badge:blue:HBÓ]
[low:Csak Munkakeret használata esetén jelenik meg.]
[badge:gray:MKH] - [badge:gray:MMÓ] egész keretre (nem csak az adott hónap)

### Hátralévő ledolgozandó órák
[badge:blue:HÁLÓ]
[low:Csak akkor jelenik meg, ha nincs munkakeret beállítva.]
[badge:gray:HLO] - [badge:gray:MMÓ]

### Állásidő
[badge:blue:ÁI]
[low:Csak akkor jelenik meg, ha nincs munkakeret beállítva.]

M kategóriájú napokon azon különbségek összege, ahol kisebb a ledolgozott óraszám, mint a munkarend szerinti (napi szinten) (pl: 8 órás munkanapon 6 órát dolgozott)

### Állásidő
[badge:blue:ÁIK]
[low:Csak Munkakeret használata esetén jelenik meg.]
[badge:gray:HBÓ] abszolút értéke, ha [badge:gray:HBÓ] > 0

### Túlóra - Munkanap
[badge:blue:TÓM]
[low:Csak akkor jelenik meg, ha nincs munkakeret beállítva.]
M kategóriájú napokon azon napi eltérések összege, ahol nagyobb a ledolgozott óraszám, mint a munakrend szerinti óraszám (pl: 8 órás munkanapon 10 órát dolgozott)

### Túlóra - Ünnepnap
[badge:blue:TÓÜ]

P kategóriájú napra - ami naptár szerint ünnepnap - beírt órák összege

### Túlóra - Vasárnap
[badge:blue:TÓV]

P kategóriájú nap, ami naptár szerint ünnepnap, a beírt órák összege, és nem [badge:gray:TÓÜ]

### Túlóra - Pihenőnap
[badge:blue:TÓP]
P kategóriájú nap, ami naptár szerint ünnepnap, a beírt órák összege, és nem [badge:gray:TÓÜ] vagy [badge:gray:TÓV]

### Túlóra - Munkanap
[badge:blue:TÓMK]
[low:Csak Munkakeret használata esetén jelenik meg.]
[badge:gray:HBÓ] abszolút értéke, ha [badge:gray:HBÓ] < 0


