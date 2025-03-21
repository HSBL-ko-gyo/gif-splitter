# gif-splitter  
## アニメーションGIF分解ツール  

このツールは、GIFアニメーションを個別のフレームに分解し、連番のPNG画像として保存できるシンプルなウェブアプリケーションです。

## 機能

- GIFアニメーションをドラッグ＆ドロップまたはクリックして選択
- 各フレームをPNG形式で表示
- 個別フレームのダウンロード
- すべてのフレームをZIPファイルでまとめてダウンロード
- クライアントサイドで完結（サーバー不要）

## 使い方

1. [アニメーションGIF分解ツール](https://HSBL-ko-gyo.github.io/gif-splitter/)にアクセス
2. GIFファイルをドラッグ＆ドロップするか、クリックしてファイルを選択
3. GIFが処理され、各フレームが表示されます
4. 個別のフレームをダウンロードするか、「すべてのフレームをダウンロード」ボタンを使用

## 技術情報

- 純粋な HTML、CSS、JavaScript で実装
- [libgif-js](https://github.com/buzzfeed/libgif-js) - GIF処理ライブラリ
- [JSZip](https://stuk.github.io/jszip/) - ZIPファイル生成
- [FileSaver.js](https://github.com/eligrey/FileSaver.js/) - ファイル保存機能

## 使用ライブラリとライセンス

このプロジェクトでは以下のライブラリを使用しています。

- **libgif-js**
  - Copyright (c) 2011 Shachaf Ben-Kiki
  - MIT License
  - https://github.com/buzzfeed/libgif-js

- **JSZip**
  - Copyright (c) 2009-2016 Stuart Knightley, David Duponchel, Franz Buchinger, António Afonso
  - MIT License
  - https://github.com/Stuk/jszip

- **FileSaver.js**
  - Copyright © 2016 Eli Grey
  - MIT License
  - https://github.com/eligrey/FileSaver.js

## ローカルでの実行

このプロジェクトはシンプルな静的HTMLファイルとして実装されているため、特別なセットアップは必要ありません。

1. リポジトリをクローン: `git clone https://github.com/yourusername/gif-splitter.git`
2. `index.html` をブラウザで開く
