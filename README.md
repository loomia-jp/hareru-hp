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

`index.html` のお問い合わせフォームは [Formspree](https://formspree.io) を利用します。
公開前に一度だけ次の設定が必要です：

1. https://formspree.io で無料アカウントを作成
2. フォームを作成し、エンドポイント URL を発行（例: `https://formspree.io/f/xxxxxxxx`）
3. `index.html` 内の `action="https://formspree.io/f/REPLACE_WITH_YOUR_FORM_ID"` を、発行された URL に差し替え

差し替えるまでフォーム送信は有効になりません（送信時はエラー表示になり、電話番号への連絡を案内します）。
