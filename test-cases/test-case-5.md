# Test Case 5
Verantwoordelijke: **Jelmer Smid**

## Doel
Testen van de Speed en Time implementatie in de simulator en controller.

## Omschrijving
Voor de mensen die Time implementeren: 
- Er wordt een bericht gestuurd naar de controller dat er een fietser staat bij het stoplicht waar Time gedisplayed wordt. De controller past de status van het stoplicht aan stuurt in het bericht naast status ook de Time mee. 

Voor de mensen die Speed implementeren: 
- De simulator stuur een bericht naar de controller met daarin de Speed. Als dit geimplementeerd is in de controller dient deze een bericht terug te sturen met daarin een bevestiging dat de Speed gezet is naar de aangevraagde snelheid. Indien dit niet geimplementeerd is in de controller wordt er geen bevestiging terug gestuurd en dient de snelheid niet te worden aangepast.

## Voorbeelden

Light voorbeeld:
```json
{
  "Lights": [
    {
      "Id": 101,
      "Status": 2,
      "Time": -1
    },
    {
      "Id": 102,
      "Status": 0,
      "Time": -1
    },
    {
      "Id": 103,
      "Status": 0,
      "Time": -1
    },
    {
      "Id": 104,
      "Status": 0,
      "Time": -1
    },
    {
      "Id": 105,
      "Status": 0,
      "Time": -1
    },
    {
      "Id": 106,
      "Status": 0,
      "Time": -1
    },
    {
      "Id": 107,
      "Status": 0,
      "Time": -1
    },
    {
      "Id": 108,
      "Status": 0,
      "Time": -1
    },
    {
      "Id": 109,
      "Status": 0,
      "Time": -1
    },
    {
      "Id": 110,
      "Status": 0
    },
    {
      "Id": 201,
      "Status": 0,
      "Time": -1
    },
    {
      "Id": 301,
      "Status": 0,
      "Time": 5
    },
    {
      "Id": 302,
      "Status": 0,
      "Time": 17
    },
    {
      "Id": 303,
      "Status": 0,
      "Time": -1
    },
    {
      "Id": 304,
      "Status": 0,
      "Time": -1
    },
    {
      "Id": 401,
      "Status": 0,
      "Time": -1
    },
    {
      "Id": 402,
      "Status": 0,
      "Time": -1
    },
    {
      "Id": 403,
      "Status": 0,
      "Time": -1
    },
    {
      "Id": 404,
      "Status": 0,
      "Time": -1
    },
    {
      "Id": 405,
      "Status": 0,
      "Time": -1
    },
    {
      "Id": 406,
      "Status": 0,
      "Time": -1
    },
    {
      "Id": 601,
      "Status": 0,
      "Time": -1
    }
  ]
}
```

Speed voorbeeld:

vraag van simulator aan controller om de snelheid 2X zo snel te maken:
```json
{
  Speed": 2.0
}
```
response van controller indien dit bevestigd wordt
```json
{
  Speed": 2.0
}
```
indien er geen reactie terug komt van de controller dient de snelheid in de simulator hetzelfde te blijven.

## Testuitvoering
Er is tijdens de les 30 minuten beschikbaar voor het valideren van de test. Niet alle combinaties van controllers en simulators kunnen in die 30 minuten worden getest. Probeer als koppel je controller en simulator met zoveel mogelijk andere controllers en simulators te testen.

Rapporteer jouw resultaten z.s.m. na de les aan de verantwoordelijke van deze test, zodat hij de resultaten in kaart kan brengen.

## Resultaten
| Koppel | Resultaat | Opmerkingen |
| --- | --- | --- |
| 1 | | |
| 2 | | |
| 3 | | |
| 4 | | |
| 5 | | |
| 6 | | |
| 7 | | |
| 8 | | |
| 9 | | |
| 10 | | |
| 11 | | |
| 12 | | |
| 13 | | |
| 14 | | |
