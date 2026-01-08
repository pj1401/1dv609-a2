# Assignment 2
Assignment 2 i 1DV609

Valt projekt: [buku](https://github.com/jarun/buku)

## Projektet

`buku` är en bokmärkes hanterare som körs genom CLI.

Några funktioner:
 - Lägga till / ta bort bokmärken
 - Importera från webbläsare
 - Söka bokmärken
 - Öppna i webbläsaren

Om man vill kan man installera en separat frontend, `bukuserver`.

## Krav

[Funktioner](https://github.com/jarun/buku?tab=readme-ov-file#features)

## Utveckling

Först publicerad i november 2015 men under namnet `MarkIt`, bytte namn till `Buku` en månad senare för att undvika copyright problem. I 2020 ändrades namnet till `buku`.

TODO: läs igenom releases för mer info om historiken

[Att göra lista](https://github.com/jarun/buku/issues/484)

## Testnings strategi

 - Automatiska tester: [Testmiljöer](https://github.com/jarun/buku/blob/master/tox.ini)
   - Använder tox
   - Testerna finns i `/tests`.
   - För att köra en testmiljö: `python -m tox -e quick`
 - [Manuella tester](https://github.com/jarun/buku/wiki/PR-guidelines#testing-bukuserver)
