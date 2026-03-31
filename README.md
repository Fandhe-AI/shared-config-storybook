# @fandhe-ai/shared-config-storybook

Storybook の共有設定。

## エクスポート

| パス | 説明 |
|------|------|
| `@fandhe-ai/shared-config-storybook/base` | 共有プレビューパラメータ（viewport プリセット・controls マッチャー） |

## 使用方法

`.storybook/preview.ts` で `parameters` を import して使用する:

```ts
import { parameters } from "@fandhe-ai/shared-config-storybook/base";

const preview = {
  parameters,
};

export default preview;
```

## 開発

### セットアップ

```bash
pnpm install
```

### コミット規約

[Conventional Commits](https://www.conventionalcommits.org/ja/) を採用。
[commitlint](https://commitlint.js.org/) + [lefthook](https://github.com/evilmartians/lefthook) により自動検証。

```
<type>: <description>

# 例
feat: 新しいルールを追加
fix: 設定の不具合を修正
chore: 依存関係を更新
```

## ライセンス

Copyright © Fandhe Inc.
