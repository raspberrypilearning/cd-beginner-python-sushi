## Controleer meer dan één ding

Wat als je wilt controleren of het getal van de gebruiker groot genoeg is, en hun wilt laten weten als dit niet zo is?

Je kunt voorwaarden combineren door `and` en `or` te gebruiken. Dus je zou als volgt code kunnen schrijven:

```python
if(mijn_getal >= 20 and mijn_getal < 30):
    print("Dat getal is minstens twintig en onder de dertig!")
```

Of bijvoorbeeld:

```python
if (eten == "Cake" of eten == "Chocolade" of eten == "Taart"):
    print ("Klinkt lekker!")
```

--- task ---

Controleer of het getal dat de gebruiker geeft groter is dan 100. Vervolgens feliciteer je de gebruiker met het geven van een getal dat groot genoeg is, of vertel je hem dat het door hem gekozen getal niet groot genoeg is.

Probeer dit:

```python
naam = input("Wat is je naam?")
mijn_getal = input("Hallo "+ naam +" kies alsjeblieft een getal dat groter is dan 100")
mijn_getal = int (mijn_getal)
print("Je getal is" + str(mijn_getal))

if (mijn_getal > 100):
    print("Dat is een groot getal!")
else:
    print("Dat getal is te klein!")
```

--- /task ---

De code binnen de `else` instructie wordt uitgevoerd wanneer de voorwaarde tussen haakjes van de `if` instructie _niet_ waar is.

### Meer voorwaarden

Wat als je de gebruiker wilt vertellen wanneer ze dichtbij zijn, bijvoorbeeld als ze een getal boven de `90` hebben ingevoerd?

Dan kun je een `elif` instructie gebruiken! Die naam zijn de woorden 'else' en 'if' aan elkaar geplakt. De code binnen een `elif` instructie wordt alleen uitgevoerd als de voorwaarde in de `if` instructie _niet_ waar is **en** de voorwaarde tussen de haakjes van de `elif` instructie _wel_ waar is.

Dit is wat je toevoegt om ervoor te zorgen dat het programma de gebruiker vertelt dat ze dichtbij zijn:

```python
elif(min_getal > 90):
    print("Je bent er bijna!")
```

--- task ---

Voeg nu die regels toe aan de rest van je programma. Merk op dat de `elif` instructies tussen de `if` en de `else` instructies moeten komen.

```python
naam = input("Wat is je naam?")
mijn_getal = input("Hallo "+ naam +" kies alsjeblieft een getal dat groter is dan 100")
mijn_getal = int (mijn_getal)
print("Je getal is" + str(mijn_getal))

if (mijn_getal > 100):
    print("Dat is een groot getal!")
elif(mijn_getal > 90):
    print("Je bent er bijna!")
else:
    print("Dat getal is te klein!")
```

--- /task ---
