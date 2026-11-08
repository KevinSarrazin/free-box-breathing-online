# 무료 온라인 박스 호흡 운동

다른 언어: [English](README.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Español (México)](README.es-MX.md) · [Português (Brasil)](README.pt-BR.md) · [Italiano](README.it.md) · [Nederlands](README.nl.md) · [Polski](README.pl.md) · [Dansk](README.da.md) · [Svenska](README.sv.md) · [Русский](README.ru.md) · [Bahasa Indonesia](README.id.md) · [हिन्दी](README.hi.md) · [日本語](README.ja.md) · [简体中文](README.zh-Hans.md) · [繁體中文（香港）](README.zh-HK.md)

브라우저에서 돌아가는 무료 박스 호흡 운동이에요. HTML 파일 하나로 되어 있어요.

온라인에서 해 보기: https://kevinsarrazin.github.io/free-box-breathing-online/ko/

사각형을 도는 빛을 따라가세요. 한 변이 한 단계이고, 단계마다 4초예요.

- **들이쉬기**: 빛이 위쪽 변을 지나고 원이 커져요.
- **참기**(들이쉰 뒤): 오른쪽 변.
- **내쉬기**: 아래쪽 변을 지나고 원이 작아져요.
- **참기**(내쉰 뒤): 왼쪽 변.

1분, 3분, 5분 세션은 항상 마지막 사이클을 끝까지 마치고 끝나요. 시작 전에 3초 카운트다운이 있고, 원하면 단계마다 부드러운 소리가 나요. 탭을 벗어나면 세션이 일시 정지되고, ‘동작 줄이기’ 설정도 존중해요.

아무것도 저장하지 않고, 어디로도 전송하지 않아요. 추적도, 외부 스크립트도, 가입도 없어요.

## 실행하기

`index.html` 파일을 아무 브라우저에서나 열면 돼요. 빌드 과정도, 의존성도 없어요.

## 잘 활용하는 법

억지로 하지 말고 부드럽게 호흡하세요. 숨 참기가 불편하면 짧게 줄이세요. 목표는 차분하고 고른 리듬이지, 잘 해내는 게 아니에요.

이 운동은 의학적 치료가 아니에요. 어지럽거나 몸이 안 좋으면 멈추고 평소처럼 호흡하세요.

## 이 호흡법을 내 웹사이트에 넣기

upchin.app의 박스 호흡 운동 전체 버전을 내 페이지에 무료로 넣을 수 있어요. 17개 언어를 지원해요. `data-lang`(또는 프레임 주소의 `lang=`) 값을 `en`, `fr`, `de`, `es-MX`, `pt-BR`, `it`, `nl`, `pl`, `da`, `sv`, `ru`, `id`, `hi`, `ja`, `ko`, `zh-Hans`, `zh-HK` 중 하나로 정해 주세요.

**스크립트를 쓰는 방법**([`box-breathing-embed.js`](box-breathing-embed.js)). 프레임 높이를 내용에 맞게 조절해 줘요.

```html
<div data-upchin-embed="box-breathing" data-lang="ko">
  <p>박스 호흡 · 제공: <a href="https://upchin.app/ko/tools/box-breathing">Upchin</a></p>
</div>
<script src="https://kevinsarrazin.github.io/free-box-breathing-online/box-breathing-embed.js" async></script>
```

**스크립트 없이 넣는 방법**. 사이트에 HTML만 넣을 수 있을 때 써요.

```html
<iframe src="https://upchin.app/embed/box-breathing?lang=ko" title="박스 호흡" width="100%" height="1450" style="border:0;max-width:100%" loading="lazy" allow="clipboard-write"></iframe>
<p>박스 호흡 · 제공: <a href="https://upchin.app/ko/tools/box-breathing">Upchin</a></p>
```

호흡법 아래의 출처 표시는 남겨 주세요. 스크립트는 그 옆에 프레임을 추가할 뿐, 출처 표시를 지우지 않아요.

## 전체 버전

17개 언어로 쓸 수 있는 [upchin.app의 박스 호흡 운동](https://upchin.app/ko/tools/box-breathing)에서는 단계마다 1~20초로 정할 수 있고, 휴대폰에서는 진동을 켤 수 있으며, 시간 제한 없이 호흡할 수도 있어요.

이 호흡 운동은 Upchin 팀이 만들었어요. 웹사이트에는 이렇게 쓰여 있어요. “휴대폰 속 앱은 계속 스크롤하도록 설계돼 있어요. Upchin은 반대로, 그 시간을 돌려주는 앱이에요.” 이 iPhone 앱은 Apple의 스크린 타임 기능을 활용해 [휴대폰에서 잠시 벗어나도록](https://upchin.app/ko) 도와줘요. 잔소리하는 대신, 꼭 필요한 순간에 브레이크를 걸어 줘요.
