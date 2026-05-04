# Performance Audit 

Doe een Performance audit op een bestaande website uit je eigen omgeving en rapporteer daarover.



## Titel Website
Performance Audit  BikerOutfit.nl
**Samenvatting**
Voor deze performance audit heb ik bikeroutfit.nl getest, een van de grootste motorkleding verkopers in Amsterdam. De audit is uitgevoerd met drie tools: Lighthouse, PageSpeed Insights en WebPageTest.
Resultaten:
Lighthouse Mobile: 55 Lighthouse Desktop: 97
Op mobile scoort de website matig, op desktop uitstekend. Het grootste verschil zit in de LCP, op mobile 10.6 seconden tegenover 0.9 seconden op desktop. Dit komt door grote niet geoptimaliseerde afbeeldingen die op mobile veel langer laden.
PageSpeed Insights Mobile: 46 PageSpeed Insights Desktop: 72
Bij echte gebruikers scoort de website lager dan in de lokale Lighthouse test. De website slaagt niet voor de Core Web Vitals evaluatie vanwege een te hoge Cumulative Layout Shift van 0.23. Dit betekent dat elementen op de pagina verschuiven tijdens het laden.
**WebPageTest**
De waterfall chart laat zien dat de pagina 88 bestanden laadt in 8 seconden. De grootste problemen zijn zware JavaScript bestanden van het webshop platform en tracking scripts van Google en Facebook.
**Grootste problemen**
De LCP op mobile is met 10.6 seconden veel te hoog. Afbeeldingen zijn niet geoptimaliseerd en er wordt veel ongebruikte CSS en JavaScript geladen. Google Tag Manager en andere tracking scripts laden laat maar zijn wel zwaar.
**Oplossingen**
Afbeeldingen optimaliseren naar moderne formaten zoals WebP, ongebruikte CSS en JavaScript verwijderen en renderblokkerende bestanden later laden.

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
