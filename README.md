# 「Webシステム開発について」勉強会第11回 ハンズオン資料 の補足

栗原さんの利用した資料などを補足するサイトです
ここに乗せているハンズオンのソースコードは、私の方でソースコードにコメントを追加しています。
従って、こちらにあるソースコードを閲覧することで、不明点が明瞭になることがあります。


## 事前に必要な知識など

- [Vue.js 公式のヘルプ(日本語:v2)](https://jp.vuejs.org/v2/guide/index.html)
- [vue-devtools](https://chrome.google.com/webstore/detail/vuejs-devtools/nhdogjmejiglipccpnnnanhbledajbpd)
  - Developer Tools に Vue 専用のタブ が増える
  - [公式](https://github.com/vuejs/vue-devtools)
- [Vue.js入門 基礎から実践アプリケーション開発まで](https://gihyo.jp/book/2018/978-4-297-10091-9)



## ハンズオン資料 + 追加したコメント

| ページ | デモ | 備考 |
| ------------- | ------------- | ------------- |
| 10 | [Vuejs1.html](https://ces-shiraishi.github.io/kurihara-training-part11/Vuejs1.html)  <br>  [jsfiddle](https://jsfiddle.net/9k1gbyrc) |   |
| 13 | [Vuejs2.html](https://ces-shiraishi.github.io/kurihara-training-part11/Vuejs2.html) | 
・ ディレクティブが色々出てきて迷うかもしれないが、それぞれ分けて考えると良い。<br>
・ 分かりづらいと思うので、チェックボックスの id を show → checkbox1 に変更 <br>
・ コメントアウトしていた `v-else` と `v-show` も表示させることにした <br>
・ `v-if` と `v-else` はセットで考える `v-if` の直前でないと反応しない |
| 14 | [Vuejs3.html](https://ces-shiraishi.github.io/kurihara-training-part11/Vuejs3.html) | |
| 16 | [Vuejs4.html](https://ces-shiraishi.github.io/kurihara-training-part11/Vuejs4.html) | |
| 17 | [Vuejs5.html](https://ces-shiraishi.github.io/kurihara-training-part11/Vuejs5.html) | sample では `class="small"` が設定されておらず、よくわからないので、当方で設定した |
| 18 | [Vuejs6.html](https://ces-shiraishi.github.io/kurihara-training-part11/Vuejs6.html) | |
| 21 | [Vuejs7.html](https://ces-shiraishi.github.io/kurihara-training-part11/Vuejs7.html) | |
| 23 | [Vuejs8.html](https://ces-shiraishi.github.io/kurihara-training-part11/Vuejs8.html) | コンポーネント とは、 `再利用可能な Vue オブジェクト` なので、Vue の インスタンス というのがポイント。資料上分かりづらいと思うが、親コンポーネント(root) は `<div id=“fruits-list”>` で 子コンポーネント は `fruits-list-title` という点を意識する。 <br> [参考…公式ページ](https://jp.vuejs.org/v2/guide/components.html) |
| 24 | [Vuejs9.html](https://ces-shiraishi.github.io/kurihara-training-part11/Vuejs9.html) | |
| 26 | [Vuejs10.html](https://ces-shiraishi.github.io/kurihara-training-part11/Vuejs10.html) | 親コンポーネントは `<div id=“app”>` である(rootコンポーネント)。このサンプルは コンポーネントのプロパティを解説したもの。 |
| 27 | [Vuejs11.html](https://ces-shiraishi.github.io/kurihara-training-part11/Vuejs11.html) | |
| 28 | [Vuejs12.html](https://ces-shiraishi.github.io/kurihara-training-part11/Vuejs12.html) | サンプルコードに誤りがあり、DOMが読み込まれる前に コンポーネントを定義しているので、エラーとなる。script要素を最後に持っていくのが良い |
| 29 | [Vuejs13.html](https://ces-shiraishi.github.io/kurihara-training-part11/Vuejs13.html) | |

