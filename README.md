# ABC KISKER

Az ABC KISKER egy billentyuzettel vezerelheto, terminalos bolti program kis uzletek szamara. Arra keszult, hogy egyszeruen lehessen vele a napi penztari munkat, a termekek karbantartasat, a keszlet kezeleset es az alap riportokat egy helyen elvegezni.

## Mire jo a program?

- Kassza (POS) hasznalata termekek beolvasasahoz, tetelezeshez es blokk lezarashoz
- Vonalkodok gyors ellenorzese
- Termekek rogzitese, szerkesztese, EAN kodok kezelese
- Keszlet novelese es csokkentese
- Alap riportok megtekintese napi eladasokrol es alacsony keszletrol
- Biztonsagi mentesek keszitese es korabbi adatok visszaallitasa

## Javasolt telepites Windows alatt

A program javasolt helye:

`C:\ABC\`

A legegyszerubb hasznalat:

1. Masold be a program fajljait a `C:\ABC\` mappaba.
2. Innen inditsd el a programot.
3. A program innen fogja elerni az adatbazist es a menteseket is.

## Hol tarolja az adatokat?

A program az adatait egy SQLite adatbazisban tarolja, amelynek neve:

`pos.db`

Ez a fajl alapertelmezetten ugyanabban a mappaban van, ahonnan a program fut. Javasolt telepites eseten ez tipikusan:

`C:\ABC\pos.db`

## Hogyan keszul rola mentes?

A program automatikusan havi biztonsagi mentest keszit az adatbazisrol. Ez azt jelenti, hogy minden honapban az elso inditasnal letrehoz egy uj mentest a `backup` mappaba.

A mentesek helye javasolt telepites eseten:

`C:\ABC\backup\`

Ezen felul a programbol kezzel is lehet export mentest kesziteni, es visszaallitas elott automatikusan vedelmi mentest is keszit, hogy az elozo allapot visszanyerheto maradjon. Továbbá minden frissítés elott is automatikusan mentest keszit a program.

## Rovid osszefoglalas

Az ABC KISKER egy egyszeru, gyorsan kezelheto bolti program, amely egy helyen ad penztargepet, termeknyilvantartast, keszletkezelest, riportokat es adatmentest.

## Licensz

Az ABC KISKER program minden magyar kisbolt szamara ingyenesen hasznalhato.
