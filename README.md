# itouuuuuuuuu.github.io

伊藤 将史 (itouuuuuuuuu) のユーザーサイト。GitHub Pages で公開する静的サイトです。

## 目的

- 公開している OSS プロジェクトの一覧
- 寄付（Ko-fi / GitHub Sponsors）の案内
- 特定商取引法に基づく表記（Stripe 審査用）
- 問い合わせ窓口

## 公開 URL

| ページ | URL | 説明 |
| --- | --- | --- |
| トップ | <https://itouuuuuuuuu.github.io/> | プロフィールと公開中の OSS プロジェクト一覧 |
| サポート | <https://itouuuuuuuuu.github.io/sponsor.html> | Ko-fi / GitHub Sponsors を通じた寄付の案内 |
| 特定商取引法に基づく表記 | <https://itouuuuuuuuu.github.io/tokushoho.html> | OSS 開発への任意の寄付に関する販売事業者・支払方法・返金等の表記。Stripe 審査の提出 URL として使用 |
| お問い合わせ | <https://itouuuuuuuuu.github.io/contact.html> | 不具合報告・機能要望・その他連絡先 |

## ファイル構成

```
index.html       トップ（プロジェクト一覧）
sponsor.html     寄付の案内
contact.html     問い合わせ
tokushoho.html   特定商取引法に基づく表記
style.css        共通スタイル
```

ビルドツールは使用していません。`main` ブランチにプッシュすると GitHub Pages に反映されます。

## 新しい OSS プロジェクトを追加するとき

1. 該当リポジトリに `.github/FUNDING.yml` を追加（`ko_fi: itouuuuuuuuu`）
2. このリポジトリの `index.html` のプロジェクト一覧に追記
3. 必要に応じて `contact.html` の Issues リンクを追記

特商法ページとサポート方針は全プロジェクト共通です。
