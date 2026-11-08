# Ejercicio de respiración cuadrada gratis en línea

Otros idiomas: [English](README.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Português (Brasil)](README.pt-BR.md) · [Italiano](README.it.md) · [Nederlands](README.nl.md) · [Polski](README.pl.md) · [Dansk](README.da.md) · [Svenska](README.sv.md) · [Русский](README.ru.md) · [Bahasa Indonesia](README.id.md) · [हिन्दी](README.hi.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [简体中文](README.zh-Hans.md) · [繁體中文（香港）](README.zh-HK.md)

Un ejercicio guiado de respiración cuadrada gratis que funciona en tu navegador, en un solo archivo HTML.

Pruébalo en línea: https://kevinsarrazin.github.io/free-box-breathing-online/es-MX/

Sigue la luz alrededor del cuadrado. Cada lado es un tiempo de 4 segundos:

- **Inhala**: la luz recorre el lado de arriba y el círculo crece.
- **Retén**, con los pulmones llenos: el lado derecho.
- **Exhala**: el lado de abajo, y el círculo se encoge.
- **Retén**, con los pulmones vacíos: el lado izquierdo.

Las sesiones de 1, 3 o 5 minutos siempre terminan en un ciclo completo. Primero hay una cuenta regresiva de 3 segundos, un sonido suave opcional marca cada tiempo, la sesión se pausa cuando sales de la pestaña y se respeta la configuración de movimiento reducido.

No se guarda nada y no se envía nada a ningún lado: sin rastreo, sin scripts externos, sin registro.

## Cómo usarlo

Abre `index.html` en cualquier navegador. Sin compilación y sin dependencias.

## Para usarlo bien

Respira suavemente, sin forzar. Si las retenciones te incomodan, acórtalas: lo que importa es un ritmo tranquilo y constante, no exigirte de más.

Este ejercicio no es un tratamiento médico. Si te mareas o te sientes mal, detente y respira normalmente.

## Agrega el ejercicio a tu sitio web

Puedes mostrar gratis el ejercicio completo de respiración cuadrada de upchin.app en tu propia página. Está disponible en 17 idiomas: define `data-lang` (o `lang=` en la dirección del marco) como `en`, `fr`, `de`, `es-MX`, `pt-BR`, `it`, `nl`, `pl`, `da`, `sv`, `ru`, `id`, `hi`, `ja`, `ko`, `zh-Hans`, `zh-HK`.

**Con el script** ([`box-breathing-embed.js`](box-breathing-embed.js)), que ajusta la altura del marco a su contenido:

```html
<div data-upchin-embed="box-breathing" data-lang="es-MX">
  <p>Respiración cuadrada por <a href="https://upchin.app/es-MX/herramientas/respiracion-cuadrada">Upchin</a></p>
</div>
<script src="https://kevinsarrazin.github.io/free-box-breathing-online/box-breathing-embed.js" async></script>
```

**Sin script**, si tu sitio solo acepta HTML:

```html
<iframe src="https://upchin.app/embed/box-breathing?lang=es-MX" title="Respiración cuadrada" width="100%" height="1450" style="border:0;max-width:100%" loading="lazy" allow="clipboard-write"></iframe>
<p>Respiración cuadrada por <a href="https://upchin.app/es-MX/herramientas/respiracion-cuadrada">Upchin</a></p>
```

Por favor, conserva la línea de crédito debajo del ejercicio. El script agrega el marco junto a ella y nunca la quita.

## Versión completa

El [ejercicio de respiración cuadrada en upchin.app](https://upchin.app/es-MX/herramientas/respiracion-cuadrada) está disponible en 17 idiomas. Puedes ajustar cada tiempo de 1 a 20 segundos, agregar vibración en el celular y respirar sin límite de tiempo.

Este ejercicio lo hace el equipo detrás de Upchin. En palabras de su sitio web: “Tus apps están diseñadas para que sigas haciendo scroll. Upchin está diseñada para devolverte tu tiempo.” La app para iPhone usa Tiempo en pantalla de Apple para ayudarte a [tomar descansos del celular](https://upchin.app/es-MX), con fricción en el momento justo en lugar de sermones.
