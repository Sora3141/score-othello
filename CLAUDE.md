# 点数オセロ

T.OF... のアプリ。https://t-of.github.io/score-othello/

- ルールは本部の `~/GitHub/tof/t-of.github.io/RULES.md` に従う（全アプリ共通）。ブランドは `docs/BRAND.md`。
- 直したら本部で `npm run audit:browser -- score-othello` を通す。
- 公開は本部の `docs/RELEASE.md` の手順。大きな作業は本部で Claude を起動すると、役割を分けて進められる。
- localStorage のキーは `score-othello.` で始める。SW のキャッシュ名は `score-othello-` で始める。
