# nextjs-python-test-blog

Next.js で Web サイトを作成。TailwindCSS でレイアウト調整。

Next.js のテストを学習。

jest, testing-library, next-page-tester

バックエンドは、[python_nextjs_test_blog_api](https://github.com/massu-159/python_nextjs_test_blog_api)

認証、CRUD 等の結合テスト

url はこちら
https://github.com/massu-159/nextjs-python-test-blog

## 目次

1. 環境構築
2. アプリケーションの仕様

## 1. 環境構築

### 1-1. ライブラリ インストール

```
npm install

または

yarn
```

### 1-2. アプリケーション実行

```
npm run dev

または

yarn dev
```

### 1-3. テスト実行

```
npm run test

または

yarn test
```

### 1-4. 環境変数の設定

ルートディレクトリ直下に`.env.local`ファイルを作成し、環境変数を設定する。

```
NEXT_PUBLIC_RESTAPI_URL = "https://XXXXXXXXXXX/api"
```

## 2. アプリケーションの仕様

### 2-1. 仕様

- ブログ
  - ブログ一覧
  - ブログ詳細
  - ブログ削除（ログイン後）
- 認証
  - ユーザー登録
  - ログイン
  - ログアウト

### 2-2. 構成技術

- react : 18.2.0
- react-dom : 18.2.0
- next : 12
- axios : 0.21.1
- autoprefixer : 10.4.5
- universal-cookie : 4.0.4
- msw : 0.39.2
- swr : 1.3.0
- @testing-library/jest-dom 　: 5.16.5
- @testing-library/react 　: 13.4.0
- @testing-library/user-event 　: 14.4.3
- next-page-tester : 0.32.0
- tailwindcss : 3.2.4
