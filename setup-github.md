# GitHubリポジトリセットアップ手順

## 1. GitHubでリポジトリを作成
1. [GitHub.com](https://github.com) にログイン
2. 右上の「+」ボタン → 「New repository」
3. リポジトリ名を入力（例：`hajime-matsumoto`）
4. 説明を追加（オプション）
5. パブリック/プライベートを選択
6. 「Create repository」をクリック

## 2. リモートリポジトリの接続
GitHubでリポジトリを作成した後、以下のコマンドを実行：

```bash
# リモートリポジトリを追加（GitHubで作成したリポジトリのURLを使用）
git remote add origin https://github.com/[username]/[repository-name].git

# メインブランチをmainに変更（推奨）
git branch -M main

# 初回プッシュ
git push -u origin main
```

## 3. 今後の作業フロー
```bash
# 変更をステージング
git add .

# コミット
git commit -m "コミットメッセージ"

# リモートにプッシュ
git push origin main
```

## 注意事項
- `[username]` と `[repository-name]` を実際の値に置き換えてください
- GitHubでリポジトリを作成する際に「Initialize this repository with a README」のチェックを外してください（既にローカルにREADME.mdがあるため）
