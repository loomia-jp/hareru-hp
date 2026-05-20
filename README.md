# はれる コーポレートサイト

合同会社にじが運営する就労継続支援B型事業所「はれる」の公式サイト。

## 構成

- 純粋な静的サイト（HTML / CSS / JS / 画像）
- ビルド不要・依存関係なし
- Vercel / Netlify / GitHub Pages いずれでもそのままデプロイ可能

## ファイル

| ファイル | 内容 |
| --- | --- |
| `index.html` | トップページ |
| `works.html` | 作品ギャラリー |
| `scenes.html` | 作業風景 |
| `iphone-preview.html` | iPhone 表示プレビュー（任意） |
| `assets/` | 画像 |

## ローカルで確認

ファイルをブラウザで開くだけ：

```
open index.html
```

## デプロイ

GitHub に push → Vercel が自動で再デプロイ。

## お問い合わせフォーム

`index.html` のお問い合わせフォームは [Formspree](https://formspree.io) 経由でメール送信されます（接続済み）。フォームから送信された内容は、Formspree に登録したメールアドレスに届きます。送信先の変更や受信履歴の確認は Formspree の管理画面から行えます。
