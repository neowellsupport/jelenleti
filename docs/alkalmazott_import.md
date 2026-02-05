# Alkalmazott import

Az alkalmazott törzset a felületen csoportosan import segítségével is lehet rögízteni, illetve adatokat módosítani. A felületről kiexportált táblázatot módosíthatjuk, és utána visszatölthetjük a rendszerbe.  
<br>
> [!NOTE|label:Import filera vonatkozó általános szabályok]
> - fix fejléceket tartalmaz, azok nem módosíthatók
> - az oszlopok sorrendje felcserélhető
> - az egyes rekordok beazonosítása a [badge:blue:XXXX] oszlop alapján történik


Az import file az alábbi oszlopokat tartalmazza:

### Név
Az alkalmazott neve.
<br>

| Validátor | Leírás |
|:------| :-----------|
| KÖTELEZŐ | [badge:red:kötelező] |
| HOSSZ | Legfeljebb [badge:gray:100] karakter hosszú lehet.|

### Email
Az alkalmazott email címe.
<br>

| Validátor | Leírás |
|:------| :-----------|
| KÖTELEZŐ | [badge:red:kötelező] |
| FORMÁTUM | Tartalmaznia kell 1 [badge:gray:@] karaktert, és legalább 1 [badge:gray:.] karaktert (Itt igazából gbobálisabb Email formátum ellenőrzés van, ami elvileg azt is kidobja ha a @ és . között nincs semmi vagy előtte utána ...) | 
| HOSSZ | Legfeljebb [badge:gray:100] karakter hosszú lehet.|
| DUPLIKÁCIÓ | Legfeljebb [badge:gray:1] - szer szerepelhet ugyanaz az email cím.|

### Adószám
Az alkalmazott adóazonosító jele.
<br>

| Validátor | Leírás |
|:------| :-----------|
| HOSSZ | Legfeljebb [badge:gray:50] karakter hosszú lehet.|

### Telefonszám
Az alkalmazott telefonszáma.
<br>

| Validátor | Leírás |
|:------| :-----------|
| HOSSZ | Legfeljebb [badge:gray:15] karakter hosszú lehet.|

### Pozíció
| Validátor | Leírás |
|:------| :-----------|
| HOSSZ | Legfeljebb [badge:gray:100] karakter hosszú lehet.|
| LÉTREHOZÁS | Ha nem létezik a megadott pozíció a rendszerben, akkor automatikusan létrehozásra kerül|

### Divízió
| Validátor | Leírás |
|:------| :-----------|
| HOSSZ | Legfeljebb [badge:gray:100] karakter hosszú lehet.|
| LÉTREHOZÁS | Ha nem létezik a megadott pozíció a rendszerben, akkor automatikusan létrehozásra kerül|

### Munkakör
| Validátor | Leírás |
|:------| :-----------|
| HOSSZ | Legfeljebb [badge:gray:150] karakter hosszú lehet.|
| LÉTEZÉS | A rendszerben már létező munkakörnek kell lennie|

### Felettes (emailcíme)
| Validátor | Leírás |
|:------| :-----------|
| LÉTEZÉS2 | Ha létező cím kerül megadásra, akkor hozzárendelésre kerül a felettes, ha nem akkor nem okoz validációs hibát, üres lesz a felettes mező|

### Munkaidő kezdete
 Validátor | Leírás |
|:------| :-----------|
| FORMÁTUM |[badge:gray:HH:PP] formátumú értelmezhető időpont  | 

### Munkaidő vége
 Validátor | Leírás |
|:------| :-----------|
| FORMÁTUM |[badge:gray:HH:PP] formátumú értelmezhető időpont  | 
