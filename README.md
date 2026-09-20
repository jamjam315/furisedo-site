# furisedo-site

「フリセド」（フリマ・せどりの損益管理アプリ）の案内サイト。
GitHub Pages で <https://furisedo.com/> に公開している。

| | |
|---|---|
| トップ | `index.html` |
| プライバシーポリシー | `privacy/index.html` → <https://furisedo.com/privacy/> |
| 免責事項 | `disclaimer/index.html` → <https://furisedo.com/disclaimer/> |

- **Play Console に登録するURLは `https://furisedo.com/privacy/`。** 一度登録したURLは消さない
  （消すと審査が通らなくなる。移動するときは転送ページを残す）
- 免責事項は**アプリ内の「設定 → 免責事項」と同じ文言**。正本はこのサイトで、アプリ側は写し
  （`furima` の `lib/domain/legal_text.dart`）。**片方だけ直さないこと**
- ビルド工程は無い。HTMLを直して `main` に push すれば反映される
