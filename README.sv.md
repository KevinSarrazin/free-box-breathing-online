# Gratis boxandning online

Andra språk: [English](README.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Español (México)](README.es-MX.md) · [Português (Brasil)](README.pt-BR.md) · [Italiano](README.it.md) · [Nederlands](README.nl.md) · [Polski](README.pl.md) · [Dansk](README.da.md) · [Русский](README.ru.md) · [Bahasa Indonesia](README.id.md) · [हिन्दी](README.hi.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [简体中文](README.zh-Hans.md) · [繁體中文（香港）](README.zh-HK.md)

En gratis guidad övning i boxandning som körs i webbläsaren, i en enda HTML-fil.

Testa online: https://kevinsarrazin.github.io/free-box-breathing-online/sv/

Följ ljuset runt fyrkanten. Varje sida är ett steg på 4 sekunder:

- **Andas in**: ljuset löper längs överkanten och cirkeln växer.
- **Håll**, fulla lungor: högra sidan.
- **Andas ut**: underkanten, och cirkeln krymper.
- **Håll**, tomma lungor: vänstra sidan.

Pass på 1, 3 eller 5 minuter slutar alltid med ett helt varv. Först kommer en nedräkning på 3 sekunder, ett mjukt ljud markerar varje steg om du vill, passet pausas när du lämnar fliken och inställningen för minskad rörelse respekteras.

Inget sparas och inget skickas någonstans: ingen spårning, inga externa skript, inget konto.

## Kör övningen

Öppna `index.html` i valfri webbläsare. Inget byggsteg och inga beroenden.

## Att tänka på

Andas mjukt, utan att forcera. Känns det obekvämt att hålla andan, kan du korta den tiden: målet är en lugn och jämn rytm, inte en prestation.

Övningen är ingen medicinsk behandling. Om du blir yr eller mår dåligt, avbryt och andas som vanligt.

## Bädda in övningen på din webbplats

Du kan visa hela övningen i boxandning från upchin.app på din egen sida, gratis. Den finns på 17 språk: sätt `data-lang` (eller `lang=` i ramens adress) till `en`, `fr`, `de`, `es-MX`, `pt-BR`, `it`, `nl`, `pl`, `da`, `sv`, `ru`, `id`, `hi`, `ja`, `ko`, `zh-Hans`, `zh-HK`.

**Med skriptet** ([`box-breathing-embed.js`](box-breathing-embed.js)), som anpassar ramens höjd efter innehållet:

```html
<div data-upchin-embed="box-breathing" data-lang="sv">
  <p>Boxandning från <a href="https://upchin.app/sv/verktyg/boxandning">Upchin</a></p>
</div>
<script src="https://kevinsarrazin.github.io/free-box-breathing-online/box-breathing-embed.js" async></script>
```

**Utan skript**, om din webbplats bara tillåter HTML:

```html
<iframe src="https://upchin.app/embed/box-breathing?lang=sv" title="Boxandning" width="100%" height="1450" style="border:0;max-width:100%" loading="lazy" allow="clipboard-write"></iframe>
<p>Boxandning från <a href="https://upchin.app/sv/verktyg/boxandning">Upchin</a></p>
```

Låt gärna källhänvisningen under övningen vara kvar. Skriptet lägger till ramen bredvid den och tar aldrig bort den.

## Fullständig version

Den fullständiga versionen, [boxandningsövningen på upchin.app](https://upchin.app/sv/verktyg/boxandning), finns på 17 språk. Där kan du ställa in varje steg på 1 till 20 sekunder, få vibration på mobilen och andas utan tidsgräns.

Övningen är gjord av teamet bakom Upchin. Med webbplatsens egna ord: ”Dina appar är gjorda för att få dig att scrolla. Upchin är gjord för att ge dig tiden tillbaka.” Appen för iPhone bygger på Apples Skärmtid och hjälper dig att [ta pauser från mobilen](https://upchin.app/sv) – med friktion i rätt ögonblick, utan pekpinnar.
