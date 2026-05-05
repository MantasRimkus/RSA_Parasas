RSA Skaitmeninio Parašo Sistema

Aprašymas
Ši programa yra žiniatinklio sistema, leidžianti vartotojui generuoti RSA raktus, pasirašyti tekstą skaitmeniniu parašu ir patikrinti parašo galiojimą. Programa veikia naršyklėje naudojant JavaScript.

Funkcionalumas
Sistema leidžia sugeneruoti RSA viešąjį ir privatųjį raktus, įvesti tekstą, sugeneruoti skaitmeninį parašą, rankiniu būdu pakeisti parašą ir patikrinti, ar parašas yra galiojantis ar negaliojantis.

Kaip paleisti
Atsisiųskite projektą arba atsidarykite GitHub repozitoriją. Atidarykite index.html failą naršyklėje. Paspauskite „Generuoti raktus“, įveskite tekstą, paspauskite „Pasirašyti“, o tada „Tikrinti“.

Naudotos technologijos
HTML, CSS, JavaScript, JSEncrypt biblioteka (RSA), CryptoJS (SHA-256).

Veikimo principas
Vartotojas įveda pranešimą, kuris yra maišomas naudojant SHA-256. Gautas maišos rezultatas pasirašomas naudojant RSA privatųjį raktą. Tikrinimo metu parašas tikrinamas naudojant viešąjį raktą ir nustatoma, ar jis atitinka pranešimą. Jei parašas ir pranešimas sutampa, parašas laikomas galiojančiu, priešingu atveju – negaliojančiu.
