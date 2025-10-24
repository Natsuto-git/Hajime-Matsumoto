# Hajime Matsumoto - LotusCard プロフィールページ

モダンでクリーンなデザインのプロフィールページです。オレンジをテーマカラーとした、レスポンシブ対応のWebページです。

## 概要
このリポジトリはHajime Matsumotoのプロフィールページプロジェクトです。

## 特徴

- 🎨 **オレンジテーマ**: 温かみのあるオレンジカラーを基調としたデザイン
- 📱 **レスポンシブデザイン**: スマートフォンからデスクトップまで対応
- ⚡ **インタラクティブ**: スムーズなアニメーションとホバー効果
- 🔗 **ソーシャルリンク**: 各種SNSプラットフォームへのリンク
- 📇 **連絡先交換**: vCard形式での連絡先ダウンロード機能

## ファイル構成

```
├── index.html          # メインHTMLファイル
├── styles.css          # スタイルシート
├── script.js           # JavaScript機能
├── sw.js               # Service Worker
├── .gitignore          # Git除外設定
└── README.md           # このファイル
```

## 技術仕様

- **HTML5**: セマンティックなマークアップ
- **CSS3**: Flexbox、Grid、アニメーション
- **JavaScript (ES6+)**: モダンなJavaScript機能
- **Font Awesome**: アイコンライブラリ
- **Google Fonts**: Inter フォントファミリー

## セットアップ
```bash
# リポジトリのクローン
git clone https://github.com/Natsuto-git/Hajime-Matsumoto.git

# ディレクトリに移動
cd Hajime-Matsumoto

# ファイルをWebサーバーにアップロード
# または index.html をブラウザで開く
```

## 機能

### メイン機能
- プロフィール情報の表示
- ソーシャルメディアリンク
- 連絡先交換機能
- vCard形式での連絡先ダウンロード

### アニメーション
- ページ読み込み時のフェードイン効果
- ホバー時のスムーズなトランジション
- スクロール時の要素表示アニメーション

### レスポンシブ対応
- モバイルファーストデザイン
- タブレット・デスクトップ対応
- 柔軟なレイアウト調整

## 使用方法

1. ファイルをWebサーバーにアップロード
2. `index.html` をブラウザで開く
3. 各リンクやボタンでインタラクションを体験

## カスタマイズ

### 色の変更
`styles.css` の以下の変数を変更することで、テーマカラーを変更できます：

```css
/* メインカラー */
#ff6b35  /* オレンジ */
#ff8c42  /* ライトオレンジ */
#ffa726  /* ゴールドオレンジ */
```

### ソーシャルリンクの編集
`index.html` のソーシャルリンクセクションを編集して、自分のSNSアカウントに変更してください。

### プロフィール情報の変更
- プロフィール名: `.profile-name` クラス
- タイトル: `.title` クラス
- タグ: `.tags` セクション内の `.tag` 要素

## ブラウザ対応

- Chrome (最新版)
- Firefox (最新版)
- Safari (最新版)
- Edge (最新版)

## 貢献
プルリクエストやイシューの報告を歓迎します。

## ライセンス

MIT License

## 作者

LotusCard
- GitHub: [@LotusCard925](https://github.com/LotusCard925)
- Twitter: [@LotusCard925](https://twitter.com/LotusCard925)
