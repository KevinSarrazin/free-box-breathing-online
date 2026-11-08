# 無料オンライン・ボックス呼吸ガイド

ほかの言語： [English](README.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Español (México)](README.es-MX.md) · [Português (Brasil)](README.pt-BR.md) · [Italiano](README.it.md) · [Nederlands](README.nl.md) · [Polski](README.pl.md) · [Dansk](README.da.md) · [Svenska](README.sv.md) · [Русский](README.ru.md) · [Bahasa Indonesia](README.id.md) · [हिन्दी](README.hi.md) · [한국어](README.ko.md) · [简体中文](README.zh-Hans.md) · [繁體中文（香港）](README.zh-HK.md)

ブラウザで動く無料のボックス呼吸ガイドです。HTMLファイル1つでできています。

オンラインで試す：https://kevinsarrazin.github.io/free-box-breathing-online/ja/

四角形をめぐる光を目で追いましょう。1辺が1ステップで、それぞれ4秒です：

- **吸って**：光が上の辺を進み、円がふくらみます。
- **止めて**（吸ったあと）：右の辺。
- **吐いて**：下の辺。円がしぼみます。
- **止めて**（吐いたあと）：左の辺。

1分、3分、5分のセッションは、必ずサイクルの区切りで終わります。始まる前に3秒のカウントダウンがあり、ステップごとにやさしい音を鳴らすこともできます。タブを離れるとセッションは一時停止し、「視差効果を減らす」などの動きを抑える設定にも対応しています。

データは何も保存されず、どこにも送信されません。トラッキングも、外部スクリプトも、登録もありません。

## 実行する

`index.html` をお好きなブラウザで開くだけです。ビルドも依存関係も必要ありません。

## 使うときのポイント

無理をせず、やさしく呼吸してください。息を止めるのがつらければ、短くしましょう。目指すのは落ち着いた一定のリズムで、上手にこなすことではありません。

この練習は治療法ではありません。めまいがしたり気分が悪くなったりしたら、中止していつもどおりに呼吸してください。

## この呼吸法を自分のサイトに埋め込む

upchin.appのボックス呼吸ガイド（完全版）を、自分のページに無料で表示できます。17言語に対応しています。`data-lang`（またはフレームのアドレスの `lang=`）に、`en`, `fr`, `de`, `es-MX`, `pt-BR`, `it`, `nl`, `pl`, `da`, `sv`, `ru`, `id`, `hi`, `ja`, `ko`, `zh-Hans`, `zh-HK` のいずれかを指定してください。

**スクリプトを使う場合**（[`box-breathing-embed.js`](box-breathing-embed.js)）。フレームの高さを内容に合わせて調整します：

```html
<div data-upchin-embed="box-breathing" data-lang="ja">
  <p>ボックス呼吸（提供：<a href="https://upchin.app/ja/tools/box-breathing">Upchin</a>）</p>
</div>
<script src="https://kevinsarrazin.github.io/free-box-breathing-online/box-breathing-embed.js" async></script>
```

**スクリプトを使わない場合**（HTMLしか使えないサイト向け）：

```html
<iframe src="https://upchin.app/embed/box-breathing?lang=ja" title="ボックス呼吸" width="100%" height="1450" style="border:0;max-width:100%" loading="lazy" allow="clipboard-write"></iframe>
<p>ボックス呼吸（提供：<a href="https://upchin.app/ja/tools/box-breathing">Upchin</a>）</p>
```

呼吸法の下のクレジット表記は残してください。スクリプトはその横にフレームを追加するだけで、クレジットを消すことはありません。

## 完全版

[upchin.appのボックス呼吸ガイド](https://upchin.app/ja/tools/box-breathing)は17言語に対応しています。各ステップを1〜20秒で設定でき、スマホではバイブレーションも使え、時間制限なしで呼吸することもできます。

この呼吸法は、Upchinのチームが作りました。公式サイトにはこうあります。「スマホのアプリは、スクロールがやめられないように作られています。Upchinは逆に、その時間をあなたに返すためのアプリです。」このiPhoneアプリは、Appleのスクリーンタイム機能を使って[スマホから離れる時間をつくる](https://upchin.app/ja)お手伝いをします。説教をするのではなく、ここぞというときに小さなブレーキをかける。それがUpchinのやり方です。
