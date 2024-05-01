# obs-supporter

obs を使う配信者向けのサポートツールです。

## 要件
### 配信終了時刻を設定できる
[x] デフォルトで現在時刻+1時間後に設定しておく。

[] 変えたければ操作で変えてね。

[] 今の時刻から+30分刻みで設定できる

[] 直接入力

[] 時間になったらアラームっぽい表示を出す。（赤く光る）

### obsで操作しやすい配慮（余力があれば）
* 拡大縮小が必要ないサイズで作る
  ▶細かい画面上のレイアウトが実現できない。右上のちょっと下、とか。
  ▶時計は時計、BGMはBGMとしてページ分けようか。
  ▶果たしてそれ使いやすいかな？


## how to develop
```
pnpm install
pnpm run dev
```

## Vue 3 + Vite

This template should help get you started developing with Vue 3 in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Vue - Official](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (previously Volar) and disable Vetur