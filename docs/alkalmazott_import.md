# Alkalmazott import

Az alkalmazott törzset a felületen csoportosan import segítségével is lehet rögízteni, illetve adatokat módosítani. A felületről kiexportált táblázatot módosíthatjuk, és utána visszatölthetjük a rendszerbe.

## Alkalmazott törzs import táblázat struktúra

> [!NOTE|label:Import filera vonatkozó általános szabályok]
> - fix fejléceket tartalmaz, azok nem módosíthatók
> - az oszlopok sorrendje felcserélhető
> - az egyes rekordok beazonosítása a [badge:blue:XXXX] oszlop alapján történik

Az import file az alábbi oszlopokat tartalmazza:

### ID

| Validátor | Leírás |
| ------| -----------|
| validátor1   | path to data files to supply the data that will be passed into templates. |
| 2 | engine to be used for processing templates. Handlebars is the default. |
| 3    | extension to be used for dest files. |

### Alkalmazott neve
