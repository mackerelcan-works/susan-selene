Susan Selene / Dialogue Archive

構成:
/
  index.html        トップページ／記事一覧
  ogp.png           トップページ用OGP画像
  netlify.toml      Netlifyビルド設定（句読点の自動統一）
/taiyo/
  index.html        『太陽を盗んだ男』対話
  ogp.png           記事用OGP画像
/hipgnosis/
  index.html        『ヒプノシス　レコードジャケットの美学』対話
  have_a_cigar.jpg  『Have a Cigar』対訳画像

公開URL:
https://susan-selene.netlify.app/
https://susan-selene.netlify.app/taiyo/
https://susan-selene.netlify.app/hipgnosis/

運用:
GitHub リポジトリ mackerelcan-works/susan-selene を原本とし，Netlify が main ブランチを自動デプロイする。
新規記事や修正は作業ブランチで行い，Deploy Preview で確認したうえで main にマージする。
Netlify Drop にサイト一式を手動アップロードする運用は終了。

編集方針:
Susan Selene に書き出す日本語本文・見出し・説明文の句読点は「，」「。」に統一する。
通常のChatGPT上の対話ではこの規則を強制せず，Susan Selene 用に編集・書き出す段階で変換する。
引用画像など，画像そのものに含まれる文字組みは改変しない。
Netlify deploy 時にも netlify.toml により全HTMLの「、」を「，」へ自動変換し，書き出し時の取りこぼしを防ぐ。
