# Gratis box breathing-oefening online

Andere talen: [English](README.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Español (México)](README.es-MX.md) · [Português (Brasil)](README.pt-BR.md) · [Italiano](README.it.md) · [Polski](README.pl.md) · [Dansk](README.da.md) · [Svenska](README.sv.md) · [Русский](README.ru.md) · [Bahasa Indonesia](README.id.md) · [हिन्दी](README.hi.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [简体中文](README.zh-Hans.md) · [繁體中文（香港）](README.zh-HK.md)

Een gratis begeleide box breathing-oefening die in je browser draait, in één HTML-bestand.

Probeer het online: https://kevinsarrazin.github.io/free-box-breathing-online/nl/

Volg het licht rond het vierkant. Elke zijde is één stap van 4 seconden:

- **Adem in**: het licht loopt langs de bovenkant en de cirkel wordt groter.
- **Houd vast**, longen vol: de rechterkant.
- **Adem uit**: de onderkant, en de cirkel wordt kleiner.
- **Houd vast**, longen leeg: de linkerkant.

Sessies van 1, 3 of 5 minuten eindigen altijd met een volledige ronde. Eerst wordt er 3 seconden afgeteld, een zacht geluid markeert desgewenst elke stap, de sessie pauzeert als je het tabblad verlaat en de instelling voor minder beweging wordt gerespecteerd.

Er wordt niets opgeslagen en niets verstuurd: geen tracking, geen extern script, geen account.

## Starten

Open `index.html` in een willekeurige browser. Geen buildstap en geen afhankelijkheden.

## Goed oefenen

Adem zacht, zonder te forceren. Voelt het vasthouden onprettig, maak het dan korter: het doel is een rustig, gelijkmatig ritme, geen prestatie.

Deze oefening is geen medische behandeling. Word je duizelig of voel je je niet goed, stop dan en adem normaal.

## Zet de oefening op je website

Je kunt de volledige box breathing-oefening van upchin.app gratis op je eigen pagina tonen. Ze is beschikbaar in 17 talen: zet `data-lang` (of `lang=` in het adres van het frame) op `en`, `fr`, `de`, `es-MX`, `pt-BR`, `it`, `nl`, `pl`, `da`, `sv`, `ru`, `id`, `hi`, `ja`, `ko`, `zh-Hans`, `zh-HK`.

**Met het script** ([`box-breathing-embed.js`](box-breathing-embed.js)), dat de hoogte van het frame aan de inhoud aanpast:

```html
<div data-upchin-embed="box-breathing" data-lang="nl">
  <p>Box breathing door <a href="https://upchin.app/nl/tools/box-breathing">Upchin</a></p>
</div>
<script src="https://kevinsarrazin.github.io/free-box-breathing-online/box-breathing-embed.js" async></script>
```

**Zonder script**, als je site alleen HTML accepteert:

```html
<iframe src="https://upchin.app/embed/box-breathing?lang=nl" title="Box breathing" width="100%" height="1450" style="border:0;max-width:100%" loading="lazy" allow="clipboard-write"></iframe>
<p>Box breathing door <a href="https://upchin.app/nl/tools/box-breathing">Upchin</a></p>
```

Laat de bronvermelding onder de oefening alsjeblieft staan. Het script plaatst het frame ernaast en haalt de vermelding nooit weg.

## Volledige versie

De [box breathing-oefening op upchin.app](https://upchin.app/nl/tools/box-breathing) is beschikbaar in 17 talen. Je stelt elke stap in op 1 tot 20 seconden, kunt je telefoon laten trillen en oefent ook zonder tijdslimiet.

Deze oefening is gemaakt door het team achter Upchin. In de woorden van de website: ‘Apps zijn gemaakt om je te laten blijven scrollen. Upchin is gemaakt om je die tijd terug te geven.’ De iPhone-app gebruikt Schermtijd van Apple om je te helpen [vaker je telefoon weg te leggen](https://upchin.app/nl), met frictie op het juiste moment in plaats van een opgeheven vingertje.
