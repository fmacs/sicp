# 図書名
[図書リンク](https://www.seshop.com/product/detail/16888)

[日本語訳](https://sicp.iijlab.net/fulltext/xcont.html)

# 運用ルール
* 部活のMTGとは独立して実施すること
* 2021/6/13開始
* 毎週 日曜20:00〜21:00 実施(5分前ベル，5分後強制終了．BGMなりをうまく使う)
* ラウンドロビン形式で問題の答え合わせを実施（1MTG 10問）
* 会議する場所はgoogle meet(リンクはslackのチャンネルにて共有)
* コミュニケーションは以下で実施  
  https://masteringallt-qoq1317.slack.com/archives/C02451ML474


# 新規に参加する時
1. 本リポジトリをクローンする  
   `git clone git@github.com:fmacs/sicp.git`
2. `$YOUR_NAME`でブランチを切って切り替える    
   `git checkout -b $YOUR_NAME origin/main`
3. githubのリポジトリにpushする  
   `git push origin $YOUR_NAME`

# コードや資料を共有する時
1. 下記コマンドにて，ブランチを切り替える  
   `git checkout $YOUR_NAME`
2. 自分のブランチを最新状態にする  
   `git pull origin main`
3. 資料を追加する
   ```
   git add .
   git commit
   ```
4. 変更をpushする
   `git push origin $YOUR_NAME`
5. GUIでpullリクを作成し，mainにマージする．セルフマージでオッケー．


# 実行環境構築手順
下記docker imageを使用して，使い慣れたnotebookで環境を構築する  
https://github.com/Calysto/calysto_scheme
1. 下記コマンドを実行  
   `docker compose up -d`
2. http://localhost:8888  にアクセスする
