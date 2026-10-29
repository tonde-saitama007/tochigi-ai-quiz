# 栃木愛クイズ

スマートフォン対応・単一HTMLの無料クイズ。30問から重複なしで10問、各15秒、最大100点。

## 内容
- `index.html`：GitHub Pages公開用サイト（問題データを内蔵）
- `questions.json`：点検用問題データ（編集時は index.html と整合させる）
- `SOURCES.md`：設問ごとの公式出典

## 公開方法
1. GitHubで `tochigi-ai-quiz` 公開リポジトリを作成
2. ファイルを main に登録
3. Settings > Pages > Deploy from a branch > main / (root) を指定
4. https://tonde-saitama007.github.io/tochigi-ai-quiz/ の公開を確認
5. スマートフォンで開始・正誤・時間切れ・結果・PNGダウンロード・URLコピー・再挑戦を確認

## 公開・確認状況（2026年10月30日）
公開URL：https://tonde-saitama007.github.io/tochigi-ai-quiz/
main / (root) からGitHub Pagesで公開済み。

アプリ内ブラウザで確認済み：
- 10問進行、正解・誤答の採点と解説、結果・称号
- 15秒の時間切れ、再挑戦と得点初期化
- PNG実ファイル保存（1080×1080）と画像内容
- 320px・390px幅の表示、横方向のはみ出しなし
- JavaScript構文、30問の一意性・4択・正解番号、問題JSONとの一致

リンクコピーは成功表示を確認。コピー先URLはコードで確認済みですが、検証ブラウザの仮想クリップボードが空のため貼り付け内容の実確認は未完了です。
スマートフォン実機は未確認です。ユーザー自身が10問回答、PNG保存・閲覧、リンク貼り付け、再挑戦、画面の切れを確認してください。
既存4県への変更はありません。