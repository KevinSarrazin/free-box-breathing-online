# Gratis øvelse i boksvejrtrækning online

Andre sprog: [English](README.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Español (México)](README.es-MX.md) · [Português (Brasil)](README.pt-BR.md) · [Italiano](README.it.md) · [Nederlands](README.nl.md) · [Polski](README.pl.md) · [Svenska](README.sv.md) · [Русский](README.ru.md) · [Bahasa Indonesia](README.id.md) · [हिन्दी](README.hi.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [简体中文](README.zh-Hans.md) · [繁體中文（香港）](README.zh-HK.md)

En gratis guidet øvelse i boksvejrtrækning, der kører i din browser, i én enkelt HTML-fil.

Prøv den online: https://kevinsarrazin.github.io/free-box-breathing-online/da/

Følg lyset rundt om firkanten. Hver side er ét trin på 4 sekunder:

- **Ånd ind**: lyset løber hen langs toppen, og cirklen vokser.
- **Hold** med fyldte lunger: højre side.
- **Ånd ud**: bunden, og cirklen bliver mindre.
- **Hold** med tomme lunger: venstre side.

Sessioner på 1, 3 eller 5 minutter slutter altid med en hel runde. Først kommer en nedtælling på 3 sekunder, en blød lyd kan markere hvert trin, sessionen sættes på pause, når du forlader fanen, og der tages hensyn til indstillingen for reduceret bevægelse.

Intet bliver gemt, og intet bliver sendt videre: ingen sporing, intet eksternt script, ingen tilmelding.

## Kør den

Åbn `index.html` i en hvilken som helst browser. Intet build-trin og ingen afhængigheder.

## Sådan får du mest ud af den

Træk vejret roligt uden at presse. Føles det ubehageligt at holde vejret, så gør den tid kortere: målet er en rolig, jævn rytme, ikke en præstation.

Øvelsen er ikke en medicinsk behandling. Bliver du svimmel eller får det dårligt, så stop og træk vejret normalt.

## Sæt øvelsen på dit websted

Du kan gratis vise hele øvelsen i boksvejrtrækning fra upchin.app på din egen side. Den findes på 17 sprog: sæt `data-lang` (eller `lang=` i rammens adresse) til `en`, `fr`, `de`, `es-MX`, `pt-BR`, `it`, `nl`, `pl`, `da`, `sv`, `ru`, `id`, `hi`, `ja`, `ko`, `zh-Hans`, `zh-HK`.

**Med scriptet** ([`box-breathing-embed.js`](box-breathing-embed.js)), som tilpasser rammens højde til indholdet:

```html
<div data-upchin-embed="box-breathing" data-lang="da">
  <p>Boksvejrtrækning fra <a href="https://upchin.app/da/vaerktoejer/boksvejrtraekning">Upchin</a></p>
</div>
<script src="https://kevinsarrazin.github.io/free-box-breathing-online/box-breathing-embed.js" async></script>
```

**Uden script**, hvis dit websted kun accepterer HTML:

```html
<iframe src="https://upchin.app/embed/box-breathing?lang=da" title="Boksvejrtrækning" width="100%" height="1450" style="border:0;max-width:100%" loading="lazy" allow="clipboard-write"></iframe>
<p>Boksvejrtrækning fra <a href="https://upchin.app/da/vaerktoejer/boksvejrtraekning">Upchin</a></p>
```

Lad venligst kildeangivelsen under øvelsen blive stående. Scriptet sætter rammen ind ved siden af og fjerner aldrig kildeangivelsen.

## Fuld version

Den guidede [boksvejrtrækning på upchin.app](https://upchin.app/da/vaerktoejer/boksvejrtraekning) findes på 17 sprog. Du kan indstille hvert trin fra 1 til 20 sekunder, få vibration på telefonen og trække vejret uden tidsgrænse.

Øvelsen er lavet af holdet bag Upchin. Med webstedets egne ord: »Dine apps er designet til at få dig til at scrolle. Upchin er designet til at give dig din tid tilbage.« Appen til iPhone bruger Apples Skærmtid til at hjælpe dig med at [holde pauser fra telefonen](https://upchin.app/da), med friktion på det rigtige tidspunkt i stedet for løftede pegefingre.
