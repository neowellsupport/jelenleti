# Alkalmazott import

Az alkalmazott törzset a felületen csoportosan import segítségével is lehet rögízteni, illetve adatokat módosítani. A felületről kiexportált táblázatot módosíthatjuk, és utána visszatölthetjük a rendszerbe.

## Alkalmazott törzs import táblázat struktúra

> [!NOTE|label:Import filera vonatkozó általános szabályok]
> - fix fejléceket tartalmaz, azok nem módosíthatók
> - az oszlopok sorrendje felcserélhető
> - az egyes rekordok beazonosítása a [badge:blue:XXXX] oszlop alapján történik

Az import file az alábbi oszlopokat tartalmazza:

### Név
[badge:red:kötelező]
Típus: [badge:gray:szöveges]
Max hossz: [badge:gray:50 karakter]

| Validátor | Leírás |
| ------| -----------|
| validátor1   | path to data files to supply the data that will be passed into templates. |

### Email
Az alkalmazott email címe.

| Validátor | Leírás |
| ------| -----------|
| VLD_MAILFORMAT | Tartalmaznia kell 1 [badge:gray:@] karaktert, és legalább 1 [badge:gray:.] karaktert |

### Adószám
[badge:red:kötelező]
Típus: [badge:gray:szöveges]
Max hossz: [badge:gray:?? karakter]
Formátum: [badge:gray:????]

