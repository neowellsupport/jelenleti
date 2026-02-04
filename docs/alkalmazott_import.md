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
| ------| -----------|
| KÖTELEZŐ | [badge:red:kötelező] |
| HOSSZ | Legfeljebb [badge:gray:50] karakter hosszú lehet.|

### Email
Az alkalmazott email címe.
<br>

| Validátor | Leírás |
| ------| -----------|
| FORMÁTUM | Tartalmaznia kell 1 [badge:gray:@] karaktert, és legalább 1 [badge:gray:.] karaktert |
| HOSSZ | Legfeljebb [badge:gray:50] karakter hosszú lehet.|

### Adószám
Az alkalmazott adóazonosító jele.
<br>

| Validátor | Leírás |
| ------| -----------|
| KÖTELEZŐ | [badge:red:kötelező] |
| HOSSZ | Legfeljebb [badge:gray:50] karakter hosszú lehet.|
| FORMÁTUM | ???|


### Telefonszám
Az alkalmazott telefonszáma.
<br>

| Validátor | Leírás |
| ------| -----------|
| HOSSZ | Legfeljebb [badge:gray:50] karakter hosszú lehet.|
| FORMÁTUM | ???|

### Pozíció


### Divízió

### Költséghely

### Munkakör
