# 警備検定ドリル

交通誘導警備業務検定2級の学科試験にそなえる学習アプリ「警備検定ドリル」の、サポートページ・プライバシーポリシー・利用規約・特定商取引法に基づく表記です。アプリは非公式の学習用アプリで、公的機関や団体とは関係がありません。収録している問題はオリジナルの予想問題で、実際の試験問題ではありません。

- トップ：https://hiromiokamura1002-art.github.io/keibi/
- サポート：https://hiromiokamura1002-art.github.io/keibi/support.html
- プライバシーポリシー：https://hiromiokamura1002-art.github.io/keibi/legal/privacy.html
- 利用規約：https://hiromiokamura1002-art.github.io/keibi/legal/terms.html
- 特定商取引法に基づく表記：https://hiromiokamura1002-art.github.io/keibi/legal/tokushoho.html

問い合わせ：elplancho.cheese@gmail.com（所在地・電話番号は載せません。特定商取引法の表記では「請求があれば遅滞なく開示」としています）

## 公開のしかた（GitHub Pages）

1. GitHub の右上「＋」→「New repository」→ 名前 `keibi`、**Public** で作る（アカウントは `hiromiokamura1002-art`）
2. このフォルダの中身（index.html・support.html・legal フォルダ・README.md・.nojekyll）をそのまま入れる（ブラウザなら「uploading an existing file」にまとめてドラッグ → 「Commit changes」。`legal` フォルダごと入れる）
3. リポジトリの **Settings → Pages** →「Build and deployment」の Source を **Deploy from a branch**、Branch を **main**、フォルダを **/ (root)** にして **Save**
4. 1〜5 分待って、上の 5 つの URL が iPhone の Safari でも開くことを確かめる

## 文面を直すとき

ここのファイルは、アプリのリポジトリ（非公開の `keibi-app`）の `src/lib/legalTexts.ts` から `npm run gen:legal` で書き出した `docs/index.html`・`docs/support.html`・`docs/legal/*.html` の写しです。ここを直接直さず、アプリ側で直して書き出してから写します（料金・基準日・注意書きを変えたときも同じ）。
