# De StalKas — instructies voor Codex

Dit is de bestaande Nederlandstalige HTML/PWA voor kosten en verbruik op stal. Repository: `riannesplinter/De-stalkas` (GitHub Pages). Behoud de huidige functies en gebruikersdata bij elke wijziging.

## Doel
Publiceer deze bestanden in de bestaande repository. GitHub Pages moet via `main` / `/ (root)` worden aangeboden en de site moet op Android en iPhone als webapp op het beginscherm kunnen worden gezet.

## Behoud functies
- Bruincafé-stalstijl, titel **De StalKas**, ondertitel **Kosten & verbruik**.
- Boxhuur €150 per box per maand; hooi €6 per baal; stro €6 per baal. Plus/min-knoppen.
- Kuil: 1 krat per dag €30/maand, 2 kratten per dag €60/maand, onbeperkt €90/maand, zelf invullen (losse kistjes tellen niet automatisch mee). Duidelijke waarschuwing bij maandtotaal.
- Zelf producten toevoegen met naam, prijs, aantal plus/min en drie afbeeldingkeuzes (paardendrol met paraplu, wortelzak, paardentrailer). De keuzemenu's moeten pas verschijnen wanneer op het lege plaatje wordt gedrukt. Geen namen onder keuzeplaatjes.
- Grote bedragen, compacte afbeeldingen die binnen hun vierkanten blijven.
- Automatische opslag + handmatige OPSLAAN-knop; maandwissel; downloadbare PDF-maandoverzicht en tekstreservekopie en terugzetten.
- Geen betaalde services en geen accounts/server nodig voor de basisversie. De gegevens zijn per apparaat lokaal en synchroniseren niet. Leg dit eerlijk uit.

## Technische controle vóór publicatie
- Controleer `index.html`, `manifest.webmanifest`, `sw.js` en alle iconen.
- Verifieer dat de PDF-download echt een download oplevert en niet alleen een voorbeeld opent, voor zover de browser dit toestaat.
- Test mobiel scherm 360px, Android Chrome en iPhone Safari waar mogelijk.
- Controleer dat bestaande `localStorage`-sleutel/data bij updates behouden blijft en migratie van bestaande exportbestanden mogelijk is.
- Pas geen prijs- of productlogica aan zonder expliciete opdracht.
- Maak bij publicatie geen claims over live-URL tot de GitHub Pages-url echt bereikbaar is.
