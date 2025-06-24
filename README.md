# mastra-example-weather

mastra-example-weatherは、[mastra](https://github.com/mastra-ai/mastra)フレームワークを利用した天気情報取得のサンプルアプリケーションです。

## 機能
- 天気情報の取得エージェント/ツール/ワークフローの実装例
- mastraのエージェント・ツール・ワークフローの連携サンプル

## ディレクトリ構成

```
mastra-example-weather/
├── package.json
├── tsconfig.json
└── src/
    └── mastra/
        ├── index.ts
        ├── agents/
        │   └── weather-agent.ts
        ├── tools/
        │   └── weather-tool.ts
        └── workflows/
            └── weather-workflow.ts
```

## 必要要件
- Node.js >= 20.9.0
- TypeScript

## セットアップ

1. 依存パッケージのインストール

```sh
npm install
```

2. 開発サーバーの起動

```sh
npm run dev
```

3. ビルド

```sh
npm run build
```

4. 本番起動

```sh
npm start
```

## ライセンス

ISC
