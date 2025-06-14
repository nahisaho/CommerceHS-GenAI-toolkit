# GitHub Pages 設定手順

このファイルは GitHub Pages の設定が完了したら削除してください。

## 🚨 重要：GitHub Pages を有効にしてください

現在、GitHub Pages が有効になっていないため、サイトにアクセスできません。
以下の手順で設定を完了してください：

## 📋 設定手順

### 1. GitHubリポジトリの設定ページを開く
1. ブラウザで [https://github.com/nahisaho/CommerceHS-GenAI-toolkit](https://github.com/nahisaho/CommerceHS-GenAI-toolkit) を開く
2. 画面上部の **Settings** タブをクリック

### 2. Pages設定を開く
1. 左サイドバーで **Pages** をクリック
2. "GitHub Pages" セクションが表示される

### 3. ソースを設定
**Source** セクションで以下を選択：
- **Deploy from a branch** を選択
- **Branch**: `main` を選択
- **Folder**: `/ (root)` を選択
- **Save** ボタンをクリック

### 4. 代替設定（推奨）
GitHub Actions を使用する場合：
- **Source** で **GitHub Actions** を選択
- 既に `.github/workflows/pages.yml` ファイルが用意されています

## ✅ 設定完了後

設定が完了すると、以下の URL でアクセスできるようになります：

- **メインサイト**: https://nahisaho.github.io/CommerceHS-GenAI-toolkit/
- **プレゼンテーション**: https://nahisaho.github.io/CommerceHS-GenAI-toolkit/presentation/

## ⏱️ 反映時間

- 初回設定：5-10分程度
- 更新反映：1-3分程度

## 🔍 設定確認方法

1. GitHubリポジトリの **Actions** タブで実行状況を確認
2. **Settings** > **Pages** で公開URLを確認
3. 緑色のチェックマークが表示されれば成功

## ❓ トラブルシューティング

### 404エラーが続く場合
1. **Settings** > **Pages** で正しい設定になっているか確認
2. **Actions** タブで最新のワークフローが成功しているか確認
3. ブラウザのキャッシュをクリア

### その他の問題
- リポジトリが **Public** になっていることを確認
- **Actions** の権限が有効になっていることを確認

---

**このファイルは設定完了後に削除してください。**