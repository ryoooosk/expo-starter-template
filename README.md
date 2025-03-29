# Welcome to Ryoooosk Expo Starter Template

## Biome

[Biome](https://biomejs.dev/ja/)

### install

https://biomejs.dev/ja/guides/getting-started/

### Formatter

https://biomejs.dev/ja/formatter/

#### コードのフォーマットを無効にする

```js
// biome-ignore format: <説明文>
```

### Linter

https://biomejs.dev/ja/linter/

#### コードのリントを無効にする

```js
// biome-ignore lint: <explanation>
// biome-ignore lint/suspicious/noDebugger: <explanation>
```

### CLI

https://biomejs.dev/ja/reference/cli/

### 設定オプション

https://biomejs.dev/ja/reference/configuration/

## husky & lint-staged

[husky](https://typicode.github.io/husky/)  
Git のフック機能を使って、コミット前やプッシュ前に任意のスクリプトを実行できるツールです。コミット前にbiomeでリントとフォーマットを実行します。

[lint-staged](https://github.com/lint-staged/lint-staged)  
ステージングされた（= `git add` 済みの）ファイルに対してのみ処理を行うためのライブラリ。`husky`と組み合わせて、効率的にコードチェックを実施できます。
