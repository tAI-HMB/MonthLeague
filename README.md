# Monthly League

キーワードと年月から、その月のスプラトゥーン3のルール・ステージ・ブキを決めるローテーションツール。

**公開URL:** https://tai-hmb.github.io/MonthLeague/

毎月、ルール1つ（ナワバリバトル＋ガチルール4種から）・ステージ3つ・ブキ5つが選ばれます。

## 使い方

URLパラメータで指定できます。

```
https://tai-hmb.github.io/MonthLeague/?keyword=いつものメンバー&ym=2026-10
```

| パラメータ | 内容 | 既定値 |
| --- | --- | --- |
| `keyword` | キーワード（同じキーワードなら同じ結果） | なし |
| `ym` | 年月（`YYYY-MM`） | 今月 |

## データの編集

ルール・ステージ・ブキの一覧は `data/` フォルダにあります。

- `data/rules.js` … ルール
- `data/stages.js` … ステージ
- `data/weapons.js` … ブキ（ブキ種別ごと）

## GitHub Pages の設定

1. リポジトリの **Settings → Pages** を開く
2. **Source** を `Deploy from a branch` にする
3. **Branch** を `main` / `/ (root)` にして Save

数分後に上の公開URLで見られるようになります。
