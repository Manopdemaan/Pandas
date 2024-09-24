# Opdracht: Meest Waardevolle Voetbalclubs voor Pan al Andas

## Omschrijving
Nadat ik goed werk had geleverd voor McPandas, ben ik gevraagd door sjeik Pan al Andas om uit te zoeken welke voetbalclubs de duurste selecties hebben. Pan is groot fan van voetbal en wil graag een club kopen die de Champions League kan winnen. Hij denkt dat de club met de duurste spelers ook de beste is. Mijn taak was om te achterhalen welke tien clubs de meeste waarde hebben op basis van de spelers.

Hiervoor moest ik een aantal stappen doorlopen:
1. Het CSV-bestand `fifa_ratings.csv` inladen in een DataFrame.
2. De totale waarde van de spelers (kolom `value_eur`) berekenen per club.
3. De tien duurste voetbalclubs laten zien.
4. Een barchart maken waarin de tien clubs gerangschikt staan van duur naar minder duur.

## Wat ik heb geleerd
In deze opdracht heb ik geleerd hoe ik de functie `groupby` in pandas kan gebruiken om data te groeperen en op te tellen. Dit was de eerste keer dat ik met `groupby` werkte, en ik vond het heel handig. Hiermee kon ik eenvoudig de waarde van de spelers per club bij elkaar optellen en zo de duurste clubs achterhalen.

Het leuke aan `groupby` is dat je snel statistieken kunt maken over bepaalde groepen in je data. In dit geval ging het om clubs en de waarde van hun selectie. Dit maakte het makkelijk om een ranglijst van de duurste clubs te maken.

