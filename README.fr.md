# Exercice de respiration carrée gratuit en ligne

Autres langues : [English](README.md) · [Deutsch](README.de.md) · [Español (México)](README.es-MX.md) · [Português (Brasil)](README.pt-BR.md) · [Italiano](README.it.md) · [Nederlands](README.nl.md) · [Polski](README.pl.md) · [Dansk](README.da.md) · [Svenska](README.sv.md) · [Русский](README.ru.md) · [Bahasa Indonesia](README.id.md) · [हिन्दी](README.hi.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [简体中文](README.zh-Hans.md) · [繁體中文（香港）](README.zh-HK.md)

Un exercice de respiration carrée guidé et gratuit, qui tourne dans ton navigateur, en un seul fichier HTML.

Essaie-le en ligne : https://kevinsarrazin.github.io/free-box-breathing-online/fr/

Suis la lumière autour du carré. Chaque côté est un temps de 4 secondes :

- **Inspire** : la lumière longe le haut et le cercle grandit.
- **Retiens**, poumons pleins : le côté droit.
- **Expire** : le côté du bas, et le cercle rétrécit.
- **Retiens**, poumons vides : le côté gauche.

Les séances de 1, 3 ou 5 minutes se terminent toujours sur un cycle complet. Un compte à rebours de 3 secondes ouvre la séance, un son doux en option marque chaque temps, la séance se met en pause quand tu quittes l’onglet, et les réglages de réduction des animations sont respectés.

Rien n’est enregistré et rien n’est envoyé nulle part : aucun pistage, aucun script externe, aucune inscription.

## Lancer en local

Ouvre `index.html` dans n’importe quel navigateur. Aucune compilation, aucune dépendance.

## Bien l’utiliser

Respire doucement, sans forcer. Si les rétentions te gênent, raccourcis-les : le but est un rythme calme et régulier, pas une performance.

Cet exercice n’est pas un traitement médical. Si tu as des vertiges ou si tu te sens mal, arrête et respire normalement.

## Intègre l’exercice sur ton site

Tu peux afficher gratuitement l’exercice de respiration carrée complet d’upchin.app sur ta propre page. Il existe en 17 langues : règle `data-lang` (ou `lang=` dans l’adresse du cadre) sur `en`, `fr`, `de`, `es-MX`, `pt-BR`, `it`, `nl`, `pl`, `da`, `sv`, `ru`, `id`, `hi`, `ja`, `ko`, `zh-Hans`, `zh-HK`.

**Avec le script** ([`box-breathing-embed.js`](box-breathing-embed.js)), qui ajuste la hauteur du cadre à son contenu :

```html
<div data-upchin-embed="box-breathing" data-lang="fr">
  <p>Respiration carrée par <a href="https://upchin.app/fr/outils/respiration-carree">Upchin</a></p>
</div>
<script src="https://kevinsarrazin.github.io/free-box-breathing-online/box-breathing-embed.js" async></script>
```

**Sans script**, si ton site n’accepte que du HTML :

```html
<iframe src="https://upchin.app/embed/box-breathing?lang=fr" title="Respiration carrée" width="100%" height="1450" style="border:0;max-width:100%" loading="lazy" allow="clipboard-write"></iframe>
<p>Respiration carrée par <a href="https://upchin.app/fr/outils/respiration-carree">Upchin</a></p>
```

Garde la ligne de crédit sous l’exercice, s’il te plaît. Le script ajoute le cadre à côté d’elle et ne la retire jamais.

## Version complète

L’[exercice de respiration carrée sur upchin.app](https://upchin.app/fr/outils/respiration-carree) existe en 17 langues. Tu peux y régler chaque temps de 1 à 20 secondes, ajouter des vibrations sur téléphone et respirer sans limite de durée.

Cet exercice est réalisé par l’équipe d’Upchin. Comme le dit son site : « Tes apps sont conçues pour te faire scroller. Upchin est conçue pour te rendre ton temps. » L’app iPhone s’appuie sur le Temps d’écran d’Apple pour t’aider à [faire des pauses loin de ton téléphone](https://upchin.app/fr), avec de la friction au bon moment plutôt qu’une leçon de morale.
