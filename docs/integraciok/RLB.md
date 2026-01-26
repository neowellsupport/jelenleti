# RLB export

## Export formátum

- File típus: [[token:gray:BEO]] (ez technikailag CSV file)
- Kódolás: [token:gray:UTF-8]
- Fejléc: van, tartalom, egymás utáni cellákban: [token:gray:<cég neve>], [token:gray:<cég adószáma>], [token:gray:<exportált hónap>]  “éééé-hh” formátumban

### Törzsszám 
Cég alkalmazaottjához tartozó külső azonosító (törzsszám)

### Név
Alkalmazott neve

### Hónap
Az exportált hónap. Formátum: _éééé-hh_

### [1 ... 31] - a hónap napjai felsorolva
A nap kódja, a naptípusban tárolt RLB külső azonosító alapján.

### Ledolgozott órák
Beírt munkaórák száma azokra a napokra, amelyeknek kategóriája M, F, FSZ.

### Szabadság (óra)
Munkarend szerinti napi óraszám azokra a napokra, ahol kategória SZ

### Betegszabadság (óra)
Munkarend szerinti napi óraszám azokra a napokra, ahol kategória B

### Rendkívüli munkaidő pihenõnapon 100% pótlékos (óra)
Szumma beírt óraszám azokra a napokra, ahol kategória P, és a nap nem ünnepnap, és nem vasárnap.

### Rendkívüli munkaidő beosztás eltérés miatt 50% pótlékos (óra)
Nincs használatban, fixen üres.

### Vasárnapi 50% pótlékos (óra)
Szumma beírt óraszám azokra a napokra, ahol kategória P, és a nap nem ünnepnap.

### Munkaszüneti-napi 100% pótlékos (óra)
Szumma beírt óraszám azokra a napokra, ahol kategória P, és a nap naptár szerinti ünnepnap.

### Mûszakpótlék 30% -os (óra)
Nincs használatban, fixen üres.

### Éjszakai pótlék 15%-os (óra)
Nincs használatban, fixen üres.

### Ledolgozott napok száma
Napok száma, ahol nap kategória M, FSZ

### Pihenőnapok száma
Napok száma, ahol nap kategória M, FSZ.

### Fizetett távollét
Napok száma, ahol nap kategória SZ.

### Állásidő
- **Munkakeret nélkül:** Azokra a napokra számolt különbség összege, melynek kategóriája M és a beírt órák száma kevesebb, mint a munkarend szerinti óraszám.
- **Munkakerettel:** {Munkaidő keret hossza} - {Munkanapi munkaórák összesen}, ha a fenti érték nagyobb, mint nulla.

### Munkaidõkeret feletti 50% pótlékos (óra)
Nincs használatban, fixen üres.

### Készenlét 20%
Nincs használatban, fixen üres.

### Készenlét alatt ledolgozott 100%
Nincs használatban, fixen üres.
