# 免費網上箱式呼吸練習

其他語言： [English](README.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Español (México)](README.es-MX.md) · [Português (Brasil)](README.pt-BR.md) · [Italiano](README.it.md) · [Nederlands](README.nl.md) · [Polski](README.pl.md) · [Dansk](README.da.md) · [Svenska](README.sv.md) · [Русский](README.ru.md) · [Bahasa Indonesia](README.id.md) · [हिन्दी](README.hi.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [简体中文](README.zh-Hans.md)

一個在瀏覽器裡運行的免費箱式呼吸引導練習，只有一個 HTML 檔案。

網上試用：https://kevinsarrazin.github.io/free-box-breathing-online/zh-HK/

跟著光點繞方形走。每條邊是一個步驟，每步 4 秒：

- **吸氣**：光點沿上邊移動，圓圈慢慢變大。
- **屏氣**（吸滿後）：右邊。
- **呼氣**：下邊，圓圈慢慢變小。
- **屏氣**（呼盡後）：左邊。

可選 1、3 或 5 分鐘，每次練習總會等完整的一輪結束後才停止。開始前有 3 秒倒數，每換一步可以選擇輕響一聲作為提示；離開分頁時練習會自動暫停，也會遵從系統的「減少動態效果」設定。

不儲存任何資料，也不會傳送到任何地方：沒有追蹤，沒有外部腳本，也無需註冊。

## 運行

用任何瀏覽器開啟 `index.html` 即可。不用經過建構步驟，也沒有任何依賴項。

## 練習小貼士

輕柔地呼吸，不要勉強。如果屏氣令你不舒服，就縮短屏氣時間：目標是平穩、均勻的節奏，而不是挑戰極限。

這個練習不是治療手段。如果感到頭暈或身體不適，請停下來，正常呼吸。

## 把這個練習嵌入你的網站

你可以免費把 upchin.app 上完整的箱式呼吸練習放到自己的網頁上。它支援 17 種語言：把 `data-lang`（或框架網址中的 `lang=`）設為 `en`, `fr`, `de`, `es-MX`, `pt-BR`, `it`, `nl`, `pl`, `da`, `sv`, `ru`, `id`, `hi`, `ja`, `ko`, `zh-Hans`, `zh-HK` 其中之一即可。

**使用腳本**（[`box-breathing-embed.js`](box-breathing-embed.js)），它會根據內容自動調整框架高度：

```html
<div data-upchin-embed="box-breathing" data-lang="zh-HK">
  <p>箱式呼吸法，由 <a href="https://upchin.app/zh-HK/tools/box-breathing">Upchin</a> 提供</p>
</div>
<script src="https://kevinsarrazin.github.io/free-box-breathing-online/box-breathing-embed.js" async></script>
```

**不用腳本**，適合只接受 HTML 的網站：

```html
<iframe src="https://upchin.app/embed/box-breathing?lang=zh-HK" title="箱式呼吸法" width="100%" height="1450" style="border:0;max-width:100%" loading="lazy" allow="clipboard-write"></iframe>
<p>箱式呼吸法，由 <a href="https://upchin.app/zh-HK/tools/box-breathing">Upchin</a> 提供</p>
```

請保留練習下方的來源連結。腳本只會在它旁邊加入框架，絕不會把它移除。

## 完整版

[upchin.app 上的箱式呼吸練習](https://upchin.app/zh-HK/tools/box-breathing)支援 17 種語言。你可以把每一步設為 1 至 20 秒，在手機上開啟震動，還能不限時地練習。

這個練習由 Upchin 團隊打造。用其官網的話說：「手機裡的 App，生來就是為了讓你玩個不停；Upchin 反其道而行，把時間還給你。」這款 iPhone App 借助 Apple 的螢幕使用時間功能，幫你[不時放下手機](https://upchin.app/zh-HK)——不靠說教，而是在關鍵時刻踩一下剎車。
