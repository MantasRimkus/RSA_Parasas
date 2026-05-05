# RSA Skaitmeninio Parašo Sistema

## Aprašymas
Ši programa yra žiniatinklio sistema, leidžianti vartotojui generuoti RSA raktus, pasirašyti tekstą skaitmeniniu parašu ir patikrinti parašo galiojimą.

Programa sukurta naudojant JavaScript ir veikia naršyklėje be serverio.

---

## Funkcionalumas

- Generuoti RSA viešąjį ir privatųjį raktus
- Įvesti tekstą
- Sugeneruoti skaitmeninį parašą
- Rankiniu būdu pakeisti parašą
- Patikrinti parašo galiojimą
- Parodyti rezultatą (galiojantis / negaliojantis)

---

## Kaip paleisti

1. Atsisiųskite projektą arba atsidarykite GitHub nuorodą
2. Atidarykite `index.html` failą naršyklėje
3. Naudokite sistemą:
   - Paspauskite "Generuoti raktus"
   - Įveskite tekstą
   - Paspauskite "Pasirašyti"
   - Paspauskite "Tikrinti"

---

## Naudotos technologijos

- HTML
- CSS
- JavaScript
- JSEncrypt biblioteka (RSA)
- CryptoJS (SHA-256 maišos funkcija)

---

## Veikimo principas

1. Vartotojas įveda pranešimą
2. Pranešimas yra maišomas naudojant SHA-256
3. Maišos reikšmė pasirašoma naudojant RSA privatųjį raktą
4. Tikrinimo metu:
   - Parašas tikrinamas naudojant viešąjį raktą
   - Lyginama, ar parašas atitinka pranešimą
5. Jei sutampa – parašas galiojantis, jei ne – negaliojantis

---
