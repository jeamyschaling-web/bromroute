# BromRoute v0.1

Mobielvriendelijk prototype met Leaflet, OpenStreetMap, Nominatim en een OSRM-demo-autoprofile.

**WAARSCHUWING:** De routes zijn NIET gecontroleerd op brommobieltoegang en mogen NIET als rijnavigatie gebruikt worden. De OSRM-demo is alleen geschikt voor licht testen, niet voor productie.

## Starten

Pak het ZIP-bestand uit. Open een terminal in deze map en voer `python -m http.server 8000` uit. Open vervolgens `http://localhost:8000` op de computer. Voor locatie op een telefoon is HTTPS vereist: publiceer de map via een statische HTTPS-host, bijvoorbeeld GitHub Pages. Installeer via de browseroptie 'Toevoegen aan startscherm'.

## Volgende stap

Bouw een eigen router met voertuig-specifieke toegang, max 45 km/u, Nederlandse verkeersregels, gecontroleerde OSM-tags en actuele restricties. Valideer routes en ontbrekende data vóór gebruik onderweg. Voor productie eigen of contractueel toegestane tile/geocode/routing-infrastructuur inzetten en OSM-attributie behouden.
