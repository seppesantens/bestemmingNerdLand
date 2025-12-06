# Bestemming Nerdland
*Inspiratie nodig voor je volgende uitstap of reis?*

[Nerdland](https://maandoverzicht.nerdland.be/) to the rescue! Met deze toepassing vind je heel wat "Nerdland bestemmingen" op een interactieve kaart.
Klik op een bestemming om meer informatie te krijgen en luister direct naar het bijbehorende fragment.

Bekijk het resultaat op [GitHub Pages](https://seppesantens.github.io/bestemmingNerdLand/)

## Open source en open knowledge
De toepassing is gebaseerd op open source en open knowledge:
- De open source bibliotheek [MapLibre GL JS](https://maplibre.org/maplibre-gl-js/docs/) wordt gebruikt om de bestemmingen op de kaart te tonen
- De achtergrond waarop de bestemmingen getoond worden is gebaseerd op de open data van [OpenStreetMap](https://www.openstreetmap.org/)
- Informatie over de bestemmingen wordt gegeven door [Wikidata](https://www.wikidata.org/) en [Wikipedia](https://www.wikipedia.org/)

## Zelf bijdragen?
De toepassing is heel erg eenvoudig en dat mag gerust zo blijven. Pull requests worden aangemoedigd, maar vooral om de data aan te vullen.

De data zijn opgesplitst in 
- [NRDLplaces.geojson](https://github.com/seppesantens/bestemmingNerdLand/blob/main/NRDLplaces.geojson) met daarin:
	- een Wikidata item voor de bestemming
	- de geografische coördinaten van de bestemming

- [NRDLclips.geojson](https://github.com/seppesantens/bestemmingNerdLand/blob/main/NRDLclips.json) met daarin:
	- een Wikidata item voor de bestemming
	- een array met clips die elk volgende data bevatten:
		- de datum van de aflevering in het formaat YYYY-MM
		- een link naar de Nerdland aflevering op Soundcloud	
		- de tijdscode van het fragment