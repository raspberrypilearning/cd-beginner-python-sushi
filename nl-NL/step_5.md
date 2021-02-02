## Vergelijk en controleer dingen

Je kunt Python vragen om het ene getal te vergelijken met een ander getal. Dit kan erg handig zijn voor het schrijven van spellen (bijvoorbeeld hebben spelers minstens zoveel geld als dit kostuum kost?).

Je doet dit met behulp van speciale symbolen:
* `a > b` controleert of `a` groter is dan `b`
* `a < b` controleert of `a` kleiner is dan `b`
* `a == b` controleert of `a` hetzelfde is als `b`
* `a != b` controleert of `a` niet hetzelfde is als `b`
* `a >= b` controleert of `a` groter is dan of even groot is als `b`
* `a <= b` controleert of `a` kleiner is dan of even groot is als `b`

--- collapse ---
---
title: Waarom zijn er twee gelijktekens bij elkaar?
---

De twee gelijktekens `==` worden gebruikt om variabelen **te vergelijken**, omdat het enkele gelijkteken al wordt gebruikt om waarden **toe te wijzen** aan variabelen.

--- /collapse ---

Je kunt deze vergelijkingen gebruiken om `if` instructies te maken: code die alleen zou moeten worden uitgevoerd _als_ wat tussen haakjes staat (de **voorwaarde**) waar is. Hier wordt de instructie `print` binnen de instructie `if` alleen uitgevoerd als de waarde van `mijn_getal` groter is dan `100`;

```python
if(mijn_getal > 100):
    print("Dat is een groot getal!")
```

#### Inspringing
Merk op dat de `print` binnen de `if` instructie is **ingesprongen**. Dat betekent dat er vier spaties voor zijn gezet.

Python heeft deze spaties nodig om je programma te begrijpen!

Voeg dat kleine beetje code nu samen met je programma van de vorige kaart.

--- task ---

Verander het programma zo dat het er zo uitziet:

```python
naam = input("Wat is je naam?")
mijn_getal = input("Hoi "+naam+" kies een getal")
mijn_getal = int(mijn_getal)
print("Jouw getal is "+str(mijn_getal))

if(mijn_getal > 100):
    print("Dat is een groot getal!")
```

--- /task ---

--- task ---

Voer het nu uit en probeer verschillende getallen boven en onder de 100 om te zien wat er gebeurt. Wat zou er gebeuren als je precies 100 invoert?

--- /task ---
