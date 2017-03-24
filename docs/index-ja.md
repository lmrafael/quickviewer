---
layout: default
---

# [](#header-1)QuickViewer

**QuickViewer** は、たくさんの画像を快適に閲覧するための画像ビューアです。

画像データの読み込みを先回りして行い、読み込んだ画像データをOpenGLで画面に描画することで、これまでにない軽快さで画像を閲覧できるようになります。

**QuickViewer** は GPLv3 のフリーソフトウェアです。

[英語表記](https://kanryu.github.io/quickviewer/) / [日本語表記](https://kanryu.github.io/quickviewer/index-ja)

## 使い方


1. アプリを起動し、ウィンドウを表示します
1. メインメニューの選択してダイアログからフォルダを選ぶ、もしくはエクスプローラーから画像ファイルの入ったフォルダをアプリのウィンドウにDrag Dropします
1. 画面に読み込んだ画像が表示されます。ツールバーの「←」「→」ボタン、マウスホイール、マウスの進む戻るボタン、ウィンドウの左右端クリックなどで画像を切り替えます

## ダウンロード

[ビルド済みリリース版](https://github.com/kanryu/quickviewer/releases) (Windows x86/x64)

ソースコードについては [リポジトリ](https://github.com/kanryu/quickviewer) から最新のソースコードをcloneして入手してください。

## 機能紹介

### 通常表示(1ページ表示)

![通常表示](https://github.com/kanryu/quickviewer/wiki/images/singleview.jpg)

『見開き表示』をオフにしている場合、画面に画像を1枚表示します。

### 見開き表示


![見開き表示](https://github.com/kanryu/quickviewer/wiki/images/dualview.jpg)


『見開き表示』をオンにしている場合、画像を2枚横に並べて表示します。

## 画面の操作

画面の操作はメインメニュー、ツールバー、マウスボタン、ホイール、キーボードなどで行うことができます。

| 操作        | デバイス | 入力内容 | 備考 |
|:-------------|:-------|:--------|:--------|
| 次のページ | キーボード | 右キー(→) | |
|           | マウスホイール | 下回転 | |
|           | マウス | 進むボタン   | |
| 前のページ | キーボード | 左キー(←) | |
|           | マウスホイール | 上回転 | |
|           | マウス | 戻るボタン | |
| 全画面表示 | キーボード | F11キー | |
|           | キーボード | ESCキー | 全画面解除のみ |
|           | マウス | ホイールクリック | 中央ボタンクリック扱い |
| 画像拡大 | キーボード | テンキー(+) | フィット表示時使用不可 |
| 画像縮小 | キーボード | テンキー(-) | フィット表示時使用不可 |



```
The final element.
```