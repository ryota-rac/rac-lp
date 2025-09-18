# R・A・C Landing Page (GitHub Pages)

静的LP（`index.html` + `assets/`）を **GitHub Pages** で公開するためのセットです。

## 公開手順（最短）
1. GitHubで新規リポジトリを作成（例: `rac-lp`）
2. このフォルダ内のファイル一式をアップロード（`index.html` と `assets/`、`.nojekyll` を含む）
3. リポジトリ → **Settings** → **Pages**  
   - **Build and deployment**: *Deploy from a branch*  
   - **Branch**: `main` ／ **Folder**: `/root`
4. 数分で **https://<yourname>.github.io/rac-lp/** が公開されます
5. Googleビジネスプロフィール：  
   - **ウェブサイト** → 上記URL  
   - **予約** → HPB: https://beauty.hotpepper.jp/kr/slnH000752648/coupon/

## 更新方法
- 画像は `assets/` を同名差し替え
- LINE友だち追加や地図リンクは `index.html` の該当hrefを書き換え→コミット

## （任意）独自ドメイン
- `Settings` → `Pages` → **Custom domain** にドメインを入力  
- 画面の指示どおりにDNS（CNAME）を設定  
- このリポジトリ直下に `CNAME` ファイルを置くと固定できます（例：`example.jp`）