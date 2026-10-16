# BromRoute v2.2

Experimentele routevergelijker voor brommobielen. Niet gebruiken als rijnavigatie.

Nieuw: opslag van opgehaalde OpenStreetMap-weggegevens in IndexedDB, met een tijdelijke sessionStorage-terugval. Verse cache (<24 uur) wordt gebruikt zonder serveraanvraag; als de servers niet bereikbaar zijn, kunnen gegevens van maximaal zeven dagen oud als duidelijk gemarkeerde noodoplossing worden gebruikt. Er wordt alleen exact dezelfde kaartgebiedsquery uit de cache gebruikt. Voor een nieuw gebied zonder opgeslagen gegevens is een werkende Overpass-server nodig.

Upload index.html en README.md naar de hoofdmap van de bestaande GitHub-repository.
