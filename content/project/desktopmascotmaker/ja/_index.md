---
title: "Desktop Mascot Maker"
description: "デスクトップマスコットメーカーは Unity でデスクトップマスコットキャラクターを作るUnityのアセットです。"
date: 2018-08-26T03:07:53+09:00
categories: []
tags: [dev]
draft: false
layout: single
---

<div style="text-align: right;">
    <a href="project/desktopmascotmaker/en/">English version is here</a>
</div>

![](project/desktopmascotmaker/images/title.png)

<h1 class="title is-1">Unityでデスクトップマスコットを作ろう</h1>

デスクトップマスコットメーカーは Unity でデスクトップマスコットキャラクターを作るUnityのアセットです。

Unity のカメラに映るものなら3Dでも2Dでも何でも、簡単にデスクトップマスコットを作ることができます。

{{< youtube id="wJ27IUKV5aw" autoplay="false" >}}

<h1 class="title is-1">アセットの特徴</h1>

- Unity5, Unity2017に対応
- Unityのスクリプトからマスコットを自由自在に操作できる
- マスコットの不透明度を自由に変更できる
- マスコット上で起こるクリック、ダブルクリック、マウスホイールなどのたくさんのイベント処理を利用できる
- マウスがマスコット上にあるかどうかを検出できる
- uGUIの表示に対応（Button/Toggle/ToggleGroup/Image/Text）
- Unityメインウィンドウの非表示化、半透明化に対応
- MascotMakerMultiコンポーネントを使って複数のデスクトップマスコットを同時に表示できる
- 全てのコードがオープンソースです

<h1 class="title is-1">ご注意</h1>

- ビルドのターゲットとなるプラットフォームは Windows だけとなります


<h1 class="title is-1">どんなことができるか？</h1>

Unityを使って、ゲームを作るようにデスクトップマスコットを作れたら便利だと思いませんか？

DesktopMascotMakerは、Unity上でデスクトップマスコットを簡単に作ることができるアセットです。

# デスクトップマスコットのキャラクターを色んな角度から眺めることができる

![](project/desktopmascotmaker/images/niconi.gif)

# uGUIを利用してキャラクターに吹き出しやラベルを付けたり、ボタンで動かしたりする

Unity4.6から登場したuGUIの表示に対応しています。

uGUIのImageとTextを使って、キャラクターにセリフの吹き出しや、ラベルを付けることができます。

# Live2D/E-moteとの併用

Live2DやE-moteのUnityプラグインを併用すれば、2Dのキャラクターのデスクトップマスコット化も簡単です。

![](project/desktopmascotmaker/images/DesktopMascotMaker141221E.png)

# マウスイベントを使ってキャラクターとコミュニケーションする

デスクトップマスコット上では、マウスのクリック、ダブルクリック、マウスホイール等のイベント検出が可能です。これらのイベントを使って、キャラクターとのインタラクションを実装できます。

<h1 class="title is-1">どうやって使うの？</h1>

キャラクターを表示させるだけなら超簡単です！

キャラクターを表示するカメラに、DesktopMascotMakerのコンポーネントを１つ追加するだけです。

下図のように、カメラにMascotMaker（またはMascotMakerMulti）コンポーネントをアタッチします。

![](project/desktopmascotmaker/images/AttachMascotMaker.png)

キャラクターを表示させたら、そこからマウスイベントを追加したりカメラ／uGUIを操作するスクリプトを作ったりして、デスクトップマスコットらしく仕上げていきます。ここからが開発者さんの個性が出るところになります。

詳しくは、以下のドキュメントをご覧ください。

<h1 class="title is-1" name="doc">ドキュメントのダウンロード</h1>

<a href="https://www.assetstore.unity3d.com/en/#!/publisher/9484" TARGET="_blank" class="button is-large">ドキュメント Version 1.9.0 (2018/01/14) 最新版</a>

<a href="https://www.assetstore.unity3d.com/en/#!/publisher/9484" TARGET="_blank" class="button is-large">ドキュメント Version 1.8.0 (2016/02/10) for Unity 5</a>

<a href="https://www.assetstore.unity3d.com/en/#!/publisher/9484" TARGET="_blank" class="button is-large">ドキュメント Version 1.8.0 (2016/02/10) for Unity 4.6</a>

<h1 class="title is-1">デモプログラム</h1>

DesktopMascotMakerを使ったサンプルプログラムがいくつかあるので試しに使ってみてください。

# 基本的なデモ

この基本的なデモプログラムは、Desktop Mascot Makerのアセット内に含まれています。

![](project/desktopmascotmaker/images/DesktopMascotMakerDemo.jpg)

<a href="https://s3-us-west-2.amazonaws.com/panzersoft-assetstore/DesktopMascotMakerDemo200.zip" class="button is-large" target="_blank">基本的なデモのダウンロード</a>

# ニコニ立体ちゃんのデスクトップマスコット

パンツ丸見えのニコニ立体ちゃんのデスクトップマスコットです。

FinalIKを利用してこっちを見るようにしています

![](project/desktopmascotmaker/images/DesktopMascotMaker141221F.jpg)

<a href="https://bowlroll.net/file/55216" class="button is-large" target="_blank">ニコニ立体ちゃんのダウンロード（bowlroll）</a>

# ユニティちゃんライブのデスクトップマスコット

いきなり音がでるので注意して下さい

![](project/desktopmascotmaker/images/UnityChanLive4.gif)

<a href="https://bowlroll.net/file/55485" class="button is-large" target="_blank">ユニティちゃんライブのダウンロード（bowlroll）</a>


<h1 class="title is-1">Unityアセットストアで販売中</h1>

<a href="https://assetstore.unity.com/packages/templates/systems/desktop-mascot-maker-23732" class="button is-large is-success" target="_blank">アセットストアへ</a>

<h1 class="title is-1">無料トライアル版でお試し</h1>

機能無制限、利用期限なしの無料トライアル版がダウンロードできます。

<a href="https://s3-us-west-2.amazonaws.com/panzersoft-assetstore/DesktopMascotMakerTrial.zip" class="button is-large is-success" target="_blank">無料トライアル版をダウンロード</a>

<h1 class="title is-1">連絡先</h1>

トラブル、ご要望などございましたらこちらへお問い合わせ下さい。

<a href="https://www.assetstore.unity3d.com/en/#!/publisher/9484" TARGET="_blank" class="button is-large">お問い合わせ先</a>


<!--more-->
