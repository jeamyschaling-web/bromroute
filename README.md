# BromRoute v1.3 — experimentele testversie

- Bouwt voort op v1.2 met adresinvoer, kaart, routevarianten en Overpass-fallback.
- Sluit expliciet verboden wegen (`access`, `vehicle`, `motor_vehicle`, `motorcar`: `no`, `private`, etc.) uit.
- Sluit `destination` / `customers` / `permissive` conservatief uit als doorgaande route. Dit kan legale routes ten onrechte blokkeren.
- Toont per wegvak een toegangsoordeel en de OSM-tag of ontbrekende informatie.
- Conditionele toegangsregels worden **niet** geïnterpreteerd; routes kunnen daardoor nog ongeschikt zijn.
- Dit is geen betrouwbare navigatie en niet geschikt voor gebruik tijdens het rijden.
- OSM-tags zijn geen juridische verificatie; lokale verkeersborden, uitzonderingen, turn restrictions en tijdelijke afsluitingen ontbreken mogelijk.
