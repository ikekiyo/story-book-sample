# story-book-sample

Story BookのSample

## 環境構築手順

### react TypeScriptの構築

```bash
yarn create react-app . --template typescript
```

### Storybookの雛形作成

```bash
npx sb init
```

### インタラクションテスト関連のインストール

```bash
yarn add -D @storybook/addon-interactions @storybook/jest @storybook/testing-library @storybook/test-runner jest
```

- @storybook/addon-interactions - play() でのインタラクションを Storybook 上のタブで確認するためのアドオン
- @storybook/jest、@storybook/testing-library - Storybook用のTesting Library
- @storybook/test-runner - ストーリーをテストするためのテストランナー
- jest - @storybook/test-runner を動かすために必要です（peer dependency）

## 開発

### Storybook 起動

```bash
yarn storybook

╭───────────────────────────────────────────────────╮
│                                                   │
│   Storybook 6.5.12 for React started              │
│   13 s for preview                                │
│                                                   │
│    Local:                   │
│                                                   │
╰───────────────────────────────────────────────────╯
```

<http://localhost:6006/>
