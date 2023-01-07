# FotBot
欧州サッカー情報を配信するTwitter botです

# ソースの役割
- matchday.ipynb
  - プレミアリーグ(EPL)で注目しているクラブの試合日程と対戦相手をTwitter botで配信します
  - 本番用リソースはAWS lambdaで管理しています
  - 毎日00:00に作動します
  - [link](https://twitter.com/gundogan_vamos/status/1610805590913347584)

![matchday.ipynb](images/matchday.png)

- expire.ipynb
  - プレミアリーグ(EPL)所属選手の契約期間と年棒をTwitter botで配信します
  - 20クラブのうち1クラブをランダムに選択します
  - 本番用リソースはAWS lambdaで管理しています
  - 毎週金曜日17:00に作動します
  - [link](https://twitter.com/gundogan_vamos/status/1611570236473634818)

![matchday.ipynb](images/expire.png)

# 起動
```
jupyter-notebook
```