# Oddychanie pudełkowe – darmowe ćwiczenie online

Inne języki: [English](README.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Español (México)](README.es-MX.md) · [Português (Brasil)](README.pt-BR.md) · [Italiano](README.it.md) · [Nederlands](README.nl.md) · [Dansk](README.da.md) · [Svenska](README.sv.md) · [Русский](README.ru.md) · [Bahasa Indonesia](README.id.md) · [हिन्दी](README.hi.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [简体中文](README.zh-Hans.md) · [繁體中文（香港）](README.zh-HK.md)

Darmowe prowadzone ćwiczenie oddychania pudełkowego, które działa w przeglądarce, w jednym pliku HTML.

Wypróbuj online: https://kevinsarrazin.github.io/free-box-breathing-online/pl/

Podążaj za światłem dookoła kwadratu. Każdy bok to jedna faza trwająca 4 sekundy:

- **Wdech**: światło biegnie po górnym boku, a krąg się powiększa.
- **Wstrzymaj** oddech z pełnymi płucami: prawy bok.
- **Wydech**: dolny bok, a krąg się zmniejsza.
- **Wstrzymaj** oddech z pustymi płucami: lewy bok.

Sesje trwające 1, 3 lub 5 minut zawsze kończą się pełnym cyklem. Najpierw jest 3-sekundowe odliczanie, opcjonalny łagodny dźwięk sygnalizuje każdą fazę, sesja zatrzymuje się, gdy opuścisz kartę, a ustawienie ograniczania ruchu jest uwzględniane.

Nic nie jest zapisywane ani nigdzie wysyłane: bez śledzenia, bez zewnętrznych skryptów, bez rejestracji.

## Uruchomienie

Otwórz `index.html` w dowolnej przeglądarce. Bez kompilacji i bez zależności.

## Jak dobrze z niego korzystać

Oddychaj łagodnie, bez forsowania. Jeśli wstrzymywanie oddechu jest niewygodne, skróć je: chodzi o spokojny, równy rytm, a nie o wyczyn.

To ćwiczenie nie jest formą leczenia. Jeśli kręci Ci się w głowie albo źle się czujesz, przerwij i oddychaj normalnie.

## Umieść ćwiczenie na swojej stronie

Pełne ćwiczenie oddychania pudełkowego z upchin.app możesz bezpłatnie pokazać na własnej stronie. Jest dostępne w 17 językach: ustaw `data-lang` (lub `lang=` w adresie ramki) na jeden z kodów: `en`, `fr`, `de`, `es-MX`, `pt-BR`, `it`, `nl`, `pl`, `da`, `sv`, `ru`, `id`, `hi`, `ja`, `ko`, `zh-Hans`, `zh-HK`.

**Ze skryptem** ([`box-breathing-embed.js`](box-breathing-embed.js)), który dopasowuje wysokość ramki do treści:

```html
<div data-upchin-embed="box-breathing" data-lang="pl">
  <p>Oddychanie pudełkowe od <a href="https://upchin.app/pl/narzedzia/oddychanie-pudelkowe">Upchin</a></p>
</div>
<script src="https://kevinsarrazin.github.io/free-box-breathing-online/box-breathing-embed.js" async></script>
```

**Bez skryptu**, jeśli Twoja strona przyjmuje tylko HTML:

```html
<iframe src="https://upchin.app/embed/box-breathing?lang=pl" title="Oddychanie pudełkowe" width="100%" height="1450" style="border:0;max-width:100%" loading="lazy" allow="clipboard-write"></iframe>
<p>Oddychanie pudełkowe od <a href="https://upchin.app/pl/narzedzia/oddychanie-pudelkowe">Upchin</a></p>
```

Zostaw, proszę, informację o źródle pod ćwiczeniem. Skrypt dodaje ramkę obok niej i nigdy jej nie usuwa.

## Pełna wersja

Pełne [ćwiczenie oddychania pudełkowego na upchin.app](https://upchin.app/pl/narzedzia/oddychanie-pudelkowe) jest dostępne w 17 językach. Możesz ustawić każdą fazę od 1 do 20 sekund, włączyć wibracje w telefonie i oddychać bez limitu czasu.

To ćwiczenie przygotował zespół Upchin. Jak głosi jego strona: „Aplikacje w telefonie są projektowane tak, by trzymać Cię przy przewijaniu. Upchin powstał, by oddać Ci czas.” Aplikacja na iPhone’a korzysta z funkcji Czas przed ekranem od Apple, by pomóc Ci [częściej odkładać telefon](https://upchin.app/pl) – z hamulcem we właściwej chwili zamiast moralizowania.
