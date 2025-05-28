## アプリの起動方法

このアプリは [Next.js チュートリアル](https://nextjs.org/learn) をもとに作成されています。

### セットアップ手順

1. 本アプリを git clone する

```bash
git clone https://github.com/matsukenx/nextjs-dashborad.git
cd nextjs-dashborad
```

2. 依存パッケージのインストール

```bash
pnpm install
```

3. 開発サーバーの起動

```bash
pnpm dev
```

4. @matsukenx から `.env` ファイルを受け取り、プロジェクトルートに配置してください。

5. アプリケーションの秘密鍵を生成します。この鍵は Cookie を暗号化し、ユーザーセッションのセキュリティを確保するために使用されます。

macOS の場合、ターミナルで以下のコマンドを実行してください。

```bash
openssl rand -base64 32
```

Windows の場合、[こちらのサイト](https://generate-secret.vercel.app/32) で生成できます。

6. 生成したキーを `.env` ファイルの `AUTH_SECRET` 変数に追加してください。

```
AUTH_SECRET=your-secret-key
```

7. 初期データを投入するため、開発サーバー起動後にブラウザで `http://localhost:3000/seed` にアクセスしてください。

8. ブラウザで `http://localhost:3000` にアクセスしてください。

9. 完了です 🎉

## ログイン情報

テスト用ログインには以下の ID とパスワードを使用してください。

- ユーザー ID: `user@nextmail.com`
- パスワード: `123456`

---

> 本リポジトリは Next.js の公式チュートリアルを実装したものです。

---
