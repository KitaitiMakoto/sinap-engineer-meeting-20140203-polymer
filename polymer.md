PolymerとWeb Components
=======================

theme
:  rabbit

allotted-time
:  15m

PolymerとWeb Components
=======================

SINAPエンジニアチーム
　定例ミーティング用資料

2014年2月3日 月曜日

[Polymer][polymer]
==================

フロントエンドのアプリケーションフレームワーク

Google I/O 2013で発表

Web Componentsのpolyfill＋フレームワーク

Polyfill
========

「ブラウザー未実装の機能をJavaScriptで無理やり実装してみたもの」

`Array.prototype.forEach`とか。

ググったら小山田さんの記事が： [HTML5&CSS3入門 第6回 Graceful DegradationとPolyfill][polyfill]

Web Comopnents
==============

ウェブページをコンポーネントの組み合わせで作りやすできるような仕様の集まり
W3Cの[Introduction to Web Components][webcomponents]

Web Comopnents
==============

* Templates
* Custom Elements
* Shadow DOM
* Imports

Templates
=========

`&lt;template&gt;`要素

Custom Elements
===============

要素を自由に定義・追加できる

* bibi
* carousel
* form inputs

Shadow DOM
==========
`&lt;video&gt;`要素みたいなの（[HTML5 Rocks][html5rocksshadowdom]参照）

中が見えない

影響範囲の閉じたCSS

JavaScriptからも触れない

安全、*再利用*しやすい

Imports
=======

別ページのパーツを読み込む

* 要素定義とか
* テンプレートとか
* JavaScriptとCSSのセットとか

**`&lt;link&gt;`タグで！**

デザイナーフレンドリー

Polymer
=======

Web Componentsを使ったフレームワーク

フロントエンドのみ

PHPとかいらない

Web Components
==============

* テンプレートの使い方の具体例
* 双方向バインディング

ワークフローが変わる
====================

Before
======

WordPressの例

After
=====

Polymerを使うと……

不安点
======

Web Componentsはブラウザー実装がまだまだ

Polymerもpre-alpha

SEOどうなってるの？
  → よりよくなるらしい see [FAQ][polymerfaq]

対抗馬？
========

[X-Tag][x-tag]
:  Mozilla製フレームワーク
   Web Componentsのpolyfill＋フレームワーク


[polymer]: http://www.x-tags.org/
[polyfill]: http://www.adobe.com/jp/devnet/dreamweaver/articles/html5pack_css3_part6.html
[webcomponents]: http://w3c.github.io/webcomponents/explainer/
[html5rocksshadowdom]: http://www.html5rocks.com/ja/tutorials/video/basics/
[polymerfaq]: http://www.polymer-project.org/faq.html#seo
[x-tag]: http://www.x-tags.org/
