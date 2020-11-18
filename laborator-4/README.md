# Laboratorul 4

### ⚠ Puneți cât mai multe întrebări! Nu există întrebări greșite.
#### Semnalați orice fel de greșeli găsiți!

# Cuprins
## [Tema 2](#Tema-2-1)
## [Întrebări, erori și orice nu a fost acoperit deja](#întrebări-erori-diverse)
## [Resurse recomandate](#resurse-recomandate-1)

## Tema 2

Scopul acestei teme este familiarizarea cu limbajul C++ (din nou) și cu unele concepte OOP de bază, pe lângă cele de la prima temă. **Nu vă complicați!** Sau nu excesiv 😄

Cerințe comune:
- moșteniri, funcții virtuale (care vor fi și folosite!)
- excepții C++
- fișiere separate (!) `.h` și `.cpp` pentru fiecare clasă (dacă sunt clase mici cu același scop, le puteți pune în același fișier)
- `git tag` cu o versiune preliminară; ideea ar fi să aveți tag-ul `v1.0.0` atunci când e 99% gata, spre sfârșitul semestrului
- FĂRĂ using namespace std în fișiere .h la nivel global
  - pot fi declarații locale *[necesită verificare]*
- cod indentat consistent!
- obligatoriu smart pointers pentru alocările dinamice (discutăm excepțiile🇷🇴)
- compilat cu `-Wall -Wextra -pedantic -Weffc++` (`-Werror` pentru 10+) `-g`
- fără variabile globale (discutăm excepțiile🇷🇴)
- se aplică toate cerințele de la tema 1 care nu au fost deja îndeplinite
  - exemple: cât mai multe `const`, testat/apelat tot codul public de interes din `main` (iar ce e public și nu e apelat ar trebui șters)
- citirea datelor de intrare obligatoriu din fișier sau creat obiecte în `main`!! (discutăm excepțiile🇷🇴, dar și acolo va fi necesar așa ceva)
- hard deadline: **6 decembrie**

