# pagina-meester

Een Claude-skill voor je landingspagina of homepage. Eerst zoekt hij waar bezoekers afhaken, daarna herschrijft hij de pagina zelf.

## Wat het doet
Je plakt de tekst of de url van je pagina. Je zegt voor wie de pagina is en wat de bezoeker moet doen. Je krijgt terug:
- De 5-secondentest: snapt een vreemde wat je doet, voor wie, en wat de volgende stap is?
- De 3 grootste lekken, de grootste eerst, elk met het stuk tekst waar het misgaat.
- Een nieuw bovenste scherm: kop, subkop, één knop, een regel onder de knop en een bewijsregel.
- Wat eruit kan, en de volgorde van de blokken eronder.
- De oude en de nieuwe kop naast elkaar.

Je aanbod en je prijs blijven hetzelfde. Alleen de pagina wordt duidelijker.

Voorbeeld: een glazenwasser met vijf even zware knoppen en zijn cv bovenaan. Na de skill staat er één kop ("Glazenwasser in Den Bosch en Rosmalen") en één knop ("Vraag een prijs aan"), en het bewijs staat direct onder de kop.

## Installeren in 3 stappen
1. Open Claude Code.
2. Plak dit: `Maak hier de skill pagina-meester van.` Of zet de map `pagina-meester` in `~/.claude/skills/`.
3. Typ `/pagina-meester` en plak de tekst of de url van je pagina.

## Wat erin zit
- De 5-secondentest.
- 7 lekken: een kop zonder dienst, een verhaal over de eigenaar in plaats van over de klant, lege woorden, te veel knoppen, verstopt bewijs, angst bij de knop en rommel.
- De nieuwe opbouw van het bovenste scherm: kop, subkop, knop, de regel onder de knop en een bewijsregel.
- Wat je schrapt en de volgorde van de rest.
- Regels: alleen echte reviews en cijfers. Wat onbekend is, komt tussen [haken] zodat jij het invult.

## Waar het op leunt
Op openbare bronnen: Don't Make Me Think (Steve Krug), Building a StoryBrand (Donald Miller), Influence (Robert Cialdini), de aandachtsratio van Oli Gardner, het LIFT-model van Chris Goward en de 5-secondentest. Daarnaast op onze eigen regels: bewijs gaat boven de belofte en we verzinnen geen cijfers. Geschreven door JWRN, in het Nederlands.
