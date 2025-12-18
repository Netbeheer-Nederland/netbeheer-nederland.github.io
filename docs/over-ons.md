---
title: Over ons
nav_order: 9
---

{: .note }
Kijk gerust rond! Aan deze website wordt momenteel nog gewerkt.

# Over ons

**Onze missie:** netbeheerdata begrijpelijk en herbruikbaar maken door het publiceren van eenduidige definities.

De energietransitie vraagt om enorme hoeveelheden data. Om deze data effectief te kunnen delen tussen netbeheerders, marktpartijen en de overheid, moeten we dezelfde taal spreken. Team Semantiek faciliteert dit. Wij zijn een samenwerkingsverband van experts van de gezamenlijke regionale en landelijke netbeheerders, gefaciliteerd door Netbeheer Nederland.

## Onze kernproducten

Wij ontwikkelen drie kernproducten om grip te krijgen op data. Onderstaande afbeelding toont hoe deze producten zich tot elkaar verhouden. Daarin verwijst `MIM` naar een type informatiemodel volgens het [Metamodel Informatiemodellering](https://www.geonovum.nl/geo-standaarden/metamodel-informatiemodellering-mim).

![Modellen]({{ site.baseurl }}/assets/images/modellen.svg)

### De lagen

Om spraakverwarring te voorkomen, scheiden we de betekenis van de techniek:

* **Werkelijkheid**. Dit is de basis. Hierin leggen we de definities vast van de termen die we gebruiken (zoals `aansluiting`, `overdrachtspunt`).
* **Eisen & wensen**. Hier leggen we de relaties tussen begrippen en de bedrijfsregels vast. Bijvoorbeeld: *een aansluiting moet altijd één netbeheerder hebben*. Dit is onafhankelijk van hoe een systeem technisch werkt.
* **Systeemspecificatie**. Hier vertalen we de regels naar een structuur voor software (tabellen, berichten).

### Bron versus gebruik

Een belangrijk principe in onze architectuur is het onderscheid tussen 'waar de data woont' (bron) en 'hoe de data wordt toegepast' (gebruik).

* **De bron**. Voor de registers leggen wij als Team Semantiek de eisen vast. Hoe de softwareleverancier (bijvoorbeeld [EDSN](http://edsn.nl/) voor de centrale registers) of de netbeheerder dit vervolgens technisch opslaat in hun database, is hun eigen verantwoordelijkheid, zolang het maar voldoet aan de eisen, zodat de data uitwisselbaar blijven.
* **Het gebruik**. Voor het uitwisselen van gegevens leveren wij dataproductmodellen. Omdat uitwisseling standaardisatie vereist, leveren wij hierin zowel de context als de technische specificaties in één keer mee. Zo kunnen softwareontwikkelaars direct aan de slag.

## Samenhang en kwaliteit

De definities en regels in onze modellen zijn vaak een directe vertaling van externe verplichtingen. Input komt uit wetgeving of sectorafspraken vastgesteld in [Het Normo](https://hetnormo.nl/). Team Semantiek vertaalt deze input naar eenduidige informatiemodellen (MIM-2). Hierdoor versnellen we de implementatie bij netbeheerders en hun softwareleveranciers.

Een dataproductmodel is nooit strijdig met de registermodellen. We mogen data wel filteren of combineren voor een specifieke toepassing, maar we mogen de waarheid van de bron niet geweld aandoen.

Is er nog geen registermodel beschikbaar? Geen probleem. Omdat het begrippenkader op het hoogste niveau volledig is (dankzij het gebruik van [NBility](https://nbility-model.github.io/)-bedrijfsobjecten als topbegrippen), kunnen we dataproducten alvast definiëren en koppelen aan het juiste begrip. Zo kunnen we snel waarde leveren, terwijl we de begrippen verfijnen en de formele registermodellen op de achtergrond uitwerken.

## Contact

Heb je vragen over onze modellen of werkwijze? Of wil je bijdragen? Neem contact op via [teamsemantiek@netbeheernederland.nl](mailto:teamsemantiek@netbeheernederland.nl).
