## Mijn DDA Website

Dit is een website die ik zelf gemaakt heb aan de hand van de designs die ik gekregen heb van de opdrachtgever van DDA. Ik heb voorlopig de overzichtspagina van leden van de agency en de detail pagina van deze leden van de agency gemaakt. 

Live link: https://user-experience-enhanced-website-m6o9.onrender.com

<img width="1512" alt="Scherm­afbeelding 2025-04-22 om 10 17 13" src="https://github.com/user-attachments/assets/a3bd7fab-4061-4935-96c7-aeda84a8a440" />

# Performance Audit Test
## Lighthouse test
Link naar lighthouse test: https://github.com/Brancovanbeek/performance-audit/wiki/Lighthouse-test

<img width="726" alt="Scherm­afbeelding 2025-04-22 om 20 11 15" src="https://github.com/user-attachments/assets/ad7623b7-98c5-430f-9970-25297ace947a" />

Desktop en mobile hadden dezelfde scores. Dit waren de problemen die verholpen kunnen worden: knoppen missen een toegankelijke naam, select-elementen hebben geen label en de headingstructuur is niet logisch opgebouwd.

## PageSpeed test
Link naar PageSpeed test: https://github.com/Brancovanbeek/performance-audit/wiki/PageSpeed-insights

<img width="1056" alt="Scherm­afbeelding 2025-04-22 om 20 37 16" src="https://github.com/user-attachments/assets/a7884d1e-fcb3-401a-b5dc-f0cfe18e4287" />

Desktop en mobile hadden dezelfde scores. De problemen zijn hetzelfde als bij de lighthouse test, namelijk: knoppen missen een toegankelijke naam, select-elementen hebben geen label en de headingstructuur is niet logisch opgebouwd.

## WebPage test
Link naar WebPage test: https://github.com/Brancovanbeek/performance-audit/wiki/WebPage-test

<img width="807" alt="Scherm­afbeelding 2025-04-22 om 20 52 11" src="https://github.com/user-attachments/assets/058a2856-d88e-4f4d-b0d9-184b2822b130" />

### Problemen:
Render-blocking requests: 3 CSS/JS-bestanden blokkeren de rendering van de pagina.
Toegankelijkheidsproblemen: 2 kritieke problemen die de toegankelijkheid beïnvloeden.


## Conclusie bevindingen

- **Toegankelijkheidsproblemen**: Knoppen missen namen, select-elementen hebben geen labels, en de headingstructuur is onlogisch.
- **Render-blocking requests**: 3 CSS/JS-bestanden blokkeren de rendering.

### Oplossingen:
- Voeg toegankelijke namen en labels toe.
- Herstructureer de headings.
- Optimaliseer de CSS/JS-bestanden om render-blocking te voorkomen.

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
