# 免费在线箱式呼吸练习

其他语言： [English](README.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Español (México)](README.es-MX.md) · [Português (Brasil)](README.pt-BR.md) · [Italiano](README.it.md) · [Nederlands](README.nl.md) · [Polski](README.pl.md) · [Dansk](README.da.md) · [Svenska](README.sv.md) · [Русский](README.ru.md) · [Bahasa Indonesia](README.id.md) · [हिन्दी](README.hi.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [繁體中文（香港）](README.zh-HK.md)

一个在浏览器里运行的免费箱式呼吸引导练习，只有一个 HTML 文件。

在线试用：https://kevinsarrazin.github.io/free-box-breathing-online/zh-Hans/

跟着光点绕方形走。每条边是一个步骤，每步 4 秒：

- **吸气**：光点沿上边移动，圆圈慢慢变大。
- **屏气**（吸满后）：右边。
- **呼气**：下边，圆圈慢慢变小。
- **屏气**（呼尽后）：左边。

可选 1、3 或 5 分钟，每次练习总会等完整的一轮结束后才停止。开始前有 3 秒倒计时，每换一步可以选择轻响一声作为提示；离开标签页时练习会自动暂停，也会遵循系统的“减弱动态效果”设置。

不保存任何数据，也不会发送到任何地方：没有追踪，没有外部脚本，也无需注册。

## 运行

用任意浏览器打开 `index.html` 即可。无需构建，也没有任何依赖。

## 练习小提示

轻柔地呼吸，不要勉强。如果屏气让你不舒服，就缩短屏气时间：目标是平稳、均匀的节奏，而不是挑战极限。

这个练习不是治疗手段。如果感到头晕或身体不适，请停下来，正常呼吸。

## 把这个练习嵌入你的网站

你可以免费把 upchin.app 上完整的箱式呼吸练习放到自己的网页上。它支持 17 种语言：把 `data-lang`（或框架地址中的 `lang=`）设为 `en`, `fr`, `de`, `es-MX`, `pt-BR`, `it`, `nl`, `pl`, `da`, `sv`, `ru`, `id`, `hi`, `ja`, `ko`, `zh-Hans`, `zh-HK` 之一即可。

**使用脚本**（[`box-breathing-embed.js`](box-breathing-embed.js)），它会根据内容自动调整框架高度：

```html
<div data-upchin-embed="box-breathing" data-lang="zh-Hans">
  <p>箱式呼吸法，由 <a href="https://upchin.app/zh-Hans/tools/box-breathing">Upchin</a> 提供</p>
</div>
<script src="https://kevinsarrazin.github.io/free-box-breathing-online/box-breathing-embed.js" async></script>
```

**不用脚本**，适合只接受 HTML 的网站：

```html
<iframe src="https://upchin.app/embed/box-breathing?lang=zh-Hans" title="箱式呼吸法" width="100%" height="1450" style="border:0;max-width:100%" loading="lazy" allow="clipboard-write"></iframe>
<p>箱式呼吸法，由 <a href="https://upchin.app/zh-Hans/tools/box-breathing">Upchin</a> 提供</p>
```

请保留练习下方的来源链接。脚本只会在它旁边加入框架，绝不会把它移除。

## 完整版

[upchin.app 上的箱式呼吸练习](https://upchin.app/zh-Hans/tools/box-breathing)支持 17 种语言。你可以把每一步设为 1 到 20 秒，在手机上开启振动，还能不限时地练习。

这个练习由 Upchin 团队打造。用其官网的话说：“手机里的应用，生来就是为了让你刷个不停；Upchin 反其道而行，把时间还给你。”这款 iPhone 应用借助 Apple 的屏幕使用时间功能，帮你[时不时放下手机](https://upchin.app/zh-Hans)——不靠说教，而是在关键时刻踩一下刹车。
