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

## Utveckling

## Testnings strategi

 - Automatiska tester: [Testmiljöer](https://github.com/jarun/buku/blob/master/tox.ini)
   - Använder tox
   - Testerna finns i `/tests`.
   - För att köra en testmiljö: `python -m tox -e quick`
 - [Manuella tester](https://github.com/jarun/buku/wiki/PR-guidelines#testing-bukuserver)
