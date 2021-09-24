## Je eerste Python-programma

Tijd voor je eerste stukje Python. Je gaat de computer hallo tegen iedereen laten zeggen.

--- task ---

Typ dit in Trinket:

```python
print("Hallo allemaal")
```

--- /task ---

--- task ---

Voer de code uit en kijk wat er gebeurt!

--- /task ---

--- task ---

Probeer wat tussen de `"` symbolen staat te veranderen, misschien door je naam toe te voegen, en het opnieuw uit te voeren.

--- /task ---

--- task ---

Voeg nu nog een regel toe, onder de bestaande regel:

```python
print ("Hallo allemaal")
print ("De Code roept naar jou. Laat het maar binnen komen.")
```

--- /task ---

--- task ---

Voer het opnieuw uit.

--- /task ---

Zie je hoe de tekst (een **string**) van de tweede `print` op een nieuwe regel staat? Dit komt omdat de instructie, die de computer krijgt wanneer je het vertelt om een `print` te doen, is:

     1. Lees de code tussen de haakjes en bepaal het resultaat
     2. Zodra je hebt uitgevonden wat er staat, `print` dat op het scherm
     3. Zet een onzichtbare "begin een nieuwe regel" instructie aan het einde

Waarom moet de computer uitzoeken wat de code tussen die haakjes betekent? Dat komt doordat de computer die tekenreeks kan samenvoegen uit de delen die je hem geeft.

Probeer het uit!

--- task ---

Gebruik de volgende code, maar zet je naam tussen de `"` symbolen waarin `"mijn naam"` staat.

```python
naam = "mijn naam"
print("Hallo "+naam)
print("De Code roept naar jou. Laat het gewoon binnen.")
```

--- /task ---

--- task ---

Voer nu je code opnieuw uit en bekijk het resultaat!

--- /task ---

--- collapse ---
---
title: De spatie na "Hallo"
---

Je moet een spatie toevoegen na "Hallo", anders krijg je gewoon "Hallomijn naam", omdat Python niet weet hoe Nederlands eruit ziet!

--- /collapse ---

--- collapse ---
---
title: Hoe werkt de nieuwe code?
---

Je hebt een **variabele** genaamd `naam` gemaakt. Een variabele is als een doos in de computer met een label erop. Je kunt er alles in stoppen wat je wilt. Vervolgens kun je het label gebruiken om Python het ding dat in de doos zit te laten ophalen en in je code te gebruiken.

+ Dus eerst heb je de variabele `naam` gemaakt en er `"mijn naam"` in opgeslagen.

+ Op de volgende regel gebruikte je het `+` symbool gevolgd door de variabele om je naam toe te voegen aan het einde van de tekenreeks (string) na de begroeting.

--- /collapse ---
