# Playwright Test

Playwright は、Chromium、Firefox、WebKit を 1 つの API で自動化するためのNode.js ライブラリです。

https://playwright.dev/

## インストール方法

```
yarn create playwright
```

## 実行方法

- テスト実行
  ```
  npx playwright test
  ```

- 実行レポート表示
  ```
  npx playwright show-report
  ```

- 単一のテストをヘッドモードで実行する
  ```
  npx playwright test tests/example.spec.ts --headed
  ```

- 単一のテストをChromeのヘッドモードで実行する
  ```
  npx playwright test tests/example.spec.ts --headed  --project=chromium
  ```

- テストジェネレーターを起動
  ```
  npx playwright codegen playwright.dev
  ```

## 参考サイト
- [Fast and reliable end-to-end testing for modern web apps | Playwright](https://playwright.dev/)  
- [microsoft/playwright: Playwright is a framework for Web Testing and Automation. It allows testing Chromium, Firefox and WebKit with a single API.](https://github.com/microsoft/playwright)  
## 関連サイト
- [Playwrightを使ってブラウザ操作を自動化してみよう](https://zenn.dev/t_kitamura/articles/4a92f28b450a1c)  
- [Playwright でコンポーネントテスト](https://zenn.dev/azukiazusa/articles/playwright-component-testing)  
- [Playwrightを試してみた｜Next.js｜開発ブログ｜株式会社Nextat（ネクスタット）](https://nextat.co.jp/staff/archives/291)  
- [PlayWrightを用いたテスト自動化](https://www.cresco.co.jp/blog/entry/20355/)  
- [Playwright を使用してMicrosoft Edgeで自動化とテストを行う - Microsoft Edge Development | Microsoft Learn](https://learn.microsoft.com/ja-jp/microsoft-edge/playwright/)  
- [Playwrightも知らないで開発してる君たちへ - Qiita](https://qiita.com/cc822jp/items/6f786a9ed104af1a382f)  

