# De StalKas

Nederlandstalige, gratis offline PWA voor kosten en verbruik op stal. Geen server of account nodig.

## Installeren

- iPhone: open de website in Safari → Delen → Zet op beginscherm.
- Android: open in Chrome → menu → App installeren / Toevoegen aan startscherm.
- Open daarna steeds via hetzelfde app-icoon. Laad de website eerst eenmaal online voor offline gebruik.

## Gegevens bewaren

Wijzigingen worden automatisch lokaal opgeslagen, met dezelfde bestaande sleutel `stal-onderwater-voer-v1`. Afsluiten, opnieuw openen en updates behouden de gegevens. Alleen browsegeschiedenis wissen laat lokale opslag doorgaans staan. Websitegegevens wissen, privémodus, automatische opruiming of verwijderen van de app kan gegevens verwijderen. De knop **Opslag beschermen** vraagt blijvende opslag aan waar de browser dit ondersteunt; dit biedt geen garantie tegen handmatig wissen.

**Reservekopie (.txt)** bewaart alle maanden, profielen en eigen producten. Bewaar het bestand buiten de browser, bijvoorbeeld in Bestanden, iCloud of Drive. Terugzetten ondersteunt zowel volledige JSON-reservekopieën als oudere leesbare tekstexports per maand. Er is geen synchronisatie tussen telefoons; lokale data van een los HTML-bestand verhuizen niet vanzelf naar de website.

## Hosting

De statische website staat in de repositoryroot. GitHub Pages: Settings → Pages → Deploy from a branch → main → /(root). De workflow probeert dit automatisch in te stellen. Als de repositorytoken dit niet mag, is eenmalig instellen door een beheerder nodig.

## Lokaal starten

`python3 -m http.server 8000` in deze map, open vervolgens `http://localhost:8000`. Geen build of externe bibliotheken nodig.
