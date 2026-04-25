GitHub Pages 公開用ファイル一式です。

このフォルダ内のファイルを、GitHubリポジトリのルート直下にすべてアップロードしてください。

必要な配置:
- index.html
- myweb20240428_002.htm
- myweb20240428001001.jpg
- myweb20240428001002.jpg
- .nojekyll

GitHub 側の設定:
1. リポジトリの Settings を開く
2. Pages を開く
3. Build and deployment を「Deploy from a branch」にする
4. Branch を main、フォルダを /root にする
5. Save を押す

公開後のURL例:
https://ユーザー名.github.io/リポジトリ名/

修正内容:
- HTMLをShift_JIS/CP932からUTF-8に変換
- HTML内の文字コード指定をUTF-8に変更
- 古いHTML作成ソフト由来の unitless CSS（left:116; など）を left:116px; に補正
- 元の画像ファイル名・リンク先HTMLファイル名は維持
