# kgcc

> kgcc web

## インストールするもの

* [node](https://nodejs.org/ja/)
* [WinSCP](https://winscp.net/eng/docs/lang:jp)
* まともなテキストエディタ([VSCode](https://code.visualstudio.com/)推奨)
* Git

## ビルド

Clone したフォルダを開いて

```bash
# 依存関係のインストール
$ npm install # Or yarn install

# 開発用サーバーをlocalhost:3000で起動
$ npm run dev

# アップロード用の静的ページの生成
$ npm run generate
```

## ページの作成

`pages`フォルダの中に新しく作りたいページを作成します。

例えば、http://kgcc.hannnari.com/jikosyoukaiというページを作りたい場合、`pages/jikosyoukai.vue`というファイルを作成します。

次に、作成したファイルの中に以下をコピペします。

```html
<template>
  <h1 class=""></h1>
</template>
```

[Nuxt.js docs](https://github.com/nuxt/nuxt.js).
