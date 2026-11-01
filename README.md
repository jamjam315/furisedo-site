# furisedo-site

「フリセド」（フリマ・せどりの損益管理アプリ）の案内サイト。
GitHub Pages で <https://furisedo.com/> に公開している。

| | |
|---|---|
| トップ | `index.html` |
| プライバシーポリシー | `privacy/index.html` → <https://furisedo.com/privacy/> |
| 免責事項 | `disclaimer/index.html` → <https://furisedo.com/disclaimer/> |
| app-ads.txt | `app-ads.txt` → <https://furisedo.com/app-ads.txt>（AdMob の販売者の確認用。ストアに載せた開発者サイトのルートに置く必要がある） |

- **Play Console に登録するURLは `https://furisedo.com/privacy/`。** 一度登録したURLは消さない
  （消すと審査が通らなくなる。移動するときは転送ページを残す）
- 免責事項は**アプリ内の「設定 → 免責事項」と同じ文言**。正本はこのサイトで、アプリ側は写し
  （`furima` の `lib/domain/legal_text.dart`）。**片方だけ直さないこと**
- ビルド工程は無い。HTMLを直して `main` に push すれば反映される
- **`app-ads.txt` は場所と名前を変えない**（AdMob がこの URL を読みに来る）。中身は JAM の指定の行だけ（2026-11-01 に2行目を足した。既存の行は消さない）
