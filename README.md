# chatStats
Statsをchat形式で返却してくれるTwitter botです。

## 要件
GA数でしかサッカーを見れないことは1選手の能力や貢献度の理解を遠ざけます。

「この選手の何が良いの？」「ほかの選手と比べてどのくらい優れているの？」という素朴な疑問に対して、

FotMobの最新データをもとに分析した成績グラフを返却することで、その疑問を解決します。

## サンプルリソース
（１）攻撃系の成績
https://github.com/gundogan8/analyze/blob/main/code/Radars/Shooting_1on1.ipynb

（２）パス精度
https://github.com/gundogan8/analyze/blob/main/code/Beeswarms/Beeswarms.ipynb

（３）パスマップ
https://github.com/gundogan8/analyze/blob/main/code/Passmap/heat%20map%20tutorial.ipynb

## アーキテクチャ
- フロント
  - Next
  - TypeScript
- API
  - AWS lambda（Node.js）
  - Twitter Dev
  - TypeScript
- DB
  - none
- サーバ
  - AWS lambda（Node.js）
  - API Gateway

# 開発期間
１か月以内（YYYYMMDD開始）

## 開始要件
- 昔作成したアプリで利用したAWS lambdaの作業手順見返す
  - [ ] https://github.com/gundogan8/twitter-favorite-tutorial-sub
- Twitter Dev登録
  - [X] https://developer.twitter.com/en/portal/projects/1557313161698889728/apps/25116554/keys
