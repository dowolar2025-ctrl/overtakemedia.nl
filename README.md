# overtakemedia.nl

Website van Overtake Media, gepubliceerd via GitHub Pages.

## Nieuwe versie online zetten

Verander je iets aan een pagina of aan `stijl.css`, hoog dan één nummer op, op vier plekken tegelijk:
`stijl.css?v=<nummer>` in `index.html`, `films.html` en `websites.html`, en het nummer in `versie.txt`.
Een bezoeker met een oude pagina in het geheugen krijgt dan vanzelf één keer de nieuwe versie.

## Besloten filmpagina voor een klant

Voorbeeld en sjabloon: `concept/voorbeeld-film-q8r3/index.html`.

1. Kopieer die map naar `concept/<klant>-<4 willekeurige tekens>/` (de code maakt het adres onraadbaar; `concept/` staat in `robots.txt` op Disallow en de pagina heeft `noindex`).
2. Zet de film met watermerk als `film.mp4` en het startbeeld als `film.jpg` in die map, en verwijs daar in de `<video>` naar.
3. Vervang de bedrijfsnaam (titel, "Alleen voor …", onderwerp van beide mailknoppen), het label "Proefversie … · datum" en de tekst in de akkoordmail.
4. Online zetten zoals altijd en de link aan de klant sturen. De akkoordknop blijft staan (besluit 14-10-2026): de klant verstuurt het akkoord zelf per mail.
