# [Google Apps Script](https://www.google.com/script/start/)

スプレッドシートやスライドの操作やその他Webアプリケーションや定期実行のプログラム実行環境として使用できるJavaScriptの実行環境。  
基本的にはコンソール上のエディタを使用してプログラムを記述する。

[@google/clasp](https://github.com/google/clasp) を使用することで、TypeScript を使用してプログラムを書くことも可能。

#### スキマ・漫画全巻での利用例
1. 週次ミーティングの資料のバックアップ
2. URLからQRコードの画像を複数枚発行する

## コンソール上からプログラムを実装する

### 1. プロジェクトを作成する

1. https://www.google.com/script/start/ にアクセス
2. 画面右上の「Start Scripting」をクリックする
3. 画面左上「新しいプロジェクト」をクリックする

### 2. プログラムを書いてみる

```javascript
function myFunction() {
    console.log('myFunction');
}
```

## TypeScrip を使用して、Apps Script を作成する

## Google Apps 以外のサービスを使用する