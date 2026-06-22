# PokeTrip

> **Status: 未完成の学習用アーカイブ（開発終了）**

PokeTripは、旅行とポケモンを組み合わせたWebアプリの着想から作成されたリポジトリです。ただし、現時点のコードは `create-next-app` が生成した初期テンプレートのみで、PokeTrip固有の画面、データモデル、API連携などは実装されていません。

完成したプロダクトやポートフォリオ作品として誤解されないよう、このリポジトリは「Next.jsプロジェクトを作成した段階の学習記録」として公開しています。新規開発のベースにはせず、実装を再開する場合は要件定義から新しいリポジトリで始めることを推奨します。

## 現在含まれるもの

- Next.js 15 App Routerの初期構成
- React 19、TypeScript、Tailwind CSS 4
- ESLint、型検査、production buildを確認するGitHub Actions

PokeTrip固有の機能、外部API、データベース、認証、テストはありません。APIキーなどの環境変数も不要です。

## ローカルで確認する

Node.js 20以上を使用します。

```bash
npm ci
npm run dev
```

[http://localhost:3000](http://localhost:3000) を開くと、Next.jsの初期画面が表示されます。

## 検証

```bash
npm run lint
npm run typecheck
npm run build
```

## 今後について

このリポジトリでは機能追加を予定していません。アイデアを再開する場合は、対象ユーザー、提供価値、利用する位置情報・コンテンツAPIとその利用規約を整理してから、別プロジェクトとして設計し直します。
