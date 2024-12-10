# Nobel

## Adatszerkezet

Első lépésként azt kell eldöntenünk, hogyan tároljuk a díjak adatait.

Először létrehozunk egy Dij osztályt, amelyben egy díj adatai, és az őket kezelő metódusok vannak. Ezután a Main osztályban listát készítünk a díjak beolvasott adataiból.

Kezdj egy új projektet _Nobel_ néven! Bár a feladat azt írta, hogy grafikus alkalmazást is létre lehet hozni, a konzolos megoldás egyszerűbb és gyorsabb.

A Main osztályon kívül hozz létre a projektben egy Dij osztályt is!

## A Dij osztály

A Dij osztályban tároljuk egy díj minden adatát.

Add meg ezeket így:

Ezután készíts egy konstruktort, amely a beolvasott sorból beállítja a változók értékeit! Vigyázz, van olyan díj, ahol nincs megadva a vezetéknév! Ezt az esetet is kezelni kell!

Ezután készíts automatikus getter metódusokat az adattagokhoz (Alt+Insert)!

Mivel a feladatban több helyen a teljes név kell, készíts egy getNev metódust is:

Enélkül is meg lehetne oldani a feladatot, de így kényelmesebb.

## Beolvasás

Válts át a Main osztályra, és hozd létre a díjak listáját:

Ezután készítsd el a main metódus elején a beolvasást (2. feladat)! A beolvasás elején átugorjuk a fejléc sort.   

Most írtunk hibakezelést, ezért nem kell jelezni a kivétel dobását, és a fájl automatikusan bezáródik a beolvasás után.

Másold a CSV fájlt a projekt mappájába, és próbáld ki a programot!

## Arthur B. McDonald

Keresd meg (lineáris kereséssel), és írasd ki Arthur B. McDonald díjának típusát (3. feladat):

Próbáld ki!

## A 2017-es irodalmi díj

A 4. feladatban azt kell kiíratni, hogy ki kapta 2017-ben az irodalmi Nobel-díjat.

Folytasd így a main metódust:

Próbáld ki!

## Szervezetek

Az 5. feladatban összeszámolni, hogy mely szervezetek kaptak béke Nobel-díjat 1990-től kezdve.

A megoldásban felhasználjuk, hogy a díjakat évszám szerint csökkenően olvastuk be (nézd meg a fájlban), és hogy a szervezeteknél a vezetéknév nincs megadva.

Folytasd a main metódust:

Próbáld ki, és hasonlítsd össze a mintával!

## Curie család

Ezután a Curie család díjait kell kilistázni. Vigyázat, a vezetéknévben nem csak Curie szerepelhet! Ezért használjuk a contains metódust, amely azt vizsgálja, hogy a vezetéknév tartalmazza-e a Curie szót.

Próbáld ki, és hasonlítsd össze a mintával!

## Melyikből mennyi?

A 7. feladatban azt kell megszámolni, hogy melyik típusú díjból hányat osztottak ki.

Ehhez először készíts egy HashMap-et az osztály elején:

Utána írd ezt a main metódusba:

Próbáld ki, és hasonlítsd össze a mintával!

## Orvosi díjak

Az utolsó, 8. feladatban az orvosi Nobel-díjakat évszám szerint növekvő sorrendben kell kiíratni az _orvosi.txt_ fájlba a minta szerint.

Lehetne évszám szerint növekvő sorrendbe rendezni az adatokat, de van egyszerűbb megoldás is. Mivel most évszám szerint csökkenő sorrendben vannak, visszafelé megyünk végig a listán:

Futtasd a programot, és ellenőrizd az _orvosi.txt_ fájlt! Hasonlítsd össze a mintával!