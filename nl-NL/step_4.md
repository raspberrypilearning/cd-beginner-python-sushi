## Praat met de gebruiker

De computer je naam aan het einde van `"Hallo"` laten plakken, is leuk, maar waarom schrijf je niet gewoon `"Hallo [mijn naam]"`? Omdat je niet hoeft te weten wat er zal worden opgeslagen in een **variabele** wanneer je het programma schrijft. Je kunt zelfs aan de gebruiker van het programma vragen welke naam moet worden opgeslagen in de variabele.

--- task ---

Werk je Python-programma bij zodat het de gebruiker vraagt om de tekst die in de variabele moet worden geplaatst:

```python
naam = input("Wat is je naam?")
print("Hallo "+name)
print("De Code roept je. Laat het maar binnen.")
```

--- /task ---

--- task ---

Probeer het uit te voeren. Zodra je je naam hebt ingetypt, druk je op de <kbd>Enter</kbd> toets.

--- /task ---

--- task ---

Probeer nu een getal op te vragen bij je gebruiker door je code te wijzigen zodat die er als volgt uit ziet:

```python
naam = input("Wat is je naam?")
mijn_getal = input("Hoi "+naam+", kies een getal")
print("Jouw getal is "+mijn_getal)
```

--- /task ---

Merk op dat je de `+` aan beide kanten van een variabele kunt gebruiken!

--- task ---

Voer dit programma uit, beantwoord de vragen en kijk wat er gebeurt.

--- /task ---

Wat als je een ander getal wilt optellen bij het getal dat opgeslagen is in je nieuwe variabele? Laten we dat proberen.

--- task ---

Voeg een regel toe aan je programma die `1` optelt bij de `mijn_getal` variabele:

```python
naam = input("Wat is je naam?")
mijn_getal = input("Hoi "+naam+" kies een getal")
mijn_getal = int(mijn_getal) + 1
print("Jouw getal is "+str(mijn_getal))
```

--- /task ---

--- collapse ---
---
title: Hoe werkt de nieuwe code?
---

Je hebt net de waarde van een variabele genomen, deze aangepast en weer opgeslagen in dezelfde variabele — allemaal op dezelfde regel!

Waarom heeft de code nu `int()` en `str()` rond `mijn_getal`?

Dat is omdat Python een verschil maakt tussen het getal '1' dat het gebruikt voor wiskunde en het getal '1' dat het als tekst in een zin schrijft. `int( )` om een variabele zetten vertelt het om het te behandelen als een **integer** (een geheel getal in de wiskunde), en het plaatsen van `str( )` om een variabele heen vertelt het om het te behandelen als een **string** (een tekenreeks).

**Integers** en **strings ** zijn **types** variabele, en bepaalde stukjes code (zoals `+` en `print`) werken alleen als de variabelen die je geeft het juiste type zijn.

--- /collapse ---

### Wiskunde in Python

Je hebt hier gezien hoe je kunt optellen, maar je kunt ook:
* Aftrekken met `-`
* Vermenigvuldigen met `*`
* Delen met `/`
