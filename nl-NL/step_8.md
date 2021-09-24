## Maak een spel om getallen te raden

Dus je hebt nu geleerd over:
  * `print` instructies uit om met je gebruikers te praten
  * variabelen, die een manier zijn om ons programma waarden te laten onthouden en bij te werken
  * strings, die stukjes tekst zijn
  * `input` voor het verkrijgen van informatie van onze gebruiker
  * wiskunde: hoe wiskunde te doen met een getal
  * gehele getallen, dit zijn getallen om mee te rekenen
  * `if` instructies, om je code iets te laten doen op basis van een voorwaarde
  * `while` lussen, om je code iets te laten blijven doen totdat een voorwaarde niet waar is

Je kunt deze tools en commando's gebruiken om dit spel te maken:
  * Er is een getal (een geheel getal), tussen 1 en 9, dat het programma in het geheim kiest
  * Spelers mogen 5 keer raden om het getal te vinden
  * Het spel leert spelers de regels
  * Spelers krijgen na elke poging te horen of het getal lager, hoger of correct is, en hoeveel keer ze nog mogen raden
  * Als spelers goed raden, krijgen ze een speciaal overwinningsbericht
  * Als spelers vijf keer verkeerd gokken, is het spel voorbij en verliezen ze

Je kunt een voorbeeld van het spel spelen op [dojo.soy/py-dice](http://dojo.soy/py-dice){:target="blank"}.

Je mist nog maar één ding om dit spel te kunnen schrijven: een manier om een willekeurig getal tussen 1 en 9 te krijgen. De code om dit te doen gaat iets verder dan wat we tot nu toe hebben behandeld, maar je kunt deze nu gebruiken zonder precies te begrijpen hoe het werkt.

--- task ---

Zet dit als de **eerste regel** in je programma:

```python
from random import randint as dobbelsteen
```

--- /task ---

Nu kun je overal waar je een willekeurig getal tussen 1 en 9 nodig hebt gewoon `dobbelsteen(1,9)` gebruiken. Bijvoorbeeld:

```python
geheim_getal = dobbelsteen(1,9)
```

--- task ---

Start een nieuw Python-programma en probeer het spel nu te maken!

--- /task ---

Vergeet niet om te gebruiken wat je in eerdere stappen van dit project hebt geleerd.

Succes!

--- hints ---


--- hint ---

Je kunt het aantal keren raden bijhouden dat spelers hebben gebruikt (of over hebben, afhankelijk van hoe je het bekijkt!) door een variabele te gebruiken. Je moet code schrijven om de waarde te wijzigen na elke gok.

Schrijf vervolgens de juiste voorwaarde voor je `while` lus om te controleren of spelers al hun keren raden hebben opgebruikt.

--- /hint ---

--- hint ---

Probeer variabelen te gebruiken om ook enkele van de andere getallen op te slaan, zoals de twee getallen waartussen spelers moeten raden, en het totale aantal toegestane keren raden.

Je programma zal prima werken, zelfs als je dit niet doet, maar het is meestal een goed idee om dingen met variabelen te definiëren. Eén reden is dat het je leven makkelijker maakt als je later besluit deze waarden te veranderen: dan is het enige dat je moet veranderen de waarden die je bovenaan in je programma toekent, en je hoeft niet alle plaatsen te veranderen waar je hun waarden hebt gebruikt.

--- /hint ---

--- /hints ---

Als je vastzit, of wanneer je klaar bent, kun je mijn antwoord bekijken op [dojo.soy/python-ans](http://dojo.soy/python-ans){:target="blank"}. Maak je geen zorgen als die van jou er heel anders uitziet — dat maakt niet uit, zolang het maar werkt.

***
Dit project werd vertaald door vrijwilligers:

Robert-Jan Kempenaar
Sanneke van der Meer
Max Schaaper

Dankzij vrijwilligers kunnen we mensen over de hele wereld de kans geven om in hun eigen taal te leren. Jij kunt ons helpen meer mensen te bereiken door vrijwillig te starten met vertalen - meer informatie op [rpf.io/translate](https://rpf.io/translate).