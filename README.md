# sample-playwright

## はじめに

このリポジトリは、PlaywrightとStorybookを組み合わせたテストコードのサンプルになります。

## 前提条件

* Node.js 18.12.1

## 使い方

任意のディレクトリでこのリポジトリをクローンします。
```
git clone https://github.com/kavis777/sample-playwright.git
```

クローンしたリポジトリに遷移して、パッケージをインストールします。
```
cd sample-playwright
npm install
npx playwright install
```

以下のコマンドでテストを実行します。

```
npm run test
```

テスト実行後に以下のコマンドを打つとレポートを確認できます。

```
npx playwright show-report
```
