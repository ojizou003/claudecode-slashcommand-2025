# Claude Code 統合スラッシュコマンドガイド

Claude Codeで利用可能なすべてのスラッシュコマンドを機能カテゴリ別に整理した統合ガイドのWebサイトです。

## 🌐 公開サイト

このサイトはGitHub Pagesで公開されています：
https://[username].github.io/claudecode-slashcommand-2025/

## 📋 機能

- **インタラクティブな検索**: コマンド名やキーワードでリアルタイム検索
- **カテゴリ別フィルター**: SCコマンド、Kiroコマンド、機能カテゴリでの絞り込み
- **タブ式ナビゲーション**: 機能カテゴリ別の整理された表示
- **ワークフロー例**: 開発パターン別のコマンド使用例
- **レスポンシブデザイン**: モバイル・デスクトップ両対応
- **日本語最適化**: Noto Sans JPフォントによる美しい日本語表示

## 🏗️ 技術スタック

- **HTML5** + **CSS3** + **Vanilla JavaScript**
- **GitHub Pages**（静的ホスティング）
- **レスポンシブデザイン**（モバイルファースト）
- **日本語対応**（Noto Sans CJK）

## 📁 プロジェクト構造

```
claudecode-slashcommand-2025/
├── index.html          # メインHTMLファイル
├── styles.css          # スタイルシート
├── script.js           # インタラクティブ機能
├── integrated_slash_commands.md  # 元のMarkdownファイル
├── README.md           # このファイル
└── .gitignore          # Git無視ファイル
```

## 🚀 ローカルでの実行

1. このリポジトリをクローン：
   ```bash
   git clone https://github.com/[username]/claudecode-slashcommand-2025.git
   cd claudecode-slashcommand-2025
   ```

2. お使いのブラウザで `index.html` を開くか、ローカルサーバーを起動：
   ```bash
   # Python 3の場合
   python -m http.server 8000

   # Node.jsの場合
   npx serve .

   # PHPの場合
   php -S localhost:8000
   ```

3. ブラウザで `http://localhost:8000` にアクセス

## 🎨 カスタマイズ

### テーマカラーの変更
`styles.css` の `:root` セクションでCSS変数を編集：

```css
:root {
    --primary-color: #2563eb;    /* メインカラー */
    --secondary-color: #10b981;  /* セカンダリカラー */
    --accent-color: #f59e0b;     /* アクセントカラー */
}
```

### フォントの変更
Google Fontsから別のフォントを選び、`index.html` のリンクと `styles.css` の `--font-family` 変数を更新。

### 新しいコマンドの追加
1. `index.html` の該当するテーブルに新しい行を追加
2. 適切なカテゴリとタグ（SC/Kiro）を設定
3. 必要に応じてフィルターロジックを更新

## 📱 ブラウザ対応

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 🤝 貢献

1. Fork
2. 機能ブランチ作成 (`git checkout -b feature/AmazingFeature`)
3. コミット (`git commit -m 'Add some AmazingFeature'`)
4. プッシュ (`git push origin feature/AmazingFeature`)
5. Pull Request

## 📄 ライセンス

このプロジェクトはMITライセンスの下で公開されています。詳細は [LICENSE](LICENSE) ファイルを参照してください。

## 🙏 謝辞

- [Google Fonts](https://fonts.google.com/) - Noto Sans JPフォント
- [GitHub Pages](https://pages.github.com/) - 静的サイトホスティング
- Claude Codeコミュニティ - 貴重なフィードバックと貢献

## 📞 連絡先

質問、提案、バグ報告については：
- GitHub Issues: [Create Issue](https://github.com/[username]/claudecode-slashcommand-2025/issues)
- Twitter: [@your_username](https://twitter.com/your_username)

---

⭐ このプロジェクトが役立った場合は、GitHubでスターを付けてください！