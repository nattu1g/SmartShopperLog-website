# SmartShopperLog Website

SmartShopperLogアプリのランディングページです。

## ローカルで確認

```bash
# Python 3
python3 -m http.server 8000

# または npx
npx serve .
```

ブラウザで http://localhost:8000 を開く

## デプロイ

### GitHub Pages
1. GitHubでリポジトリを作成
2. Settings → Pages → Source を「main」ブランチに設定
3. 自動的にデプロイされる

### Netlify
1. [Netlify](https://netlify.com) にログイン
2. 「Add new site」→「Import an existing project」
3. GitHubリポジトリを選択
4. デプロイ設定はデフォルトでOK

### Vercel
1. [Vercel](https://vercel.com) にログイン
2. 「New Project」→ GitHubリポジトリを選択
3. フレームワークは「Other」を選択
4. デプロイ

## ディレクトリ構成

```
website/
├── index.html      # メインページ
├── privacy.html    # プライバシーポリシー
├── terms.html      # 利用規約
├── css/
│   └── style.css   # スタイル
├── js/
│   └── main.js     # JavaScript
└── images/
    ├── app-mockup.png      # アプリ画像
    └── app-store-badge.svg # App Storeバッジ
```

## 画像の準備

`images/` ディレクトリに以下を配置：

1. **app-mockup.png** - アプリのスクリーンショット（推奨: 350px幅）
2. **app-store-badge.svg** - App Storeダウンロードバッジ
   - [Apple公式](https://developer.apple.com/app-store/marketing/guidelines/)からダウンロード
