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