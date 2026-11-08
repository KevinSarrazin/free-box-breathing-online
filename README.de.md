# Kostenlose Übung zur Box-Atmung online

Andere Sprachen: [English](README.md) · [Français](README.fr.md) · [Español (México)](README.es-MX.md) · [Português (Brasil)](README.pt-BR.md) · [Italiano](README.it.md) · [Nederlands](README.nl.md) · [Polski](README.pl.md) · [Dansk](README.da.md) · [Svenska](README.sv.md) · [Русский](README.ru.md) · [Bahasa Indonesia](README.id.md) · [हिन्दी](README.hi.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [简体中文](README.zh-Hans.md) · [繁體中文（香港）](README.zh-HK.md)

Eine kostenlose geführte Box-Atmung, die in deinem Browser läuft, in einer einzigen HTML-Datei.

Online ausprobieren: https://kevinsarrazin.github.io/free-box-breathing-online/de/

Folge dem Licht rund ums Quadrat. Jede Seite ist ein Schritt von 4 Sekunden:

- **Einatmen**: Das Licht läuft über die obere Seite, und der Kreis wird größer.
- **Halten**, Lunge voll: die rechte Seite.
- **Ausatmen**: die untere Seite, und der Kreis wird kleiner.
- **Halten**, Lunge leer: die linke Seite.

Übungen von 1, 3 oder 5 Minuten enden immer mit einem vollständigen Zyklus. Vorher läuft ein Countdown von 3 Sekunden, ein optionaler sanfter Ton markiert jeden Schritt, die Übung pausiert, wenn du den Tab verlässt, und die Einstellung für reduzierte Bewegung wird berücksichtigt.

Nichts wird gespeichert und nichts wird irgendwohin gesendet: kein Tracking, kein externes Skript, keine Anmeldung.

## Ausführen

Öffne `index.html` in einem beliebigen Browser. Kein Build-Schritt, keine Abhängigkeiten.

## Richtig üben

Atme sanft und ohne Anstrengung. Sind dir die Haltephasen unangenehm, verkürze sie: Es geht um einen ruhigen, gleichmäßigen Rhythmus, nicht um Leistung.

Diese Übung ist keine medizinische Behandlung. Wenn dir schwindlig wird oder du dich unwohl fühlst, hör auf und atme normal weiter.

## Binde die Übung auf deiner Website ein

Du kannst die vollständige Box-Atmung von upchin.app kostenlos auf deiner eigenen Seite zeigen. Sie ist in 17 Sprachen verfügbar: Setze `data-lang` (oder `lang=` in der Adresse des Frames) auf `en`, `fr`, `de`, `es-MX`, `pt-BR`, `it`, `nl`, `pl`, `da`, `sv`, `ru`, `id`, `hi`, `ja`, `ko`, `zh-Hans`, `zh-HK`.

**Mit dem Skript** ([`box-breathing-embed.js`](box-breathing-embed.js)), das die Höhe des Frames an seinen Inhalt anpasst:

```html
<div data-upchin-embed="box-breathing" data-lang="de">
  <p>Box-Atmung von <a href="https://upchin.app/de/tools/box-atmung">Upchin</a></p>
</div>
<script src="https://kevinsarrazin.github.io/free-box-breathing-online/box-breathing-embed.js" async></script>
```

**Ohne Skript**, wenn deine Website nur HTML zulässt:

```html
<iframe src="https://upchin.app/embed/box-breathing?lang=de" title="Box-Atmung" width="100%" height="1450" style="border:0;max-width:100%" loading="lazy" allow="clipboard-write"></iframe>
<p>Box-Atmung von <a href="https://upchin.app/de/tools/box-atmung">Upchin</a></p>
```

Bitte lass die Quellenangabe unter der Übung stehen. Das Skript setzt den Frame daneben und entfernt sie nie.

## Vollständige Version

Die [Box-Atmung auf upchin.app](https://upchin.app/de/tools/box-atmung) ist in 17 Sprachen verfügbar. Du kannst jeden Schritt auf 1 bis 20 Sekunden einstellen, auf dem Handy Vibration hinzufügen und ohne Zeitlimit atmen.

Diese Übung stammt vom Team hinter Upchin. Auf der Website heißt es: „Deine Apps sind dafür gebaut, dass du weiterscrollst. Upchin ist dafür gebaut, dir deine Zeit zurückzugeben.“ Die iPhone-App nutzt Apples Bildschirmzeit, um dir zu helfen, [öfter Pausen vom Handy zu machen](https://upchin.app/de) – mit einer Bremse im richtigen Moment statt mit erhobenem Zeigefinger.
