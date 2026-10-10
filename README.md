# BromRoute v0.3 — experimentele eigen router

Een demonstratie die zelf een route zoekt in een beperkte uitsnede van OpenStreetMap, met conservatieve wegtypefilters. De router is **niet geschikt als verkeersnavigatie**. Onvolledige tagging, verkeersborden, turn restrictions, toegangsuitzonderingen en afsluitingen zijn niet betrouwbaar afgedekt. Geen route is geen bewijs dat er geen route bestaat; een getekende route is geen bewijs van wettelijke toegankelijkheid.

## Installatie op GitHub Pages
Upload `index.html` en `README.md` naar de hoofdmap van de bestaande repository. De bestaande `manifest.webmanifest` en `sw.js` mogen blijven staan. Als een oudere versie zichtbaar blijft: harde refresh met Ctrl+F5; eventuele oude service-worker-cache kan het resultaat beïnvloeden.

## Werking
Nominatim zoekt plaatsen, Overpass haalt OSM-wegen op, browser-JavaScript bouwt een gerichte graaf en Dijkstra berekent een proefroute. De toepassing weigert grotere afstanden, ontbrekende data en fouten. Er is geen fallback naar autorouting.
