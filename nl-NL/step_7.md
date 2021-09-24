## Blijf vragen

Je kunt gebruikers nu vragen om een getal te kiezen, controleren of het de juiste waarde heeft en, als dat niet zo is, hen vertellen dat het niet klopt. Wat als je het programma door wilt laten gaan totdat je een antwoord krijgt dat de juiste waarde heeft?

Je hebt een manier nodig om je vraag steeds opnieuw te stellen totdat je het juiste soort antwoord krijgt. De manier om dit te doen in computerprogrammeren heet een **lus**. Je gaat er één gebruiken die de `while` lus wordt genoemd.

Een `while` lus lijkt een beetje op een `if` instructie: er zit code in die alleen wordt uitgevoerd als de voorwaarde tussen de haakjes waar is. Het verschil is dat een `while` lus herhaald wordt totdat de voorwaarde onwaar is. Je moet ervoor zorgen dat er altijd een uitweg is uit je `while` lus, anders loopt hij voor altijd! Het ziet er zo uit:

```python
while(mijn_getal < 100):
    mijn_getal = input("Hoi "+naam+" kies een getal dat groter is dan 100")
    mijn_getal = int(mijn_getal)
```

--- task ---

Now add a `while` loop to your program, to keep asking users for a number until they give that's larger than 100.

```python
naam = input("Wat is je naam?")
mijn_getal = 0

# Herhaal zolang als "mijn_getal" kleiner is dan 100
while(mijn_getal < 100):
    # Vraag gebruikers om een getal
    mijn_getal = input("Hoi "+naam+" kies een getal dat groter is dan 100")
    # Converteer het antwoord van de gebruiker van een string naar een integer
    mijn_getal = int(mijn_getal)
    print("Je getal is "+str(mijn_getal))
    # Controleer of het getal groter is dan 100
    if(mijn_getal > 100):
        print("Dat is een groot getal!").
    elif(mijn_getal > 90):
    print("Bijna klaar! Probeer het nog eens!")
    else:
    print("Dat getal is te klein! Probeer het opnieuw!")
    # Als mijn_getal kleiner is dan 100, herhaal dan opnieuw
```

--- /task ---

--- collapse ---
---
title: Wat is die extra tekst – is het onderdeel van de code?
---

De extra regels tekst die beginnen met een `#` symbool zijn **opmerkingen**.

In de meeste programmeertalen kun je opmerkingen schrijven in je code. Dit zijn opmerkingen over wat de code doet, die de computer zelf negeert. Je kunt ze voor jezelf schrijven als herinneringen, of voor andere programmeurs die je code willen gebruiken. In Python beginnen opmerkingen met `#` en lopen ze tot aan het einde van de regel.

--- /collapse ---
