# Monthly League

キーワードと年月から、その月のスプラトゥーン3のルール・ステージ・ブキを決めるローテーションツール。

**公開URL:** https://tai-hmb.github.io/MonthLeague/

## 使い方

URLパラメータで指定できます。

```
https://tai-hmb.github.io/MonthLeague/?keyword=いつものメンバー&ym=2026-10
```

| パラメータ | 内容 | 既定値 |
| --- | --- | --- |
| `keyword` | キーワード（同じキーワードなら同じ結果） | なし |
| `ym` | 年月（`YYYY-MM`） | 今月 |
| `stages` | ステージ数（1〜10） | 3 |
| `weapons` | ブキ数（1〜16） | 4 |
| `nawabari` | `1` でナワバリバトルを含める | なし |

## GitHub Pages の設定

1. リポジトリの **Settings → Pages** を開く
2. **Source** を `Deploy from a branch` にする
3. **Branch** を `main` / `/ (root)` にして Save

数分後に上の公開URLで見られるようになります。
