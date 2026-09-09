# 🤝 Google Antigravity 2.0 ガイド 貢献ガイドライン（CONTRIBUTING.md）

「Google Antigravity 2.0 完全マスターズ・マニュアル」へのご興味・ご協力ありがとうございます！
本プロジェクトは、日本の開発者コミュニティ全体でより実用的で最新の知見を共有し合うことを目指しています。

どんな小さな修正（1文字の誤字脱字、リンク切れの報告など）でも大歓迎です！

---

## 🌟 どのような貢献を歓迎しているか？

- **誤字・脱字・表現の修正**: 日本語の言い回しの改善やタイポの修正。
- **最新仕様へのアップデート**: Google Antigravity、Gemini、MCP、Skillsなどの最新リリース情報の追記。
- **実践プロンプト・Tipsの共有**: 現場で実際に効果のあったプロンプト例やワークフロー。
- **不具合・表示崩れの報告**: モバイル表示時の崩れやCSSの不具合修正。
- **新しいプレイブックの追加**: 実用的な開発レシピやトラブルシューティング事例。

---

## 🛠 プルリクエスト（PR）の作成手順

初心者の方でも以下のステップに沿って簡単にPRを作成できます。

### 1. リポジトリを Fork & Clone する

右上の **「Fork」** ボタンをクリックし、ご自身のアカウントにリポジトリをフォークします。
フォークしたリポジトリをローカル環境にクローンします：

```bash
git clone https://github.com/<あなたのユーザー名>/google-antigravity-guide.git
cd google-antigravity-guide
```

### 2. 作業用ブランチを作成する

わかりやすいブランチ名を作成して切り替えます：

```bash
git checkout -b fix/typo-in-chapter-3
# または
git checkout -b feature/add-new-mcp-tip
```

### 3. ファイルを編集・確認する

- `index.html` をエディタで編集します。
- 編集後、ブラウザで `index.html` を直接開き、表示崩れやリンク切れがないか確認してください。

### 4. コミット & プッシュする

変更をコミットし、ご自身のフォーク先リポジトリへプッシュします：

```bash
git add index.html
git commit -m "docs: 第3章のプロンプト例に説明を追記"
git push origin fix/typo-in-chapter-3
```

### 5. プルリクエスト（Pull Request）を作成する

GitHubの元リポジトリ（`TsugawaTV/google-antigravity-guide`）を開くと、「**Compare & pull request**」ボタンが表示されます。
変更内容の要約を記載してPRを送信してください。

---

## 📝 執筆・編集時のガイドライン

1. **単一HTML完結の維持**:
   - `index.html` は外部CSSファイルやビルド不要で動作する単一HTMLファイルです。この構造を維持してください。
2. **デザイン・UI機構の保護**:
   - Tailwind CSS のユーティリティクラス、Prism.js によるハイライト、Mermaid.js による図解、左サイドバーの目次連動スクロール（ScrollSpy）が壊れないよう配慮してください。
3. **日本語表現**:
   - 読みやすく自然な口語的日本語（「〜ですね」「〜となります」等の過剰な敬語は控えめ）を心がけてください。
   - コード変数名・関数名・クラス名、ファイル名・パスは英語表記を維持してください。

---

## 💬 Issue（質問・提案）について

「PRを出すほどではないけれど、ここが間違っている」「こんな章を追加してほしい」といったご意見は、気軽に [GitHub Issues](https://github.com/TsugawaTV/google-antigravity-guide/issues) へ投稿してください。

みんなで最高の Antigravity ドキュメントを作っていきましょう！🚀
