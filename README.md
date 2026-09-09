# 🚀 Google Antigravity 2.0 完全マスターズ・マニュアル

> **日本で最も詳しく、正確で実践的な Google Antigravity 2.0 完全攻略オープンソースガイド**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![GitHub Stars](https://img.shields.io/github/stars/TsugawaTV/google-antigravity-guide?style=social)](https://github.com/TsugawaTV/google-antigravity-guide)

---

## 📖 プロジェクトのビジョン

**Google Antigravity** は、従来のコード補完型（Copilot等）やサイドバー質問型（Cursor初期等）を超越した、Google DeepMind主導の**次世代・自律完走型（Agent-First）AI開発環境**です。

本プロジェクトは、日本のエンジニアコミュニティ全体で知見を結集し、**初級者からエンタープライズ・エキスパートまでが実務で即戦力として活用できる最高峰の完全網羅マニュアル**を共同で育てていくオープンソースプロジェクトです。

---

## ✨ 本マニュアルの特徴

1. **完全単一HTML完結（Zero Dependency Single-File HTML）**
   - 外部ビルドツール不要。ブラウザで `index.html` を開くだけで、Starlight / VitePress 級のリッチなUI（ダーク/ライトモード、検索、目次連動スクロール、シンタックスハイライト、Mermaid図解）が動作します。
2. **2026年最新仕様を完全網羅**
   - **Gemini 3.7 Flash** / **Claude 3.7 Sonnet & Opus 4.6 (thinking)** のエスカレーションモデル選定則。
   - **`/goal` による Autonomous Hill-Climbing 自律山登りループ**（Lighthouse All 100 達成実録）。
   - **Chrome DevTools MCP** / **Modern Web Guidance Plugin** 連携。
   - **WordPress 開発セキュリティ5原則（完全コード集）**。
   - **Git Worktree 分離並行開発アーキテクチャ**。
3. **コピペで即動く実戦プロンプト ＆ 設定ファイル集**
   - `GEMINI.md`、`.agent/hooks.json`、`.agent/workflows/`、`mcp_config.json`、Python SDK 完全スクリプトを収録。

---

## 📑 目次一覧

- **はじめに**
- **第1章：Antigravity 概要とアーキテクチャ**
  - 1.1 Agent-First 開発思想の革命
  - 1.2 プロダクトラインナップ（2.0 司令塔 vs IDE vs CLI vs SDK）
  - 1.3 バックエンドモデルの選定指針 & 料金・レート制限
- **第2章：コア概念と「Artifacts（成果物）」システム**
  - 2.1 Artifacts システム（implementation_plan.md / walkthrough.md）
  - 2.2 レビュー駆動開発（RDD）& インラインコメント機能
  - 2.3 Local Mode vs New Worktree Mode
  - 2.4 推論努力度（Reasoning Effort）の設定指針 & 判断マトリクス
- **第3章：スラッシュコマンド完全マスター**
  - 3.1 `/goal` 自律完走指示（Autonomous Hill-Climbing ループ）
  - 3.2 `/grill-me` 要件定義・インタビュー
  - 3.3 `/browser` Chrome 操作 & ブラウザ自動化3大ルート比較
  - 3.4 `/schedule` 定期実行 & タイマータスク（SDLC自動化）
  - 3.5 カスタムワークフローの自作（`.agent/workflows/`）
- **第4章：高度な自律オーケストレーション**
  - 4.1 Dynamic Subagents（動的サブエージェント）とコンテキスト保護
  - 4.2 非同期タスク管理 & システムトレイ常駐
  - 4.3 JSON Lifecycle Hooks（ライフサイクルフック）
  - 4.4 セキュリティ・権限ポリシー & カーネルサンドボックス（Seatbelt / nsjail）
- **第5章：Skills・MCP・Python SDK 連携**
  - 5.1 Agent Skills 仕様と Progressive Disclosure
  - 5.2 Model Context Protocol (MCP) サーバー連携（Chrome DevTools MCP）
  - 5.3 Google Antigravity Python SDK 実践プログラミング
  - 5.4 Build with Google Plugins と Agent Plugin Spec
- **第6章：実戦プレイブック（即戦力レシピ）**
  - 6.1 フルスタックWebアプリのゼロイチ高速開発
  - 6.2 B2B SaaS コンバージョン特化 LP 高速作成
  - 6.3 大規模レガシーコードのリファクタリング（Worktree + TDD）
  - 6.4 **実録：Gemini 3.7 Flash × /goal による Lighthouse All 100 ＆ モダンWeb完全移行**
  - 6.5 **WordPress プラグイン開発の完全手順（セキュリティ5原則・WPCS規約）**
- **第7章：プロンプトエンジニアリング ＆ トラブルシューティング**
  - 7.1 自律エージェントを迷走させない制約条件（Constraints）
  - 7.2 知識永続化（実務推奨 `GEMINI.md` 完全テンプレート）
  - 7.3 よくある失敗と対処一覧表（トラブルシューティング）
- **付録：プロ向け実践チェックリスト ＆ リファレンス**
  - A.1 プロフェッショナル開発チェックリスト（4領域）
  - A.2 公式ドキュメント & 参考リソースリンク集
  - A.3 Windows / macOS 主要キーボードショートカット一覧

---

## 💻 ローカルでの閲覧方法

本リポジトリをクローン後、HTMLファイルを直接お好きなブラウザで開くだけです。

```bash
git clone https://github.com/TsugawaTV/google-antigravity-guide.git
cd google-antigravity-guide

# お使いのブラウザで開く（例: macOS）
open index.html

# Windows PowerShell の場合
Start-Process index.html
```

---

## 🤝 コミュニティへの貢献（Contribute）

本プロジェクトはオープンソースです。皆様からの改善提案を心よりお待ちしております！

- 誤字・脱字の修正
- 最新アップデート情報の追記
- 実務で役立ったプロンプトやワークフローの追加
- わかりにくい箇所の表現改善

詳しい手順は [CONTRIBUTING.md](CONTRIBUTING.md) をご覧ください。

---

## 📄 ライセンス

本ドキュメントおよびコードは [MIT License](LICENSE) のもとで公開されています。
