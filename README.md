# Free box breathing exercise online

Other languages: [Français](README.fr.md) · [Deutsch](README.de.md) · [Español (México)](README.es-MX.md) · [Português (Brasil)](README.pt-BR.md) · [Italiano](README.it.md) · [Nederlands](README.nl.md) · [Polski](README.pl.md) · [Dansk](README.da.md) · [Svenska](README.sv.md) · [Русский](README.ru.md) · [Bahasa Indonesia](README.id.md) · [हिन्दी](README.hi.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [简体中文](README.zh-Hans.md) · [繁體中文（香港）](README.zh-HK.md)

A free guided box breathing exercise that runs in your browser, in a single HTML file.

Try it online: https://kevinsarrazin.github.io/free-box-breathing-online/

Follow the light around the square. Each side is one step of 4 seconds:

- **Breathe in**: the light runs along the top and the circle grows.
- **Hold**, lungs full: the right side.
- **Breathe out**: the bottom side, and the circle shrinks.
- **Hold**, lungs empty: the left side.

Sessions of 1, 3 or 5 minutes always end on a full cycle. A 3-second countdown comes first, an optional gentle sound marks each step, the session pauses when you leave the tab, and reduced motion settings are respected.

Nothing is stored and nothing is sent anywhere: no tracking, no external script, no sign-up.

## Run it

Open `index.html` in any browser. No build step and no dependency.

## Using it well

Breathe gently, without forcing. If the holds feel uncomfortable, make them shorter: the aim is a calm, steady rhythm, not a performance.

This exercise is not a medical treatment. If you feel dizzy or unwell, stop and breathe normally.

## Embed the exercise on your website

You can show the full box breathing exercise from upchin.app on your own page, free. It is available in 17 languages: set `data-lang` (or `lang=` in the frame address) to `en`, `fr`, `de`, `es-MX`, `pt-BR`, `it`, `nl`, `pl`, `da`, `sv`, `ru`, `id`, `hi`, `ja`, `ko`, `zh-Hans`, `zh-HK`.

**With the script** ([`box-breathing-embed.js`](box-breathing-embed.js)), which adjusts the height of the frame to its content:

```html
<div data-upchin-embed="box-breathing" data-lang="en">
  <p>Box breathing by <a href="https://upchin.app/tools/box-breathing">Upchin</a></p>
</div>
<script src="https://kevinsarrazin.github.io/free-box-breathing-online/box-breathing-embed.js" async></script>
```

**Without a script**, if your site only accepts HTML:

```html
<iframe src="https://upchin.app/embed/box-breathing?lang=en" title="Box breathing" width="100%" height="1450" style="border:0;max-width:100%" loading="lazy" allow="clipboard-write"></iframe>
<p>Box breathing by <a href="https://upchin.app/tools/box-breathing">Upchin</a></p>
```

Please keep the credit line below the exercise. The script adds the frame next to it and never removes it.

## Full version

The [box breathing exercise on upchin.app](https://upchin.app/tools/box-breathing) is available in 17 languages. You can set each step from 1 to 20 seconds, add vibration on phones and breathe with no time limit.

This exercise is made by the team behind Upchin. In the words of its website: “Your apps are designed to keep you scrolling. Upchin is designed to give you your time back.” The iPhone app uses Apple's Screen Time to help you [take breaks from your phone](https://upchin.app/), with friction at the right moment rather than a lecture.
