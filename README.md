# Homey-wanddashboard

Dashboard voor een Homey Pro, getoond op een wandtablet (Fully Kiosk).

- `dashboard.html` — het dashboard zelf. Wordt door de lader van GitHub opgehaald.
- `versie.txt` — huidige versie; het dashboard herlaadt zichzelf als deze verandert (controle elke 5 minuten).
- `lader/index.html` — kleine pagina die eenmalig op de Homey staat (Micro Web Server, map `/dashboard`).

De foto's (`img/`) en de API-sleutel staan **niet** in deze repository: de foto's staan op de Homey naast de lader,
de API-sleutel alleen in de browser van de tablet.
